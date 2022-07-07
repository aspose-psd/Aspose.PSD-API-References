---
title: ITextParagraph
second_title: Справочник по Aspose.PSD для .NET API
description: Интерфейс для работы с абзацем
type: docs
weight: 3410
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

Интерфейс для работы с абзацем

```csharp
public interface ITextParagraph
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate) { get; set; } | Получает или задает значение, указывающее, используется ли [автоматический перенос]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading) { get; set; } | Получает или задает автоматический интерлиньяж. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari) { get; set; } | Получает или задает значение, указывающее, является ли это[`ITextParagraph`](../itextparagraph)бурасагири. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens) { get; set; } | Получает или задает последовательные дефисы. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent) { get; set; } | Получает или задает конечный отступ. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer) { get; set; } | Получает или задает значение, указывающее, является ли [композитор каждой строки]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent) { get; set; } | Получает или задает отступ первой строки. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing) { get; set; } | Получает или задает интервал между глифами. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging) { get; set; } | Получает или задает значение, указывающее, зависает ли этот[`ITextParagraph`](../itextparagraph). |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize) { get; set; } | Получает или задает размер слова через дефис. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification) { get; set; } | Получает или задает выравнивание. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder) { get; set; } | Получает или задает порядок кинсоку. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype) { get; set; } | Получает или задает тип интерлиньяжа. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing) { get; set; } | Получает или задает межбуквенный интервал. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen) { get; set; } | Получает или устанавливает дефис сообщения. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen) { get; set; } | Получает или задает преддефис. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter) { get; set; } | Получает или устанавливает пробел после. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore) { get; set; } | Получает или устанавливает предшествующий пробел. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent) { get; set; } | Получает или задает начальный отступ. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing) { get; set; } | Получает или задает интервал между словами. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone) { get; set; } | Получает или задает зону. |

## Методы

| Имя | Описание |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply)(ITextParagraph) | Применяет указанный абзац. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal)(ITextParagraph) | Определяет, равен ли указанный абзац. |

### Примеры

Следующий пример демонстрирует, что Выравнивание текста через ITextPortion для языков с письмом справа налево работает правильно.

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

В следующем примере кода демонстрируется редактирование частей текста и стиля их текста.

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

            // Проверка текста каждой порции
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Проверка данных абзаца
            // Абзацы имеют разное обоснование
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Все остальные свойства первого и второго абзаца равны
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

            // Проверка данных стиля
            // Стили имеют разные цвета и размер шрифта
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

            // Пример редактирования текста
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Пример удаления частей текста
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Пример добавления новой текстовой части
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Пример редактирования абзаца и стиля для частей
            // Установить правильное выравнивание
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Разные цвета для каждого стиля. Будет изменено, но рендеринг поддерживается не полностью
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Другой шрифт. Будет изменено, но рендеринг поддерживается не полностью
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

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
