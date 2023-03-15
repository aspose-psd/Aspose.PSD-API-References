---
title: VmskResource.VmskResource
second_title: .NET API 참조용 Aspose.PSD
description: VmskResource 건설자. 의 새 인스턴스를 초기화합니다.VmskResource 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
## VmskResource(byte[]) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`VmskResource`](../) 클래스.

```csharp
public VmskResource(byte[] data)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| data | Byte[] | 리소스 데이터입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 잘못된 Vmsk 리소스 값 |

### 또한보십시오

* class [VmskResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* 집회 [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

의 새 인스턴스를 초기화합니다.[`VmskResource`](../) 클래스.

```csharp
public VmskResource()
```

### 예

다음 코드 예제에서는 벡터 경로 개체를 조작하는 클래스를 제공하고 해당 클래스를 사용하는 방법을 보여 줍니다.

```csharp
[C#]

public void CreatingVectorPathExample(string outputPsd = "outputPsd.psd")
{
    using (var psdImage = (PsdImage)Image.Create(new PsdOptions() { Source = new StreamSource(new MemoryStream()), }, 500, 500))
    {
        FillLayer layer = FillLayer.CreateInstance(FillType.Color);
        psdImage.AddLayer(layer);

        VectorPath vectorPath = VectorDataProvider.CreateVectorPathForLayer(layer);
        vectorPath.FillColor = Color.IndianRed;
        PathShape shape = new PathShape();
        shape.Points.Add(new BezierKnot(new PointF(50, 150), true));
        shape.Points.Add(new BezierKnot(new PointF(100, 200), true));
        shape.Points.Add(new BezierKnot(new PointF(0, 200), true));
        vectorPath.Shapes.Add(shape);
        VectorDataProvider.UpdateLayerFromVectorPath(layer, vectorPath, true);

        psdImage.Save(outputPsd);
    }
}

#region Vector path editor (Here placed classes for edit vector paths).

/// <summary>
/// <see cref="Layer"/> 및 <see cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// <see cref="VectorPath"/> 입력 레이어의 리소스를 기반으로 하는 인스턴스.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    /// <returns>the <see cref="VectorPath"/> instance based on resources from input layer.</returns>
    public static VectorPath CreateVectorPathForLayer(Layer psdLayer)
    {
        ValidateLayer(psdLayer);

        Size imageSize = psdLayer.Container.Size;

        VectorPathDataResource pathResource = FindVectorPathDataResource(psdLayer, true);
        SoCoResource socoResource = FindSoCoResource(psdLayer, true);
        VectorPath vectorPath = new VectorPath(pathResource, imageSize);
        if (socoResource != null)
        {
            vectorPath.FillColor = socoResource.Color;
        }

        return vectorPath;
    }

    /// <summary>
    /// <see cref="VectorPath"/>에서 입력 레이어 리소스를 업데이트합니다. 인스턴스를 변경하거나 새 경로 리소스 및 업데이트로 교체합니다.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    /// <param name="vectorPath">벡터 경로입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    public static void UpdateLayerFromVectorPath(Layer psdLayer, VectorPath vectorPath, bool createIfNotExist = false)
    {
        ValidateLayer(psdLayer);

        VectorPathDataResource pathResource = FindVectorPathDataResource(psdLayer, createIfNotExist);
        VogkResource vogkResource = FindVogkResource(psdLayer, createIfNotExist);
        SoCoResource socoResource = FindSoCoResource(psdLayer, createIfNotExist);

        Size imageSize = psdLayer.Container.Size;
        UpdateResources(pathResource, vogkResource, socoResource, vectorPath, imageSize);

        ReplaceVectorPathDataResourceInLayer(psdLayer, pathResource, vogkResource, socoResource);
    }

    /// <summary>
    /// 입력 레이어에서 벡터 경로 데이터를 제거합니다.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    public static void RemoveVectorPathDataFromLayer(Layer psdLayer)
    {
        List<LayerResource> oldResources = new List<LayerResource>(psdLayer.Resources);
        List<LayerResource> newResources = new List<LayerResource>();
        for (int i = 0; i < oldResources.Count; i++)
        {
            LayerResource resource = oldResources[i];

            if (resource is VectorPathDataResource || resource is VogkResource || resource is SoCoResource)
            {
                continue;
            }
            else
            {
                newResources.Add(resource);
            }
        }

        psdLayer.Resources = newResources.ToArray();
    }

    /// <summary>
    /// <see cref="VectorPath"/>에서 리소스 데이터를 업데이트합니다. 사례.
    /// </summary>
    /// <param name="pathResource">경로 리소스입니다.</param>
    /// <param name="vogkResource">벡터 원본 데이터 리소스입니다.</param>
    /// <param name="socoResource">단색 리소스입니다.</param>
    /// <param name="vectorPath">벡터 경로입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    private static void UpdateResources(VectorPathDataResource pathResource, VogkResource vogkResource, SoCoResource socoResource, VectorPath vectorPath, Size imageSize)
    {
        pathResource.Version = vectorPath.Version;
        pathResource.IsNotLinked = vectorPath.IsNotLinked;
        pathResource.IsDisabled = vectorPath.IsDisabled;
        pathResource.IsInverted = vectorPath.IsInverted;

        List<VectorShapeOriginSettings> originSettings = new List<VectorShapeOriginSettings>();
        List<VectorPathRecord> path = new List<VectorPathRecord>();
        path.Add(new PathFillRuleRecord(null));
        path.Add(new InitialFillRuleRecord(vectorPath.IsFillStartsWithAllPixels));
        for (ushort i = 0; i < vectorPath.Shapes.Count; i++)
        {
            PathShape shape = vectorPath.Shapes[i];
            shape.ShapeIndex = i;
            path.AddRange(shape.ToVectorPathRecords(imageSize));
            originSettings.Add(new VectorShapeOriginSettings() { IsShapeInvalidated = true, OriginIndex = i });
        }

        pathResource.Paths = path.ToArray();
        vogkResource.ShapeOriginSettings = originSettings.ToArray();

        socoResource.Color = vectorPath.FillColor;
    }

    /// <summary>
    /// 레이어의 리소스를 업데이트되거나 새로운 리소스로 바꿉니다.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    /// <param name="pathResource">경로 리소스입니다.</param>
    /// <param name="vogkResource">벡터 원본 데이터 리소스입니다.</param>
    /// <param name="socoResource">단색 리소스입니다.</param>
    private static void ReplaceVectorPathDataResourceInLayer(Layer psdLayer, VectorPathDataResource pathResource, VogkResource vogkResource, SoCoResource socoResource)
    {
        bool pathResourceExist = false;
        bool vogkResourceExist = false;
        bool socoResourceExist = false;

        List<LayerResource> resources = new List<LayerResource>(psdLayer.Resources);
        for (int i = 0; i < resources.Count; i++)
        {
            LayerResource resource = resources[i];
            if (resource is VectorPathDataResource)
            {
                resources[i] = pathResource;
                pathResourceExist = true;
            }
            else if (resource is VogkResource)
            {
                resources[i] = vogkResource;
                vogkResourceExist = true;
            }
            else if (resource is SoCoResource)
            {
                resources[i] = socoResource;
                socoResourceExist = true;
            }
        }

        if (!pathResourceExist)
        {
            resources.Add(pathResource);
        }

        if (!vogkResourceExist)
        {
            resources.Add(vogkResource);
        }

        if (!socoResourceExist)
        {
            resources.Add(socoResource);
        }

        psdLayer.Resources = resources.ToArray();
    }

    /// <summary>
    /// <see cref="VectorPathDataResource"/> 입력 레이어 리소스의 리소스.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    /// <param name="createIfNotExist">리소스가 존재하지 않으면 <see cref="true"/> 새 리소스를 생성하고 그렇지 않으면 <see cref="null"/>.</param>을 반환합니다.
    /// <returns>The <see cref="VectorPathDataResource"/> resource.</returns>
    private static VectorPathDataResource FindVectorPathDataResource(Layer psdLayer, bool createIfNotExist = false)
    {
        VectorPathDataResource pathResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is VectorPathDataResource)
            {
                pathResource = (VectorPathDataResource)resource;
                break;
            }
        }

        if (createIfNotExist && pathResource == null)
        {
            pathResource = new VmskResource();
        }

        return pathResource;
    }

    /// <summary>
    /// <see cref="VogkResource"/> 입력 레이어 리소스의 리소스.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    /// <param name="createIfNotExist">리소스가 존재하지 않으면 <see cref="true"/> 새 리소스를 생성하고 그렇지 않으면 <see cref="null"/>.</param>을 반환합니다.
    /// <returns>The <see cref="VogkResource"/> resource.</returns>
    private static VogkResource FindVogkResource(Layer psdLayer, bool createIfNotExist = false)
    {
        VogkResource vogkResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is VogkResource)
            {
                vogkResource = (VogkResource)resource;
                break;
            }
        }

        if (createIfNotExist && vogkResource == null)
        {
            vogkResource = new VogkResource();
        }

        return vogkResource;
    }

    /// <summary>
    /// <see cref="SoCoResource"/> 입력 레이어 리소스의 리소스.
    /// </summary>
    /// <param name="psdLayer">PSD 레이어입니다.</param>
    /// <param name="createIfNotExist">리소스가 존재하지 않으면 <see cref="true"/> 새 리소스를 생성하고 그렇지 않으면 <see cref="null"/>.</param>을 반환합니다.
    /// <returns>The <see cref="SoCoResource"/> resource.</returns>
    private static SoCoResource FindSoCoResource(Layer psdLayer, bool createIfNotExist = false)
    {
        SoCoResource socoResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is SoCoResource)
            {
                socoResource = (SoCoResource)resource;
                break;
            }
        }

        if (createIfNotExist && socoResource == null)
        {
            socoResource = new SoCoResource();
        }

        return socoResource;
    }

    /// <summary>
    /// <see cref="VectorDataProvider"/>와 함께 작동하도록 계층을 검증합니다. 수업.
    /// </summary>
    /// <param name="layer"></param>
    /// <예외 cref="ArgumentNullException"></exception>
    private static void ValidateLayer(Layer layer)
    {
        if (layer == null)
        {
            throw new ArgumentNullException("The layer is NULL.");
        }

        if (layer.Container == null || layer.Container.Size.IsEmpty)
        {
            throw new ArgumentNullException("The layer should have a Container with no empty size.");
        }
    }
}

