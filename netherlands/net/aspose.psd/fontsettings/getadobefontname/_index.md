---
title: FontSettings.GetAdobeFontName
second_title: Aspose.PSD voor .NET API-referentie
description: FontSettings methode. Haalt de naam van het adobelettertype op naam van de lettertypefamilie.
type: docs
weight: 30
url: /nl/net/aspose.psd/fontsettings/getadobefontname/
---
## FontSettings.GetAdobeFontName method

Haalt de naam van het adobe-lettertype op naam van de lettertypefamilie.

```csharp
public static string GetAdobeFontName(string fontFamilyName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFamilyName | String | De familienaam van het lettertype. |

### Winstwaarde

De naam van het adobe-lettertype op familienaam van het lettertype.

### Voorbeelden

De volgende code demonstreert de mogelijkheid om de lettertypenaam te wijzigen in portiestijl.

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

### Zie ook

* class [FontSettings](../)
* naamruimte [Aspose.PSD](../../fontsettings/)
* montage [Aspose.PSD](../../../)


