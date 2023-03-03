---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD for .NET API リファレンス
description: TextLayer 財産. 変換マトリックスを取得または設定します
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

変換マトリックスを取得または設定します

```csharp
public double[] TransformMatrix { get; set; }
```

### プロパティ値

変換マトリックス

### 例

次のコードは、テキスト レイヤー内の任意のテキスト部分のフォント サイズを取得する方法を示しています。

```csharp
[C#]

// 間違ったフォント サイズを抽出しました 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 古い API (最初の段落のフォントを使用)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // ベースフォントサイズのチェック
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実際のフォントサイズをチェック
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 新しい API (1 つのテキスト レイヤーに任意の数のフォント サイズを含めることができます)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // ベース部分のフォントサイズチェック
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実部フォントサイズチェック
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### 関連項目

* class [TextLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* 組み立て [Aspose.PSD](../../../)


