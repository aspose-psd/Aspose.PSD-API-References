---
title: "VibAResource.PsdVersion"
second_title: "Aspose.PSD for .NET API Reference"
description: "VibAResource プロパティ。psd バージョンを取得します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/
---
{{< psd/tize >}}
## VibAResource.PsdVersion property

psd バージョンを取得します。

```csharp
public override int PsdVersion { get; }
```

## 例

次のコード例は、VibAResource リソースのサポートを示しています。

```csharp
[C#]

// 実行時に Vibration リソースの読み取りと書き込みをサポートする例です。
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### 関連項目

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


