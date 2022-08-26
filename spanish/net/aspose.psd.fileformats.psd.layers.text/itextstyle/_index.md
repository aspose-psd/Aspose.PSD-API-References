---
title: ITextStyle
second_title: Referencia de API de Aspose.PSD para .NET
description: Interfaz para trabajar con Text Style
type: docs
weight: 3480
url: /es/net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---
## ITextStyle interface

Interfaz para trabajar con Text Style

```csharp
public interface ITextStyle
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoKerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning) { get; set; } | Obtiene o establece el interletraje automático. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autoleading) { get; set; } | Obtiene o establece un valor que indica si [interlineado automático]. |
| [BaselineShift](../../aspose.psd.fileformats.psd.layers.text/itextstyle/baselineshift) { get; set; } | El cambio de línea de base. |
| [ContextualAlternates](../../aspose.psd.fileformats.psd.layers.text/itextstyle/contextualalternates) { get; set; } | Las alternativas contextuales utilizadas para conectar letras. |
| [DiscretionaryLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/discretionaryligatures) { get; set; } | Las ligaduras discrecionales utilizadas para conectar letras, especialmente en fuentes script. |
| [FauxBold](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxbold) { get; set; } | Obtiene o establece que la negrita falsa está habilitada. |
| [FauxItalic](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxitalic) { get; set; } | Obtiene o establece que la negrita falsa está habilitada. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fillcolor) { get; set; } | Obtiene o establece el color del relleno. |
| [FontBaseline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontbaseline) { get; set; } | La línea de base de la fuente. |
| [FontCaps](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontcaps) { get; set; } | La fuente mayúsculas. |
| [FontIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex) { get; } | Obtiene el índice de fuente. |
| [FontName](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontname) { get; set; } | Obtiene o establece el nombre de la fuente. |
| [FontSize](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontsize) { get; set; } | Obtiene o establece el tamaño de la fuente. |
| [Fractions](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fractions) { get; set; } | Los símbolos de fracciones se pueden reemplazar con un glifo especial. |
| [HindiNumbers](../../aspose.psd.fileformats.psd.layers.text/itextstyle/hindinumbers) { get; set; } | Obtiene o establece un valor que indica si [números hindi]. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/horizontalscale) { get; set; } | La escala horizontal. |
| [Kerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/kerning) { get; set; } | Obtiene o establece el kerning. |
| [LanguageIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/languageindex) { get; } | Obtiene el índice de idioma. |
| [Leading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/leading) { get; set; } | Obtiene o establece el interlineado. |
| [StandardLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/standardligatures) { get; set; } | Las ligaduras contextuales estándar utilizadas para unir letras. |
| [Strikethrough](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strikethrough) { get; set; } | Obtiene o establece un valor que indica si [tachado]. |
| [StrokeColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strokecolor) { get; set; } | Obtiene o establece el color del trazo. |
| [Tracking](../../aspose.psd.fileformats.psd.layers.text/itextstyle/tracking) { get; set; } | Obtiene o establece el seguimiento. |
| [Underline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/underline) { get; set; } | Obtiene o establece un valor que indica si [subrayado]. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/verticalscale) { get; set; } | La escala vertical. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextstyle/apply)(ITextStyle) | Aplica el estilo especificado. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isequal)(ITextStyle) | Determina si el estilo especificado es igual. |

### Ejemplos

El siguiente ejemplo demuestra cómo puede representar diferentes estilos en una capa de texto en Aspose.PSD

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

    newPortions[0].Style.Underline = true; // editar estilo de texto "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // editar estilo de texto "2\r"
    newPortions[2].Style.FauxBold = true; // editar estilo de texto "Negrita"
    newPortions[3].Style.FauxItalic = true; // editar estilo de texto "Cursiva\r"
    newPortions[3].Style.BaselineShift = -25; // editar estilo de texto "Cursiva\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // editar estilo de texto "Texto en minúsculas"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

El siguiente código demuestra cómo obtener el tamaño de fuente para cualquier parte de texto en la capa de texto.

```csharp
[C#]

// Tamaño de fuente incorrecto extraído 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Antigua API (Usando la fuente del primer párrafo)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Comprobando el tamaño de fuente base
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Comprobando el tamaño de fuente real
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nueva API (una capa de texto puede contener cualquier cantidad de tamaños de fuente)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Comprobando el tamaño de fuente de la porción base
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Comprobando el tamaño de fuente de la porción real
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

El siguiente ejemplo de código muestra la edición de porciones de texto y su estilo de texto.

```csharp
[C#]

const double Tolerance = 0.0001;
var filePath = "ThreeColorsParagraphs.psd";
var outputPath = "ThreeColorsParagraph_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var layer = im.Layers[i] as TextLayer;

        if (layer != null)
        {
            var portions = layer.TextData.Items;

            if (portions.Length != 4)
            {
                throw new Exception();
            }

            // Verificando el texto de cada porción
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Verificando los datos de los párrafos
            // Los párrafos tienen diferente justificación
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Todas las demás propiedades del primer y segundo párrafo son iguales
            for (int j = 0; j < portions.Length; j++)
            {
                var paragraph = portions[j].Paragraph;

                if (Math.Abs(paragraph.AutoLeading - 1.2) > Tolerance ||
                    paragraph.AutoHyphenate != false ||
                    paragraph.Burasagari != false ||
                    paragraph.ConsecutiveHyphens != 8 ||
                    Math.Abs(paragraph.StartIndent) > Tolerance ||
                    Math.Abs(paragraph.EndIndent) > Tolerance ||
                    paragraph.EveryLineComposer != false ||
                    Math.Abs(paragraph.FirstLineIndent) > Tolerance ||
                    paragraph.GlyphSpacing.Length != 3 ||
                    Math.Abs(paragraph.GlyphSpacing[0] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[1] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[2] - 1) > Tolerance ||
                    paragraph.Hanging != false ||
                    paragraph.HyphenatedWordSize != 6 ||
                    paragraph.KinsokuOrder != 0 ||
                    paragraph.LetterSpacing.Length != 3 ||
                    Math.Abs(paragraph.LetterSpacing[0]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[1]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[2]) > Tolerance ||
                    paragraph.LeadingType != LeadingMode.Auto ||
                    paragraph.PreHyphen != 2 ||
                    paragraph.PostHyphen != 2 ||
                    Math.Abs(paragraph.SpaceBefore) > Tolerance ||
                    Math.Abs(paragraph.SpaceAfter) > Tolerance ||
                    paragraph.WordSpacing.Length != 3 ||
                    Math.Abs(paragraph.WordSpacing[0] - 0.8) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[1] - 1.0) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[2] - 1.33) > Tolerance ||
                    Math.Abs(paragraph.Zone - 36.0) > Tolerance)
                {
                    throw new Exception();
                }
            }

            // Comprobando datos de estilo
            // Los estilos tienen diferentes colores y tamaños de letra
            if (Math.Abs(portions[0].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[1].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[2].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[3].Style.FontSize - 10) > Tolerance)
            {
                throw new Exception();
            }

            if (portions[0].Style.FillColor != Color.FromArgb(255, 145, 0, 0) ||
                portions[1].Style.FillColor != Color.FromArgb(255, 201, 128, 2) ||
                portions[2].Style.FillColor != Color.FromArgb(255, 18, 143, 4) ||
                portions[3].Style.FillColor != Color.FromArgb(255, 145, 42, 100))
            {
                throw new Exception();
            }

            for (int j = 0; j < portions.Length; j++)
            {
                var style = portions[j].Style;

                if (style.AutoLeading != true ||
                    style.HindiNumbers != false ||
                    style.Kerning != 0 ||
                    style.Leading != 0 ||
                    style.StrokeColor != Color.FromArgb(255, 175, 90, 163) ||
                    style.Tracking != 50)
                {
                    throw new Exception();
                }
            }

            // Ejemplo de edición de texto
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Ejemplo de eliminación de porciones de texto
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Ejemplo de cómo agregar una nueva porción de texto
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Ejemplo de edición de párrafo y estilo para porciones
            // Establecer justificación correcta
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Diferentes colores para cada estilo. Se cambiará, pero el renderizado no es totalmente compatible.
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Fuente diferente. Se cambiará, pero el renderizado no es totalmente compatible.
            portions[0].Style.FontSize = 6;
            portions[1].Style.FontSize = 8;
            portions[2].Style.FontSize = 10;

            layer.TextData.UpdateLayerData();

            im.Save(outputPath, new PsdOptions(im));

            break;
        }
    }
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
