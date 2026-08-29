---
title: "SoCoResource.Color"
second_title: "Aspose.PSD for .NET API Reference"
description: "SoCoResource プロパティ。RGBカラーを取得します"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

RGB カラーを取得します。

```csharp
public Color Color { get; set; }
```

### 戻り値

RGB カラー

## 例

次の例は、SoCoResource（カラー塗りつぶしレイヤー用のレイヤーリソース）を編集する方法を示しています

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer の検索
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // レイヤーリソースリスト内の SoCoResource の検索
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource の Color プロパティを設定する
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### 関連項目

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


