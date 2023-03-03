---
title: FontSettings.GetAdobeFontName
second_title: Aspose.PSD for .NET API リファレンス
description: FontSettings 方法. フォント ファミリ名から Adobe フォント名を取得します
type: docs
weight: 30
url: /ja/net/aspose.psd/fontsettings/getadobefontname/
---
## FontSettings.GetAdobeFontName method

フォント ファミリ名から Adobe フォント名を取得します。

```csharp
public static string GetAdobeFontName(string fontFamilyName)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontFamilyName | String | フォントファミリ名。 |

### 戻り値

フォントファミリ名別のAdobeフォント名。

### 例

次のコードは、部分スタイルでフォント名を変更する機能を示しています。

```csharp
[C#]

string outputFilePng = "result_fontEditTest.png";
string outputFilePsd = "fontEditTest.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = new PsdImage(500, 500))
{
    FillLayer backgroundFillLayer = FillLayer.CreateInstance(FillType.Color);
    ((IColorFillSettings)backgroundFillLayer.FillSettings).Color = Color.White;
    image.AddLayer(backgroundFillLayer);

    TextLayer textLayer = image.AddTextLayer("Text 1", new Rectangle(10, 35, image.Width, 35));

    ITextPortion firstPortion = textLayer.TextData.Items[0];
    firstPortion.Style.FontSize = 24;
    firstPortion.Style.FontName = FontSettings.GetAdobeFontName("Comic Sans MS");

    var secondPortion = textLayer.TextData.ProducePortion();
    secondPortion.Text = "Text 2";
    secondPortion.Paragraph.Apply(firstPortion.Paragraph);
    secondPortion.Style.Apply(firstPortion.Style);
    secondPortion.Style.FontName = FontSettings.GetAdobeFontName("Arial");

    textLayer.TextData.AddPortion(secondPortion);
    textLayer.TextData.UpdateLayerData();

    image.Save(outputFilePng, new PngOptions());
    image.Save(outputFilePsd);
}

using (var image = (PsdImage)Image.Load(outputFilePsd))
{
    TextLayer textLayer = (TextLayer)image.Layers[2];

    string adobeFontName1 = FontSettings.GetAdobeFontName("Comic Sans MS");
    string adobeFontName2 = FontSettings.GetAdobeFontName("Arial");

    AssertAreEqual(adobeFontName1, textLayer.TextData.Items[0].Style.FontName);
    AssertAreEqual(adobeFontName2, textLayer.TextData.Items[1].Style.FontName);
}
```

### 関連項目

* class [FontSettings](../)
* 名前空間 [Aspose.PSD](../../fontsettings/)
* 組み立て [Aspose.PSD](../../../)


