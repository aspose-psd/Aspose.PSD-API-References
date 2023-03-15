---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum 列挙. シートカラー設定可能色 PS のレイヤー一覧にあるレイヤーのUI装飾色です
type: docs
weight: 2970
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

シートカラー設定可能色 PS のレイヤー一覧にあるレイヤーのUI装飾色です

```csharp
public enum SheetColorHighlightEnum : short
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| NoColor | `0` | 色が指定されていません。 |
| Red | `1` | 赤い色. |
| Orange | `2` | オレンジ色. |
| Yellow | `3` | 黄色。 |
| Green | `4` | 緑色。 |
| Blue | `5` | 青い色. |
| Violet | `6` | 紫の色. |
| Gray | `7` | 灰色。 |

### 例

次の例は、Aspose.PSD (シート カラー設定) でシート カラー ハイライトを変更する方法を示しています。

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// ファイルでは、レイヤーのハイライトの色はこの順序になっています
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

// Layer Sheet Color は、レイヤを視覚的に強調するために使用されます。 
// たとえば、PSD のいくつかのレイヤーを更新してから、注目を集めたいレイヤーを色で強調表示できます。
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // 色を反転する必要があります
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
            // lcrl リソースは常に psd ファイル リソース リストに表示されます。
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // スタイルシートの色を反転。レイヤーカラーハイライトの設定。
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


