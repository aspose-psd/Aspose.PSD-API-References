---
title: VibAResource.VibAResource
second_title: Aspose.PSD for .NET API リファレンス
description: VibAResource コンストラクタ. の新しいインスタンスを初期化しますVibAResourceclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
## VibAResource constructor

の新しいインスタンスを初期化します[`VibAResource`](../)class.

```csharp
public VibAResource()
```

### 例

次のコード例は、VibAResource リソースのサポートを示しています。

```csharp
[C#]

// 実行時のバイブレーション リソースの読み取りと書き込みのサポートの例。
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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* 組み立て [Aspose.PSD](../../../)


