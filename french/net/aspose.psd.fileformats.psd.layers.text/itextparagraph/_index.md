---
title: "Interface ITextParagraph"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Interface Aspose.PSD.FileFormats.Psd.Layers.Text.ITextParagraph. L'interface pour travailler avec les paragraphes"
type: docs
weight: 3940
url: /fr/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
{{< psd/tize >}}
## ITextParagraph interface

L'interface pour travailler avec les paragraphes

```csharp
public interface ITextParagraph
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate/) { get; set; } | Obtient ou définit une valeur indiquant si [automatic hyphenate]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading/) { get; set; } | Obtient ou définit l'interligne automatique. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari/) { get; set; } | Obtient ou définit une valeur indiquant si ce `ITextParagraph` est burasagiri. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens/) { get; set; } | Obtient ou définit les tirets consécutifs. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent/) { get; set; } | Obtient ou définit le retrait de fin. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer/) { get; set; } | Obtient ou définit une valeur indiquant si [every line composer]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent/) { get; set; } | Obtient ou définit le retrait de la première ligne. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing/) { get; set; } | Obtient ou définit l'espacement des glyphes. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging/) { get; set; } | Obtient ou définit une valeur indiquant si ce `ITextParagraph` est suspendu. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize/) { get; set; } | Obtient ou définit la taille du mot hyphéné. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification/) { get; set; } | Obtient ou définit la justification. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder/) { get; set; } | Obtient ou définit l'ordre kinsoku. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype/) { get; set; } | Obtient ou définit le type du leading. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing/) { get; set; } | Obtient ou définit l'espacement des caractères. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen/) { get; set; } | Obtient ou définit le tiret postérieur. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen/) { get; set; } | Obtient ou définit le tiret antérieur. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter/) { get; set; } | Obtient ou définit l'espace après. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore/) { get; set; } | Obtient ou définit l'espace avant. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent/) { get; set; } | Obtient ou définit le retrait de départ. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing/) { get; set; } | Obtient ou définit l'espacement des mots. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone/) { get; set; } | Obtient ou définit la zone. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply/)(ITextParagraph) | Applique le paragraphe spécifié. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal/)(ITextParagraph) | Détermine si le paragraphe spécifié est égal. |

## Exemples

L'exemple suivant montre que l'alignement du texte via ITextPortion pour les langues de droite à gauche fonctionne correctement.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

L'exemple de code suivant montre l'édition des portions de texte et leur style de texte.

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

            // Vérification du texte de chaque portion
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Vérification des données des paragraphes
            // Les paragraphes ont une justification différente
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Toutes les autres propriétés du premier et du deuxième paragraphe sont égales
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
                    paragraph.LeadingType != LeadingType.BottomToBottom ||
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

            // Vérification des données de style
            // Les styles ont des couleurs et une taille de police différentes
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

            // Exemple d'édition de texte
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Exemple de suppression de portions de texte
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Exemple d'ajout d'une nouvelle portion de texte
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Exemple d'édition de paragraphes et de styles pour les portions
            // Définir la justification à droite
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Différentes couleurs pour chaque style. Elles seront modifiées, mais le rendu n'est pas entièrement pris en charge
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Police différente. Elle sera modifiée, mais le rendu n'est pas entièrement pris en charge
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

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../)