/// <summary>
/// Bezier 곡선 매듭, 하나의 고정점과 두 개의 제어점을 포함합니다.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// 경로 포인트 비율에 대한 이미지.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// <see cref="BezierKnot" />의 새 인스턴스를 초기화합니다. 수업.
    /// </summary>
    /// <param name="anchorPoint">앵커 포인트입니다.</param>
    /// <param name="controlPoint1">첫 번째 제어점입니다.</param>
    /// <param name="controlPoint2">두 번째 제어점.</param>
    /// <param name="isLinked">이 매듭의 연결 여부를 나타내는 값.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// <see cref="BezierKnot" />의 새 인스턴스를 초기화합니다. <see cref="BezierKnotRecord"/>에 기반한 클래스입니다.
    /// </summary>
    /// <param name="bezierKnotRecord"><see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// <see cref="BezierKnot" />의 새 인스턴스를 초기화합니다. 수업.
    /// </summary>
    /// <param name="anchorPoint">앵커가 될 포인트와 제어 포인트.</param>
    /// <param name="isLinked">이 매듭의 연결 여부를 나타내는 값.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// 이 인스턴스가 연결되었는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// 첫 번째 제어점을 가져오거나 설정합니다.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// 앵커 포인트를 가져오거나 설정합니다.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// 두 번째 제어점을 가져오거나 설정합니다.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// <see cref="BezierKnotRecord"/> 이 인스턴스를 기반으로 합니다.
    /// </summary>
    /// <param name="isClosed">이 매듭이 닫힌 모양인지 여부를 나타냅니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    /// <returns>The instance of <see cref="BezierKnotRecord"/> based on this instance.</returns>
    public BezierKnotRecord ToBezierKnotRecord(bool isClosed, Size imageSize)
    {
        BezierKnotRecord record = new BezierKnotRecord();
        record.Points = new Point[]
        {
            PointFToResourcePoint(this.ControlPoint1, imageSize),
            PointFToResourcePoint(this.AnchorPoint, imageSize),
            PointFToResourcePoint(this.ControlPoint2, imageSize),
        };
        record.IsLinked = this.IsLinked;
        record.IsClosed = isClosed;

        return record;
    }

    /// <summary>
    /// 이 노트 포인트를 입력 값으로 이동합니다.
    /// </summary>
    /// <param name="xOffset">x 오프셋입니다.</param>
    /// <param name="yOffset">y 오프셋입니다.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// 포인트 값을 리소스에서 일반으로 변환합니다.
    /// </summary>
    /// <param name="point">resource.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// 일반 포인트 값을 리소스 포인트로 변환합니다.
    /// </summary>
    /// <param name="point">점입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// 베지어 곡선의 매듭에서 나온 그림.
