---
title: Class PixelsData
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.PixelsData 班级. 存储图像像素数据及其边界的类
type: docs
weight: 5250
url: /zh/net/aspose.psd/pixelsdata/
---
## PixelsData class

存储图像像素数据及其边界的类。

```csharp
public sealed class PixelsData
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | 初始化一个新的实例`PixelsData`类. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | 初始化一个新的实例`PixelsData`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | 获取或设置像素数据的范围。 |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | 获取或设置像素数据。 |

### 例子

以下代码向您展示了如何创建具有自定义渲染器的自定义智能过滤器。

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // 在输入数组中初始化不受支持的“Crystallize”智能过滤器
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' 智能过滤器 ID。
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // 将过滤器应用到 SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // 对图层蒙版应用滤镜
        smartFilter.ApplyToMask(maskLayer);

        //对图层应用滤镜
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // 'Crystallize' 智能过滤器 ID。
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // 获取过滤器结构
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // 获取结晶尺寸的值
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


