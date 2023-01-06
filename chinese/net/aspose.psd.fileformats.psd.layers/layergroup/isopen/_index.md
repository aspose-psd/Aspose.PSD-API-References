---
title: IsOpen
second_title: Aspose.PSD for .NET API 参考
description: 获取或设置文件夹是否打开 如果设置为真的比组将在启动时处于打开状态否则处于最小化状态
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

获取或设置文件夹是否打开 如果设置为`真的`比组将在启动时处于打开状态，否则处于最小化状态。

```csharp
public bool IsOpen { get; set; }
```

### 例子

以下代码显示如何使用 IsOpen 属性打开和关闭 LayerGroup（文件夹）。

```csharp
[C#]

// 在运行时读取和写入 IsOpen 属性的示例。
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

### 也可以看看

* class [LayerGroup](../../layergroup)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->