/// </summary>
public class PathShape
{
    /// <summary>
    /// <see cref="PathShape" />의 새 인스턴스를 초기화합니다. 수업.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <see cref="PathShape" />의 새 인스턴스를 초기화합니다. <see cref="VectorPathRecord"/>에 기반한 클래스입니다.
    /// </summary>
    /// <param name="lengthRecord">레코드 길이입니다.</param>
    /// <param name="bezierKnotRecords">베지어 매듭 레코드입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <값>
    /// <c>참</c> 이 인스턴스가 닫히면; 그렇지 않으면 <c>false</c>입니다.
    /// </값>
    public bool IsClosed { get; set; }

    /// <summary>
    /// 경로 연산(부울 연산)을 가져오거나 설정합니다.
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// 레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// 베지어 곡선의 점을 가져옵니다.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// <see cref="VectorPathRecord"/> 이 인스턴스를 기반으로 하는 레코드입니다.
    /// </summary>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    /// <returns>Returns one <see cref="LengthRecord"/> and <see cref="BezierKnotRecord"/> for each point in this instance.</returns>
    public IEnumerable<VectorPathRecord> ToVectorPathRecords(Size imageSize)
    {
        List<VectorPathRecord> shapeRecords = new List<VectorPathRecord>();

        LengthRecord lengthRecord = new LengthRecord();
        lengthRecord.IsClosed = this.IsClosed;
        lengthRecord.BezierKnotRecordsCount = this.Points.Count;
        lengthRecord.PathOperations = this.PathOperations;
        lengthRecord.ShapeIndex = this.ShapeIndex;
        shapeRecords.Add(lengthRecord);

        foreach (var bezierKnot in this.Points)
        {
            shapeRecords.Add(bezierKnot.ToBezierKnotRecord(this.IsClosed, imageSize));
        }

        return shapeRecords;
    }

