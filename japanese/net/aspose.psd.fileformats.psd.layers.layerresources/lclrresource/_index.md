---
title: Class LclrResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource クラス. Class LclrResource. このリソースにはレイヤー リストのレイヤーの色に関する情報が含まれています only です
type: docs
weight: 2620
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Class LclrResource. このリソースには、レイヤー リストのレイヤーの色に関する情報が含まれています。 only です

```csharp
public class LclrResource : LayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | の新しいインスタンスを初期化します`LclrResource`class. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | の新しいインスタンスを初期化します`LclrResource`class. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | の新しいインスタンスを初期化します`LclrResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | レイヤーの色を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | タイプ ツール情報キー。 |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


