---
title: "VibAResource.Save"
second_title: "Aspose.PSD for .NET API Reference"
description: "VibAResource メソッド。リソースを指定されたストリームコンテナに保存します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

リソースを指定されたストリームコンテナに保存します。

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | StreamContainer | 保存先のストリームコンテナです。 |
| psdVersion | Int32 | PSD バージョンです。 |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


