---
title: "FontSettings.GetAdobeFontName"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "FontSettings method. Obtiene el nombre de fuente adobe por nombre de familia de fuente"
type: docs
weight: 40
url: /es/net/aspose.psd/fontsettings/getadobefontname/
---
{{< psd/tize >}}
## FontSettings.GetAdobeFontName method

Obtiene el nombre de fuente de Adobe por el nombre de la familia de fuentes.

```csharp
public static string GetAdobeFontName(string fontFamilyName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamilyName | String | El nombre de la familia de fuentes. |

### Valor devuelto

El nombre de fuente adobe por nombre de familia de fuente.

## Ejemplos

El siguiente código demuestra la capacidad de cambiar el nombre de la fuente en el estilo de porción.

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

    TextLayer textLayer = image.AddTextLayer("Text 1", new Rectangle(10, 35, image.Width, 60));

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

### Ver también

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