    /// <summary>
    /// 입력 레코드를 기반으로 값을 초기화합니다.
    /// </summary>
    /// <param name="bezierKnotRecords">베지어 매듭 레코드입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    private void InitFromResources(IEnumerable<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    {
        List<BezierKnot> newPoints = new List<BezierKnot>();

        foreach (var record in bezierKnotRecords)
        {
            newPoints.Add(new BezierKnot(record, imageSize));
        }

        this.Points = newPoints;
    }
}

/// <summary>
/// 벡터 경로를 포함하는 클래스.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// <see cref="VectorPath" />의 새 인스턴스를 초기화합니다. <see cref="VectorPathDataResource"/>를 기반으로 하는 클래스입니다.
    /// </summary>
    /// <param name="vectorPathDataResource">벡터 경로 데이터 리소스입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// 채우기가 모든 픽셀로 시작하는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <값>
    /// 채우기는 모든 픽셀에서 시작합니다.
    /// </값>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// 벡터 모양을 가져옵니다.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// 벡터 경로 채우기 색상을 가져오거나 설정합니다.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// 버전을 가져오거나 설정합니다.
    /// </summary>
    /// <값>
    /// 버전.
    /// </값>
    public int Version { get; set; }

    /// <summary>
    /// 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <값>
    /// <c>참</c> 이 인스턴스가 비활성화된 경우 그렇지 않으면 <c>false</c>입니다.
    /// </값>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <값>
    /// <c>참</c> 이 인스턴스가 연결되지 않은 경우; 그렇지 않으면 <c>false</c>입니다.
    /// </값>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <값>
    /// <c>참</c> 이 인스턴스가 반전된 경우; 그렇지 않으면 <c>false</c>입니다.
    /// </값>
    public bool IsInverted { get; set; }

    /// <summary>
    /// 입력 <see cref="VectorPathDataResource"/>를 기반으로 값을 초기화합니다. 자원.
    /// </summary>
    /// <param name="resource">벡터 경로 데이터 리소스입니다.</param>
    /// <param name="imageSize"> 변환점 좌표를 보정하기 위한 이미지 크기.</param>
    private void InitFromResource(VectorPathDataResource resource, Size imageSize)
    {
        List<PathShape> newShapes = new List<PathShape>();
        InitialFillRuleRecord initialFillRuleRecord = null;
        LengthRecord lengthRecord = null;
        List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

        foreach (var pathRecord in resource.Paths)
        {
            if (pathRecord is LengthRecord)
            {
                if (bezierKnotRecords.Count > 0)
                {
                    newShapes.Add(new PathShape(lengthRecord, bezierKnotRecords, imageSize));
                    lengthRecord = null;
                    bezierKnotRecords.Clear();
                }

                lengthRecord = (LengthRecord)pathRecord;
            }
            else if (pathRecord is BezierKnotRecord)
            {
                bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
            }
            else if (pathRecord is InitialFillRuleRecord)
            {
                initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            }
        }

        if (bezierKnotRecords.Count > 0)
        {
            newShapes.Add(new PathShape(lengthRecord, bezierKnotRecords, imageSize));
            lengthRecord = null;
            bezierKnotRecords.Clear();
        }

        this.IsFillStartsWithAllPixels = initialFillRuleRecord != null ? initialFillRuleRecord.IsFillStartsWithAllPixels : false;
        this.Shapes = newShapes;

        this.Version = resource.Version;
        this.IsNotLinked = resource.IsNotLinked;
        this.IsDisabled = resource.IsDisabled;
        this.IsInverted = resource.IsInverted;
    }
}

#endregion
```

### 또한보십시오

* class [VmskResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* 집회 [Aspose.PSD](../../../)


