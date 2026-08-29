---
title: "列挙型 SheetColorHighlightEnum"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum 列挙型。シートカラー設定の可能な色です。Photoshop のレイヤーリストでレイヤーの UI 装飾色として使用されます"
type: docs
weight: 3320
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

シートカラー設定の可能な色です。PS のレイヤーリスト内のレイヤーの UI 装飾色です。

```csharp
public enum SheetColorHighlightEnum : short
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NoColor | `0` | 色が指定されていません。 |
| Red | `1` | 赤色。 |
| Orange | `2` | オレンジ色。 |
| Yellow | `3` | 黄色。 |
| Green | `4` | 緑色。 |
| Blue | `5` | 青色。 |
| Violet | `6` | 紫色。 |
| Gray | `7` | 灰色。 |

## 例

以下の例は Aspose.PSD でシートカラーのハイライトを変更する方法を示しています（シートカラー設定）。

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// ファイル内ではレイヤーのハイライト色はこの順序です。
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// レイヤーシートカラーはレイヤーを視覚的にハイライトするために使用されます。
// 例えば、PSD のいくつかのレイヤーを更新し、注目させたいレイヤーを色でハイライトすることができます。
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // 色は逆順にする必要があります。
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // lcrl リソースは常に PSD ファイルのリソースリストに存在します。
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // スタイルシートの色を逆転させます。レイヤーのカラー ハイライトを設定します。
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


