---
title: VmskResource.VmskResource
second_title: Aspose.PSD for .NET API リファレンス
description: VmskResource コンストラクタ. の新しいインスタンスを初期化しますVmskResourceclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
## VmskResource(byte[]) {#constructor_1}

の新しいインスタンスを初期化します[`VmskResource`](../)class.

```csharp
public VmskResource(byte[] data)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| data | Byte[] | リソース データ。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Vmsk リソース値が無効です |

### 関連項目

* class [VmskResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* 組み立て [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

の新しいインスタンスを初期化します[`VmskResource`](../)class.

```csharp
public VmskResource()
```

### 例

次のコード例は、ベクター パス オブジェクトを操作するためのクラスを提供し、それらのクラスの使用方法を示しています。

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
/// <see cref="Layer"/> 間の作業を提供するクラス。および <cref="VectorPath"/> を参照してください。
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// <see cref="VectorPath"/> を作成します。入力層からのリソースに基づくインスタンス。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
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
    /// <see cref="VectorPath"/> からの入力レイヤー リソースを更新します。インスタンス、または新しいパスリソースと更新で置き換えます。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
    /// <param name="vectorPath">ベクター パス。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
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
    /// 入力レイヤーからベクター パス データを削除します。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
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
    /// <see cref="VectorPath"/> のリソース データを更新します。実例。
    /// </summary>
    /// <param name="pathResource">パス リソース。</param>
    /// <param name="vogkResource">ベクター生成データ リソース</param>
    /// <param name="socoResource">無地のリソースです。</param>
    /// <param name="vectorPath">ベクター パス。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
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
    /// レイヤ内のリソースを更新または新しいリソースに置き換えます。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
    /// <param name="pathResource">パス リソース。</param>
    /// <param name="vogkResource">ベクター生成データ リソース</param>
    /// <param name="socoResource">無地のリソースです。</param>
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
    /// <see cref="VectorPathDataResource"/> を検索します。入力層リソースのリソース。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
    /// <param name="createIfNotExist">リソースが存在しない場合は、<see cref="true"/>新しいリソースを作成します。それ以外の場合は <see cref="null"/>.</param> を返します。
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
    /// <see cref="VogkResource"/> を検索します。入力層リソースのリソース。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
    /// <param name="createIfNotExist">リソースが存在しない場合は、<see cref="true"/>新しいリソースを作成します。それ以外の場合は <see cref="null"/>.</param> を返します。
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
    /// <see cref="SoCoResource"/> を検索します。入力層リソースのリソース。
    /// </summary>
    /// <param name="psdLayer">psd レイヤー</param>
    /// <param name="createIfNotExist">リソースが存在しない場合は、<see cref="true"/>新しいリソースを作成します。それ以外の場合は <see cref="null"/>.</param> を返します。
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
    /// レイヤーが動作することを確認します <see cref="VectorDataProvider"/>クラス。
    /// </summary>
    /// <param name="レイヤー"></param>
    /// <例外 cref="ArgumentNullException"></例外>
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
/// ベジエ カーブ ノット。1 つのアンカー ポイントと 2 つのコントロール ポイントが含まれます。
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// 画像とパス ポイントの比率。
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// <see cref="BezierKnot" /> の新しいインスタンスを初期化します。クラス。
    /// </summary>
    /// <param name="anchorPoint">アンカーポイント。</param>
    /// <param name="controlPoint1">最初のコントロール ポイント。</param>
    /// <param name="controlPoint2">2 番目のコントロール ポイント。</param>
    /// <param name="isLinked">このノットがリンクされているかどうかを示す値。</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// <see cref="BezierKnot" /> の新しいインスタンスを初期化します。 <see cref="BezierKnotRecord"/> に基づくクラス。
    /// </summary>
    /// <param name="bezierKnotRecord"> <see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// <see cref="BezierKnot" /> の新しいインスタンスを初期化します。クラス。
    /// </summary>
    /// <param name="anchorPoint">アンカーポイントとコントロールポイントになるポイント</param>
    /// <param name="isLinked">このノットがリンクされているかどうかを示す値。</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// このインスタンスがリンクされているかどうかを示す値を取得または設定します。
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// 最初のコントロール ポイントを取得または設定します。
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// アンカー ポイントを取得または設定します。
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// 2 番目のコントロール ポイントを取得または設定します。
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// <see cref="BezierKnotRecord"/> のインスタンスを作成します。このインスタンスに基づいています。
    /// </summary>
    /// <param name="isClosed">この結び目が閉じているかどうかを示します。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
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
    /// このノット ポイントを入力値だけシフトします。
    /// </summary>
    /// <param name="xOffset">x オフセット。</param>
    /// <param name="yOffset">Y オフセット。</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// ポイント値をリソースから通常に変換します。
    /// </summary>
    /// <param name="point">リソースからの値を持つポイント。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// 通常のポイント値をリソース ポイントに変換します。
    /// </summary>
    /// <param name="point">ポイント。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// ベジエ曲線の結び目からの図。
/// </summary>
public class PathShape
{
    /// <summary>
    /// <see cref="PathShape" /> の新しいインスタンスを初期化します。クラス。
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <see cref="PathShape" /> の新しいインスタンスを初期化します。 <see cref="VectorPathRecord"/> に基づくクラス。
    /// </summary>
    /// <param name="lengthRecord">長さレコード。</param>
    /// <param name="bezierKnotRecords">ベジエ ノット レコード。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// このインスタンスが閉じているかどうかを示す値を取得または設定します。
    /// </summary>
    /// <値>;
    /// <c>真</c>このインスタンスが閉じている場合。それ以外の場合は <c>false</c>。
    /// </値>
    public bool IsClosed { get; set; }

    /// <summary>
    /// パス操作 (ブール演算) を取得または設定します。
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// レイヤー内の現在のパス形状のインデックスを取得または設定します。
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// ベジエ曲線のポイントを取得します。
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// <see cref="VectorPathRecord"/> を作成します。このインスタンスに基づくレコード。
    /// </summary>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
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
    /// 入力レコードに基づいて値を初期化します。
    /// </summary>
    /// <param name="bezierKnotRecords">ベジエ ノット レコード。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
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
/// ベクター パスを含むクラス。
/// </summary>
public class VectorPath
{
    /// <summary>
    /// <see cref="VectorPath" /> の新しいインスタンスを初期化します。 <see cref="VectorPathDataResource"/> に基づくクラス。
    /// </summary>
    /// <param name="vectorPathDataResource">ベクター パス データ リソース。</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// 塗りつぶしがすべてのピクセルで始まるかどうかを示す値を取得または設定します。
    /// </summary>
    /// <値>;
    /// 塗りつぶしはすべてのピクセルで始まります。
    /// </値>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// ベクトル形状を取得します。
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// ベクター パスの塗りつぶしの色を取得または設定します。
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// バージョンを取得または設定します。
    /// </summary>
    /// <値>;
    /// バージョン。
    /// </値>
    public int Version { get; set; }

    /// <summary>
    /// このインスタンスが無効かどうかを示す値を取得または設定します。
    /// </summary>
    /// <値>;
    /// <c>真</c>このインスタンスが無効になっている場合。それ以外の場合は <c>false</c>。
    /// </値>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// このインスタンスがリンクされていないかどうかを示す値を取得または設定します。
    /// </summary>
    /// <値>;
    /// <c>真</c>このインスタンスがリンクされていない場合。それ以外の場合は <c>false</c>。
    /// </値>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// このインスタンスが反転されているかどうかを示す値を取得または設定します。
    /// </summary>
    /// <値>;
    /// <c>真</c>このインスタンスが反転されている場合。それ以外の場合は <c>false</c>。
    /// </値>
    public bool IsInverted { get; set; }

    /// <summary>
    /// 入力に基づいて値を初期化 <see cref="VectorPathDataResource"/>リソース。
    /// </summary>
    /// <param name="resource">ベクター パス データ リソース</param>
    /// <param name="imageSize">変換点座標を補正するための画像サイズ</param>
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

### 関連項目

* class [VmskResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* 組み立て [Aspose.PSD](../../../)


