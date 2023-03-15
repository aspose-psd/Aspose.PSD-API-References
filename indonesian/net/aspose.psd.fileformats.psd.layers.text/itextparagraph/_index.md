---
title: Interface ITextParagraph
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextParagraph antarmuka. Antarmuka untuk bekerja dengan paragraf
type: docs
weight: 3520
url: /id/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

Antarmuka untuk bekerja dengan paragraf

```csharp
public interface ITextParagraph
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [tanda hubung otomatis]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading/) { get; set; } | Mendapat atau menyetel awalan otomatis. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah ini`ITextParagraph`adalah burasagiri. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens/) { get; set; } | Mendapat atau menyetel tanda hubung berurutan. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent/) { get; set; } | Mendapat atau menyetel indentasi akhir. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [setiap baris komposer]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent/) { get; set; } | Mendapat atau menyetel indentasi baris pertama. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing/) { get; set; } | Mendapat atau mengatur jarak mesin terbang. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah ini`ITextParagraph` sedang menggantung. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize/) { get; set; } | Mendapat atau menyetel ukuran kata dengan tanda penghubung. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification/) { get; set; } | Mendapat atau menyetel pembenaran. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder/) { get; set; } | Mendapat atau mengatur urutan kinsoku. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype/) { get; set; } | Mendapat atau menetapkan jenis terkemuka. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing/) { get; set; } | Mendapat atau mengatur spasi huruf. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen/) { get; set; } | Mendapat atau menyetel tanda hubung postingan. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen/) { get; set; } | Mendapat atau menyetel pra tanda hubung. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter/) { get; set; } | Mendapat atau menyetel spasi setelahnya. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore/) { get; set; } | Mendapat atau menyetel ruang sebelumnya. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent/) { get; set; } | Mendapat atau menyetel indentasi awal. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing/) { get; set; } | Mendapat atau mengatur spasi kata. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone/) { get; set; } | Mendapat atau mengatur zona. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply/)(ITextParagraph) | Menerapkan paragraf yang ditentukan. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal/)(ITextParagraph) | Menentukan apakah paragraf yang ditentukan sama. |

### Contoh

Contoh berikut menunjukkan bahwa Perataan Teks melalui ITextPortion untuk bahasa kanan ke kiri berfungsi dengan benar.

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

Contoh kode berikut menunjukkan bagian teks pengeditan dan gaya teksnya.

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

            // Memeriksa teks dari setiap bagian
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Memeriksa data paragraf
            // Paragraf memiliki justifikasi yang berbeda
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Semua properti lain dari paragraf pertama dan kedua adalah sama
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

            // Memeriksa data gaya
            // Gaya memiliki warna dan ukuran font yang berbeda
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

            // Contoh pengeditan teks
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Contoh penghapusan bagian teks
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Contoh menambahkan bagian teks baru
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Contoh paragraf dan pengeditan gaya untuk bagian
            // Tetapkan pembenaran yang benar
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Warna berbeda untuk setiap gaya. Itu akan diubah, tetapi rendering tidak sepenuhnya didukung
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Huruf berbeda. Itu akan diubah, tetapi rendering tidak sepenuhnya didukung
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

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* perakitan [Aspose.PSD](../../)


