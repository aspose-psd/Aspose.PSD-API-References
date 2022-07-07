---
title: BlwhResource
second_title: Aspose.PSD for .NET API 参考
description: BlwhResource 类是黑白调整层的资源
type: docs
weight: 2260
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---
## BlwhResource class

BlwhResource 类是黑白调整层的资源。

```csharp
public class BlwhResource : AdjustmentLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [BlwhResource](blwhresource)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlackAndWhitePresetFileName](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blackandwhitepresetfilename) { get; set; } | 获取或设置黑白预设文件名。 |
| [Blues](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blues) { get; set; } | 获取或设置蓝调值。 |
| [BwPresetKind](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/bwpresetkind) { get; set; } | 获取或设置黑白预设种类值。 |
| [Cyans](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/cyans) { get; set; } | 获取或设置青色值。 |
| [Greens](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/greens) { get; set; } | 获取或设置果岭值。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/key) { get; } | 获取层资源密钥。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/length) { get; } | 获取层资源长度（以字节为单位）。 |
| [Magentas](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/magentas) { get; set; } | 获取或设置洋红色值。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/psdversion) { get; } | 获取psd版本。 |
| [Reds](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/reds) { get; set; } | 获取或设置红色值。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | 获取签名。 |
| [TintColor](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/tintcolor) { get; set; } | 获取或设置 Tint Color ARGB 值。 |
| [UseTint](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/usetint) { get; set; } | 获取或设置一个值，指示是否使用[tint color]。 |
| [Yellows](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/yellows) { get; set; } | 获取或设置黄色值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/save)(StreamContainer, int) | 将资源保存到指定的流容器。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | 返回代表此实例的String。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/typetoolkey) | 类型工具信息键。 |

### 例子

以下示例演示如何编辑 BlwhResource。

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

const string ActualPropertyValueIsWrongMessage = "Expected property value is not equal to actual value";

string destinationFileName = "Output" + sourceFileName;
bool isRequiredResourceFound = false;
using (PsdImage im = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == tintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == bwPresetKind, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == bwPresetFileName, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue) < 1e-6, ActualPropertyValueIsWrongMessage);

                // 测试编辑和保存
                blwhResource.Reds = reds - 15;
                blwhResource.Yellows = yellows - 15;
                blwhResource.Greens = greens + 15;
                blwhResource.Cyans = cyans + 15;
                blwhResource.Blues = blues - 15;
                blwhResource.Magentas = magentas - 15;
                blwhResource.UseTint = !useTint;
                blwhResource.BwPresetKind = 4;
                blwhResource.BlackAndWhitePresetFileName = "bwPresetFileName";
                blwhLayer.TintColorRed = tintColorRed - 60;
                blwhLayer.TintColorGreen = tintColorGreen - 60;
                blwhLayer.TintColorBlue = tintColorBlue - 60;

                im.Save(destinationFileName);
                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");

isRequiredResourceFound = false;

using (PsdImage im = (PsdImage)Image.Load(destinationFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == !useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == newTintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == 4, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == "bwPresetFileName", ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue + 60) < 1e-6, ActualPropertyValueIsWrongMessage);

                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");
```

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
