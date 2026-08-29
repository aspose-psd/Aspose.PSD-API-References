---
title: "FilterEffectMaskData.Rectangle"
second_title: "Aspose.PSD for .NET API Reference"
description: "FilterEffectMaskData プロパティ。チャンネル矩形を取得します"
type: docs
weight: 80
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/
---
{{< psd/tize >}}
## FilterEffectMaskData.Rectangle property

チャンネルの矩形を取得します。

```csharp
public Rectangle Rectangle { get; }
```

## 例

この例は、FXidResource リソースのプロパティを取得および設定する方法を示しています。

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// 保存後に確認してください
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


