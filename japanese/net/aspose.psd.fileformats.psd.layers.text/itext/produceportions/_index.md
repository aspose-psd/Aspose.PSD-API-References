---
title: IText.ProducePortions
second_title: Aspose.PSD for .NET API リファレンス
description: IText 方法. 入力パラメータまたはデフォルト パラメータを使用して新しい部分を生成します
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

入力パラメータまたはデフォルト パラメータを使用して新しい部分を生成します。

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| portionsOfText | String[] | 新規作成するテキストの部分[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | null でない場合に新しいスタイルに適用されるスタイル、それ以外の場合はデフォルトになります。 |
| paragraphPrototype | ITextParagraph | null でない場合に新しい段落に適用される段落、それ以外の場合はデフォルトになります。 |

### 戻り値

新しい部分を返します[`ITextPortion`](../../itextportion/)入力パラメータに基づいています。

### 例

次の例は、Aspose.PSD の 1 つのテキスト レイヤーでさまざまなスタイルをレンダリングする方法を示しています。

```csharp
[C#]

string sourceFile = "text212.psd";
string etalonFile = "Ethalon_text212.psd";
string outputFile = "Output_text212.psd";

using (var img = (PsdImage)Image.Load(sourceFile))
{
    TextLayer textLayer = (TextLayer)img.Layers[1];
    IText textData = textLayer.TextData;
    ITextStyle defaultStyle = textData.ProducePortion().Style;
    ITextParagraph defaultParagraph = textData.ProducePortion().Paragraph;
    defaultStyle.FillColor = Color.DimGray;
    defaultStyle.FontSize = 51;

    textData.Items[1].Style.Strikethrough = true;

    ITextPortion[] newPortions = textData.ProducePortions(
        new string[]
        {
          "E=mc", "2\r", "Bold", "Italic\r",
          "Lowercasetext"
        },
        defaultStyle,
        defaultParagraph);

    newPortions[0].Style.Underline = true; // テキストスタイル「E=mc」を編集
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // テキスト スタイル "2\r" を編集
    newPortions[2].Style.FauxBold = true; // テキストスタイル「太字」を編集
    newPortions[3].Style.FauxItalic = true; // テキスト スタイル "Italic\r" を編集します
    newPortions[3].Style.BaselineShift = -25; // テキスト スタイル "Italic\r" を編集します
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // テキスト スタイル "Lowercasetext" を編集します

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### 関連項目

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* 組み立て [Aspose.PSD](../../../)


