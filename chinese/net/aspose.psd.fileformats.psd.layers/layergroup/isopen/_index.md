---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD for .NET API 参考"
description: "LayerGroup 属性。获取或设置文件夹是否打开；如果设置为 true，则组在启动时为打开状态，否则为最小化状态"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

获取或设置文件夹是否打开；如果设置为 `true`，则组在启动时为打开状态，否则为最小化状态。

```csharp
public bool IsOpen { get; set; }
```

## 示例

以下代码演示如何使用 IsOpen 属性打开和关闭 LayerGroup (Folder)。

```csharp
[C#]

// 运行时读取和写入 IsOpen 属性的示例。
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### 另请参阅

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


