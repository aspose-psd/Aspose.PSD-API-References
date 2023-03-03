---
title: FontSettings.GetAdobeFontName
second_title: Référence de l'API Aspose.PSD pour .NET
description: FontSettings méthode. Obtient le nom de la police Adobe par nom de famille de polices.
type: docs
weight: 30
url: /fr/net/aspose.psd/fontsettings/getadobefontname/
---
## FontSettings.GetAdobeFontName method

Obtient le nom de la police Adobe par nom de famille de polices.

```csharp
public static string GetAdobeFontName(string fontFamilyName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontFamilyName | String | Le nom de la famille de polices. |

### Return_Value

Le nom de la police Adobe par nom de famille de polices.

### Exemples

Le code suivant montre la possibilité de modifier le nom de la police au niveau du style de portion.

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

### Voir également

* class [FontSettings](../)
* espace de noms [Aspose.PSD](../../fontsettings/)
* Assemblée [Aspose.PSD](../../../)


