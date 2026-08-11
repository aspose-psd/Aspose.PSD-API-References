---
title: "VmskResource.VmskResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VmskResource 생성자. VmskResource 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
{{< psd/tize >}}
## VmskResource(byte[]) {#constructor_1}

`[`VmskResource`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public VmskResource(byte[] data)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | Byte[] | 리소스 데이터. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 잘못된 Vmsk Resource 값 |

### 또 보기

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

`[`VmskResource`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public VmskResource()
```

## 예제

다음 코드 예제는 벡터 경로 객체를 조작하는 클래스를 제공하고 해당 클래스를 사용하는 방법을 보여줍니다.

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
/// <see cref=\"Layer\"/>와 <see cref=\"VectorPath\"/> 사이의 작업을 제공하는 클래스.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// 입력 레이어의 리소스를 기반으로 <see cref=\"VectorPath\"/> 인스턴스를 생성합니다.
    /// </summary>
    /// <param name=\"psdLayer\">psd 레이어.</param>
    /// <returns>입력 레이어의 리소스를 기반으로 한 <see cref=\"VectorPath\"/> 인스턴스.</returns>
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
    /// <see cref=\"VectorPath\"/> 인스턴스로부터 입력 레이어 리소스를 업데이트하거나 새 경로 리소스로 교체하고 업데이트합니다.
    /// </summary>
    /// <param name=\"psdLayer\">psd 레이어.</param>
    /// <param name=\"vectorPath\">벡터 경로.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
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
    /// <param name=\"psdLayer\">psd 레이어.</param>
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
    /// <see cref=\"VectorPath\"/> 인스턴스로부터 리소스 데이터를 업데이트합니다.
    /// </summary>
    /// <param name=\"pathResource\">경로 리소스.</param>
    /// <param name=\"vogkResource\">벡터 원점 데이터 리소스.</param>
    /// <param name=\"socoResource\">단색 색상 리소스.</param>
    /// <param name=\"vectorPath\">벡터 경로.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
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
    /// 레이어의 리소스를 업데이트된 것이나 새로운 것으로 교체합니다.
    /// </summary>
    /// <param name=\"psdLayer\">psd 레이어.</param>
    /// <param name=\"pathResource\">경로 리소스.</param>
    /// <param name=\"vogkResource\">벡터 원점 데이터 리소스.</param>
    /// <param name=\"socoResource\">단색 색상 리소스.</param>
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
    /// 입력 레이어 리소스에서 <see cref=\"VectorPathDataResource\"/> 리소스를 찾습니다.
    /// </summary>
    /// <param name=\"psdLayer\">psd 레이어.</param>
    /// <param name=\"createIfNotExist\">리소스가 존재하지 않으면 <see cref=\"true\"/>에 대해 새 리소스를 생성하고, 그렇지 않으면 <see cref=\"null\"/>을 반환합니다.</param>
    /// <returns><see cref=\"VectorPathDataResource\"/> 리소스.</returns>
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
    /// 입력 레이어 리소스에서 <see cref=\"VogkResource\"/> 리소스를 찾습니다.
    /// </summary>
    /// <param name=\"psdLayer\">psd 레이어.</param>
    /// <param name=\"createIfNotExist\">리소스가 존재하지 않으면 <see cref=\"true\"/>에 대해 새 리소스를 생성하고, 그렇지 않으면 <see cref=\"null\"/>을 반환합니다.</param>
    /// <returns>해당 <see cref=\"VogkResource\"/> 리소스.</returns>
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
    /// 입력 레이어 리소스에서 <see cref=\"SoCoResource\"/> 리소스를 찾습니다.
    /// </summary>
    /// <param name=\"psdLayer\">psd 레이어.</param>
    /// <param name=\"createIfNotExist\">리소스가 존재하지 않으면 <see cref=\"true\"/>에 대해 새 리소스를 생성하고, 그렇지 않으면 <see cref=\"null\"/>을 반환합니다.</param>
    /// <returns>해당 <see cref=\"SoCoResource\"/> 리소스.</returns>
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
    /// 레이어가 <see cref=\"VectorDataProvider\"/> 클래스를 사용하도록 검증합니다.
    /// </summary>
    /// <param name=\"layer\"></param>
    /// <exception cref=\"ArgumentNullException\"></exception>
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
/// Bezier 곡선 노드이며, 하나의 앵커 포인트와 두 개의 제어 포인트를 포함합니다.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// 이미지와 경로 포인트 비율.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// 새로운 <see cref=\"BezierKnot\" /> 클래스 인스턴스를 초기화합니다.
    /// </summary>
    /// <param name=\"anchorPoint\">앵커 포인트.</param>
    /// <param name=\"controlPoint1\">첫 번째 제어 포인트.</param>
    /// <param name=\"controlPoint2\">두 번째 제어 포인트.</param>
    /// <param name=\"isLinked\">이 노드가 연결되어 있는지 여부를 나타내는 값.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// 새로운 <see cref=\"BezierKnot\" /> 클래스 인스턴스를 <see cref=\"BezierKnotRecord\"/>를 기반으로 초기화합니다.
    /// </summary>
    /// <param name=\"bezierKnotRecord\">해당 <see cref=\"BezierKnotRecord\"/>.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// 새로운 <see cref=\"BezierKnot\" /> 클래스 인스턴스를 초기화합니다.
    /// </summary>
    /// <param name=\"anchorPoint\">앵커 및 제어 포인트가 될 포인트.</param>
    /// <param name=\"isLinked\">이 노드가 연결되어 있는지 여부를 나타내는 값.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// 이 인스턴스가 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// 첫 번째 제어 포인트를 가져오거나 설정합니다.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// 앵커 포인트를 가져오거나 설정합니다.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// 두 번째 제어 포인트를 가져오거나 설정합니다.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// 이 인스턴스를 기반으로 <see cref=\"BezierKnotRecord\"/> 인스턴스를 생성합니다.
    /// </summary>
    /// <param name=\"isClosed\">이 노드가 닫힌 형태인지 여부를 나타냅니다.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    /// <returns>이 인스턴스를 기반으로 한 <see cref=\"BezierKnotRecord\"/> 인스턴스.</returns>
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
    /// 입력 값에 따라 이 노드 포인트를 이동합니다.
    /// </summary>
    /// <param name=\"xOffset\">x 오프셋.</param>
    /// <param name=\"yOffset\">y 오프셋.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// 리소스에서 일반으로 포인트 값을 변환합니다.
    /// </summary>
    /// <param name=\"point\">리소스에서 가져온 값이 있는 포인트.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    /// <returns>일반으로 변환된 포인트.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// 일반 포인트 값을 리소스 포인트로 변환합니다.
    /// </summary>
    /// <param name=\"point\">포인트.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    /// <returns>리소스를 위한 값이 있는 포인트.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// 베지어 곡선의 노드에서 얻은 도형.
/// </summary>
public class PathShape
{
    /// <summary>
    /// <see cref=\"PathShape\" /> 클래스의 새 인스턴스를 초기화합니다.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <see cref=\"PathShape\" /> 클래스의 새 인스턴스를 <see cref=\"VectorPathRecord\"/> 기반으로 초기화합니다.
    /// </summary>
    /// <param name=\"lengthRecord\">길이 레코드.</param>
    /// <param name=\"bezierKnotRecords\">베지어 노드 레코드.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// 이 인스턴스가 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <value>
    ///   <c>true</c> 이 인스턴스가 닫혀 있으면; 그렇지 않으면 <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// 경로 연산(불리언 연산)을 가져오거나 설정합니다.
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// 레이어에서 현재 경로 도형의 인덱스를 가져오거나 설정합니다.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// 베지어 곡선의 포인트를 가져옵니다.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// 이 인스턴스를 기반으로 <see cref=\"VectorPathRecord\"/> 레코드를 생성합니다.
    /// </summary>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    /// <returns>이 인스턴스의 각 포인트에 대해 하나의 <see cref=\"LengthRecord\"/>와 <see cref=\"BezierKnotRecord\"/>를 반환합니다.</returns>
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
    /// <param name=\"bezierKnotRecords\">베지어 노드 레코드.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
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
    /// <see cref=\"VectorPath\" /> 클래스의 새 인스턴스를 <see cref=\"VectorPathDataResource\"/> 기반으로 초기화합니다.
    /// </summary>
    /// <param name=\"vectorPathDataResource\">벡터 경로 데이터 리소스.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// 채우기가 모든 픽셀부터 시작되는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <value>
    /// 채우기가 모든 픽셀부터 시작됩니다.
    /// </value>
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
    /// <value>
    /// 버전입니다.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <value>
    ///   <c>true</c> 이 인스턴스가 비활성화된 경우; 그렇지 않으면 <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <value>
    ///   <c>true</c> 이 인스턴스가 연결되지 않은 경우; 그렇지 않으면 <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다.
    /// </summary>
    /// <value>
    ///   <c>true</c> 이 인스턴스가 반전된 경우; 그렇지 않으면 <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// 입력 <see cref="VectorPathDataResource"/> 리소스를 기반으로 값을 초기화합니다.
    /// </summary>
    /// <param name="resource">벡터 경로 데이터 리소스.</param>
    /// <param name=\"imageSize\">점 좌표 변환을 보정하기 위한 이미지 크기.</param>
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

### 또 보기

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


