---
title: "ISmartFilterRenderer.Render"
second_title: "Aspose.PSD for .NET API 参考"
description: "ISmartFilterRenderer 方法。在像素数据上渲染当前智能过滤器"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
{{< psd/tize >}}
## ISmartFilterRenderer.Render method

在像素数据上渲染当前智能滤镜。

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelsData | PixelsData | 像素数据。 |

### 返回值

返回处理后的像素数据。

## 示例

以下代码展示了如何创建具有自定义渲染器的自定义智能滤镜。

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // 在输入数组中初始化不受支持的 'Crystallize' 智能滤镜
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' 智能滤镜 ID。
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

        // 将滤镜应用于 SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // 将滤镜应用于图层蒙版
        smartFilter.ApplyToMask(maskLayer);

        //将滤镜应用于图层
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
        // 'Crystallize' 智能滤镜 ID。
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // 获取滤镜结构
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // 获取 Crystallize 大小的值
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

### 另请参阅

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../../)


