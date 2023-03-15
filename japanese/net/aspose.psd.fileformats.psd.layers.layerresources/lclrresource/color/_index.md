---
title: LclrResource.Color
second_title: Aspose.PSD for .NET API リファレンス
description: LclrResource 財産. レイヤーの色を取得または設定します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

レイヤーの色を取得または設定します。

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### プロパティ値

色.

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* 組み立て [Aspose.PSD](../../../)


