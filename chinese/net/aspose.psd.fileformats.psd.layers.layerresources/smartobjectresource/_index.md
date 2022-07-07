---
title: SmartObjectResource
second_title: Aspose.PSD for .NET API 参考
description: 定义 SmartObjectResource 类该类包含有关 PSD 文件中智能对象层的信息 Is 是 Sold 和 Sole 资源的基类用于支持 Adobe Photoshop 图像中的智能对象层
type: docs
weight: 2910
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---
## SmartObjectResource class

定义 SmartObjectResource 类，该类包含有关 PSD 文件中智能对象层的信息。 Is 是 Sold 和 Sole 资源的基类，用于支持 Adobe® Photoshop® 图像中的智能对象层。

```csharp
public abstract class SmartObjectResource : PlacedResource, ISmartObjectLayerResource
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy) { get; set; } | 获取或设置PSD图像中智能对象层数据的反锯齿策略。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom) { get; set; } | 获取或设置放置图层在 PSD 图像中的底部位置。 |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds) { get; set; } | 获取或设置 PSD 文件中放置层的边界。 |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp) { get; set; } | 获取或设置 PSD 文件中智能对象层数据的 comp 值。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid) { get; set; } | 获取或设置子文档当前选择的comp的ID，如果没有选择则为-1。 Comps 是设计师可以创建的页面布局的组合。使用图层复合，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本 。图层组合是“图层”面板状态的快照。图层组合保存三种类型的图层选项，但 此属性获取 PSD 文件中智能对象图层的图层组合选择标识符。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop) { get; set; } | 获取或设置 PSD 图像中智能对象图层数据的裁剪。 |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator) { get; set; } | 获取或设置时长分母。 |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator) { get; set; } | 获取或设置持续时间分子。 |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount) { get; set; } | 获取或设置 PSD 文件中智能对象图层数据的帧数。 |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator) { get; set; } | 获取或设置帧步长分母。 |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator) { get; set; } | 获取或设置帧步长分子。 |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height) { get; set; } | 获取或设置高度。 |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints) { get; set; } | 获取或设置 PSD 文件中放置层的水平网格点。 |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit) { get; set; } | 获取或设置水平网格点的度量单位。 |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom) { get; set; } | 获取或设置一个值，该值指示此实例扭曲样式是否为自定义。 如果为真则包含网格点。如果设置为 false，它会删除网格点。 |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items) { get; set; } | 获取或设置PSD文件中智能对象层数据的描述符项。 |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key) { get; } | 获取层资源密钥。 |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left) { get; set; } | 获取或设置放置图层在 PSD 文件中的左侧位置。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length) { get; } | 获取智能对象资源长度（以字节为单位）。 |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix) { get; set; } | 获取或设置PSD文件中智能对象图层数据的非仿射变换矩阵。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid) { get; } | 获取子文档当前选中的 Comp 的原始 ID，如果没有选中则为 -1。 此属性获取 PSD 文件中智能对象层的原始层 Comp 选择标识符。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber) { get; set; } | 获取或设置 PSD 文件中智能对象图层数据的页码。 |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective) { get; set; } | 获取或设置PSD文件中放置图层的透视值。 |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother) { get; set; } | 获取或设置PSD文件中放置图层的透视其他值。 |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid) { get; set; } | 获取或设置此智能对象图层数据在 PSD 图像中的唯一标识符。 |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype) { get; set; } | 获取或设置 PSD 文件中智能对象图层数据的类型。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion) { get; } | 获取智能对象资源所需的最低 psd 版本。 0 表示没有限制。 |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution) { get; set; } | 获取或设置 PSD 文件中智能对象图层数据的分辨率。 |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit) { get; set; } | 获取或设置PSD文件中智能对象图层数据的分辨率度量单位。 |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right) { get; set; } | 获取或设置放置图层在 PSD 文件中的正确位置。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature) { get; } | 获取智能对象资源签名。 |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top) { get; set; } | 获取或设置放置图层在 PSD 图像中的顶部位置。 |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages) { get; set; } | 获取或设置 PSD 文件中智能对象图层数据的总页数。 |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix) { get; set; } | 获取或设置PSD文件中智能对象图层数据的变换矩阵。 |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid) { get; set; } | 获取或设置 PSD 图像中智能对象层数据[`SmartObjectResource`](../smartobjectresource)的全局唯一标识符。 |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder) { get; set; } | 获取或设置 PSD 文件中放置图层的 U 阶值。 |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value) { get; set; } | 获取或设置 PSD 图像中放置层的扭曲值。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version) { get; } | 获取PSD文件中放置图层的版本，一般为3。 |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints) { get; set; } | 获取或设置 PSD 文件中放置层的水平网格点。 |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit) { get; set; } | 获取或设置垂直网格点的测量单位。 |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder) { get; set; } | 获取或设置 PSD 文件中放置图层的 V 阶值。 |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width) { get; set; } | 获取或设置宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save)(StreamContainer, int) | 将智能对象资源保存到指定的流容器。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | 返回代表此实例的String。 |

### 例子

以下代码演示了对 SoLEResource、SmartObjectResource 和 PlacedResource 资源的支持。

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

void CheckSmartObjectResourceValues(object[] expectedValue, SmartObjectResource resource)
{
    AssertAreEqual(expectedValue[0], resource.IsCustom);
    AssertAreEqual(expectedValue[2], resource.PageNumber);
    AssertAreEqual(expectedValue[3], resource.TotalPages);
    AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
    AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
    AssertAreEqual(8, resource.TransformMatrix.Length);
    AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
    AssertAreEqual(expectedValue[7], resource.Value);
    AssertAreEqual(expectedValue[8], resource.Perspective);
    AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
    AssertAreEqual(expectedValue[10], resource.Top);
    AssertAreEqual(expectedValue[11], resource.Left);
    AssertAreEqual(expectedValue[12], resource.Bottom);
    AssertAreEqual(expectedValue[13], resource.Right);
    AssertAreEqual(expectedValue[14], resource.UOrder);
    AssertAreEqual(expectedValue[15], resource.VOrder);

    AssertAreEqual(expectedValue[16], resource.Crop);
    AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
    AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
    AssertAreEqual(expectedValue[19], resource.DurationNumerator);
    AssertAreEqual(expectedValue[20], resource.DurationDenominator);
    AssertAreEqual(expectedValue[21], resource.FrameCount);
    AssertAreEqual(expectedValue[22], resource.Width);
    AssertAreEqual(expectedValue[23], resource.Height);
    AssertAreEqual(expectedValue[24], resource.Resolution);
    AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
    AssertAreEqual(expectedValue[26], resource.Comp);
    AssertAreEqual(expectedValue[27], resource.CompId);
    AssertAreEqual(expectedValue[28], resource.OriginalCompId);
    AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
    AssertAreEqual(expectedValue[30], resource.NonAffineTransformMatrix);
    if (resource.IsCustom)
    {
        AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
        AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
    }
}

void SetNewSmartValues(SmartObjectResource resource, object[] newValues)
{
    // 这个值我们不会在资源中改变
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // 这个值也应该在 PlLdResource 中更改（使用指定的 UniqueId）
    // 其中一些必须与LinkDataSource中的下划线智能对象一致
    resource.PageNumber = (int)newValues[2]; // 2;
    resource.TotalPages = (int)newValues[3]; // 3;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789;
    resource.Perspective = (double)newValues[8]; // 0.123456789;
    resource.PerspectiveOther = (double)newValues[9]; // 0.987654321;
    resource.Top = (double)newValues[10]; // -126;
    resource.Left = (double)newValues[11]; // -215;
    resource.Bottom = (double)newValues[12]; // 248;
    resource.Right = (double)newValues[13]; // 145;
    resource.Crop = (int)newValues[16]; // 5;
    resource.FrameStepNumerator = (int)newValues[17]; // 1;
    resource.FrameStepDenominator = (int)newValues[18]; // 601;
    resource.DurationNumerator = (int)newValues[19]; // 2;
    resource.DurationDenominator = (int)newValues[20]; // 602;
    resource.FrameCount = (int)newValues[21]; // 11;
    resource.Width = (double)newValues[22]; // 541;
    resource.Height = (double)newValues[23]; // 249;
    resource.Resolution = (double)newValues[24]; // 144;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21;
    resource.CompId = (int)newValues[27]; // 22;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // 如果有的话，这个唯一的 Id 应该在引用中改变
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98");
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // 注意一些参数：保存的图像可能会变得无法被 Adobe® Photoshop® 读取
    ////resource.UOrder = 6;
    ////resource.VOrder = 9;

    // 不要改变这个，否则你将无法使用自由变换
    // 或将下划线智能对象更改为矢量类型
    ////resource.PlacedLayerType = PlacedLayerType.Vector;

    // 应该有具有此唯一 ID 的有效 PlLdResource
    ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");
}

object[] newSmartValues = new object[]
{
    true,
    null,
    2,
    3,
    0,
    PlacedLayerType.ImageStack,
    new double[8]
    {
        12.937922786050663,
        19.419959734187131,
        2.85445817782261,
        1.0540625423957124,
        7.20861031651307,
        14.634102808208553,
        17.292074924741144,
        4
    },
    1.23456789,
    0.123456789,
    0.987654321,
    -126d,
    -215d,
    248d,
    145d,
    4,
    4,
    5,
    1,
    601,
    2,
    602,
    11,
    541d,
    249d,
    144d,
    UnitTypes.Percent,
    21,
    22,
    23,
    "12345678-9abc-def0-9876-54321fecba98",
    new double[8]
    {
        129.937922786050663,
        195.419959734187131,
        26.85445817782261,
        12.0540625423957124,
        72.20861031651307,
        147.634102808208553,
        175.292074924741144,
        42
    },
    UnitTypes.Points,
    new double[16]
    {
        0.01d, 103.33333333333433d, 206.66686666666666d, 310.02d,
        0.20d, 103.33333333333533d, 206.69666666666666d, 310.03d,
        30.06d, 103.33333333336333d, 206.66660666666666d, 310.04d,
        04.05d, 103.33333333373333d, 206.66666166666666d, 310.05d
    },
    UnitTypes.Distance,
    new double[16]
    {
        0.06d, 0.07d, 0.08d, 0.09d,
        49.066666666666664d, 49.266666666666664d, 49.566666666666664d, 49.766666666666664d,
        99.133333333333329d, 99.433333333333329d, 99.633333333333329d, 99.833333333333329d,
        140, 141, 142, 143,
    },
};

object[] expectedValues = new object[]
{
    new object[]
    {
        false,
        "5867318f-3174-9f41-abca-22f56a75247e",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        2d,
        2d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        2d,
        2d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "64b3997c-06e0-be40-a349-41acf397c897",
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
    }
};

var sourceFilePath = "rgb8_2x2_linked.psd";
var outputPath = "rgb8_2x2_linked_output.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLeResource soleResource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as SoLeResource;
            if (resource != null)
            {
                soleResource = resource;
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                CheckSmartObjectResourceValues(expectedValue, resource);
                SetNewSmartValues(resource, newSmartValues);

                break;
            }
        }
    }

    AssertIsTrue(soleResource != null);
    image.Save(outputPath, new PsdOptions(image));
    using (PsdImage savedImage = (PsdImage)Image.Load(outputPath))
    {
        foreach (Layer imageLayer in savedImage.Layers)
        {
            foreach (var imageResource in imageLayer.Resources)
            {
                var resource = imageResource as SoLeResource;
                if (resource != null)
                {
                    CheckSmartObjectResourceValues(newSmartValues, resource);

                    break;
                }
            }
        }
    }
}
```

### 也可以看看

* class [SoLdResource](../soldresource)
* class [PlacedResource](../placedresource)
* interface [ISmartObjectLayerResource](../ismartobjectlayerresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
