---
title: "VmskResource.VmskResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "VmskResource コンストラクタ。VmskResource クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
{{< psd/tize >}}
## VmskResource(byte[]) {#constructor_1}

[`VmskResource`](../) クラスの新しいインスタンスを初期化します。

```csharp
public VmskResource(byte[] data)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | Byte[] | リソース データ。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 無効な Vmsk Resource 値 |

### 関連項目

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

[`VmskResource`](../) クラスの新しいインスタンスを初期化します。

```csharp
public VmskResource()
```

## 例

以下のコード例はベクトルパスオブジェクトを操作するクラスを提供し、これらのクラスの使用方法を示します。

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
/// クラスは <see cref=\"Layer\"/> と <see cref=\"VectorPath\"/> の間の作業を提供します。
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// 入力レイヤーのリソースに基づいて <see cref=\"VectorPath\"/> インスタンスを作成します。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
    /// <returns>入力レイヤーのリソースに基づく <see cref=\"VectorPath\"/> インスタンス。</returns>
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
    /// <see cref=\"VectorPath\"/> インスタンスから入力レイヤーのリソースを更新するか、新しいパスリソースに置き換えて更新します。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
    /// <param name=\"vectorPath\">ベクトルパス。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
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
    /// 入力レイヤーからベクトルパスデータを削除します。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
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
    /// <see cref=\"VectorPath\"/> インスタンスからリソースデータを更新します。
    /// </summary>
    /// <param name=\"pathResource\">パスリソース。</param>
    /// <param name=\"vogkResource\">ベクトル起点データリソース。</param>
    /// <param name=\"socoResource\">単色リソース。</param>
    /// <param name=\"vectorPath\">ベクトルパス。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
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
    /// レイヤー内のリソースを更新されたものまたは新しいものに置き換えます。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
    /// <param name=\"pathResource\">パスリソース。</param>
    /// <param name=\"vogkResource\">ベクトル起点データリソース。</param>
    /// <param name=\"socoResource\">単色リソース。</param>
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
    /// 入力レイヤーのリソースから <see cref=\"VectorPathDataResource\"/> リソースを検索します。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
    /// <param name=\"createIfNotExist\">リソースが存在しない場合、<see cref=\"true\"/> のときは新しいリソースを作成し、そうでなければ <see cref=\"null\"/> を返します。</param>
    /// <returns><see cref=\"VectorPathDataResource\"/> リソース。</returns>
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
    /// 入力レイヤーのリソースから <see cref=\"VogkResource\"/> リソースを検索します。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
    /// <param name=\"createIfNotExist\">リソースが存在しない場合、<see cref=\"true\"/> のときは新しいリソースを作成し、そうでなければ <see cref=\"null\"/> を返します。</param>
    /// <returns>この <see cref=\"VogkResource\"/> リソース。</returns>
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
    /// 入力レイヤーリソース内の <see cref=\"SoCoResource\"/> リソースを検索します。
    /// </summary>
    /// <param name=\"psdLayer\">psd レイヤー。</param>
    /// <param name=\"createIfNotExist\">リソースが存在しない場合、<see cref=\"true\"/> のときは新しいリソースを作成し、そうでなければ <see cref=\"null\"/> を返します。</param>
    /// <returns>この <see cref=\"SoCoResource\"/> リソース。</returns>
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
    /// レイヤーが <see cref=\"VectorDataProvider\"/> クラスと連携できるか検証します。
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
/// Bezier 曲線のノットで、1 つのアンカーポイントと 2 つの制御ポイントを含みます。
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// 画像とパスポイントの比率。
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// 新しい <see cref=\"BezierKnot\" /> クラスのインスタンスを初期化します。
    /// </summary>
    /// <param name=\"anchorPoint\">アンカーポイント。</param>
    /// <param name=\"controlPoint1\">最初の制御ポイント。</param>
    /// <param name=\"controlPoint2\">2 番目の制御ポイント。</param>
    /// <param name=\"isLinked\">このノットがリンクされているかどうかを示す値。</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// 新しい <see cref=\"BezierKnot\" /> クラスのインスタンスを <see cref=\"BezierKnotRecord\"/> に基づいて初期化します。
    /// </summary>
    /// <param name=\"bezierKnotRecord\">対象の <see cref=\"BezierKnotRecord\"/>。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// 新しい <see cref=\"BezierKnot\" /> クラスのインスタンスを初期化します。
    /// </summary>
    /// <param name=\"anchorPoint\">アンカーおよび制御ポイントになる点。</param>
    /// <param name=\"isLinked\">このノットがリンクされているかどうかを示す値。</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// このインスタンスがリンクされているかどうかを示す値を取得または設定します。
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// 最初の制御ポイントを取得または設定します。
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// アンカーポイントを取得または設定します。
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// 2 番目の制御ポイントを取得または設定します。
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// このインスタンスに基づいて <see cref=\"BezierKnotRecord\"/> のインスタンスを作成します。
    /// </summary>
    /// <param name=\"isClosed\">このノットが閉じた形状かどうかを示す。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
    /// <returns>このインスタンスに基づく <see cref=\"BezierKnotRecord\"/> のインスタンス。</returns>
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
    /// 入力値でこのノットのポイントをシフトします。
    /// </summary>
    /// <param name=\"xOffset\">x オフセット。</param>
    /// <param name="yOffset">y オフセット。</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// リソースから通常へのポイント値を変換します。
    /// </summary>
    /// <param name="point">リソースからの値を持つポイント。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
    /// <returns>通常に変換されたポイント。</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// 通常のポイント値をリソースポイントに変換します。
    /// </summary>
    /// <param name="point">ポイント。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
    /// <returns>リソース用の値を持つポイント。</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// ベジェ曲線のノットから得られる図形。
/// </summary>
public class PathShape
{
    /// <summary>
    /// 新しい <see cref="PathShape" /> クラスのインスタンスを初期化します。
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <see cref="VectorPathRecord"/> に基づく新しい <see cref="PathShape" /> クラスのインスタンスを初期化します。
    /// </summary>
    /// <param name="lengthRecord">長さレコード。</param>
    /// <param name="bezierKnotRecords">ベジェノットレコード。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
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
    /// <value>
    ///   <c>true</c> このインスタンスが閉じている場合; それ以外は <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// パス操作（ブール演算）を取得または設定します。
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// レイヤー内の現在のパスシェイプのインデックスを取得または設定します。
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// ベジェ曲線のポイントを取得します。
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// このインスタンスに基づいて <see cref="VectorPathRecord"/> レコードを作成します。
    /// </summary>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
    /// <returns>このインスタンスの各ポイントに対して、1つの <see cref="LengthRecord"/> と <see cref="BezierKnotRecord"/> を返します。</returns>
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
    /// <param name="bezierKnotRecords">ベジェノットレコード。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
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
/// ベクトルパスを含むクラスです。
/// </summary>
public class VectorPath
{
    /// <summary>
    /// <see cref="VectorPathDataResource"/> に基づく新しい <see cref="VectorPath" /> クラスのインスタンスを初期化します。
    /// </summary>
    /// <param name="vectorPathDataResource">ベクトルパスデータリソース。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// 値を取得または設定します。この値は塗りがすべてのピクセルから開始するかどうかを示します。
    /// </summary>
    /// <value>
    /// 塗りがすべてのピクセルから開始します。
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// ベクトル形状を取得します。
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// ベクトルパスの塗り色を取得または設定します。
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// バージョンを取得または設定します。
    /// </summary>
    /// <value>
    /// バージョンです。
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// このインスタンスが無効かどうかを示す値を取得または設定します。
    /// </summary>
    /// <value>
    ///   <c>true</c> このインスタンスが無効な場合; それ以外は <c>false</c>。
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// このインスタンスがリンクされていないかどうかを示す値を取得または設定します。
    /// </summary>
    /// <value>
    ///   <c>true</c> このインスタンスがリンクされていない場合; それ以外は <c>false</c>。
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// このインスタンスが反転しているかどうかを示す値を取得または設定します。
    /// </summary>
    /// <value>
    ///   <c>true</c> このインスタンスが反転している場合; それ以外は <c>false</c>。
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// 入力 <see cref="VectorPathDataResource"/> リソースに基づいて値を初期化します。
    /// </summary>
    /// <param name="resource">ベクトルパスデータリソース。</param>
    /// <param name=\"imageSize\">ポイント座標変換を補正するための画像サイズ。</param>
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


