---
title: Interface IText
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Text.IText 상호 작용. 텍스트 레이어의 텍스트 편집용 인터페이스
type: docs
weight: 3510
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itext/
---
## IText interface

텍스트 레이어의 텍스트 편집용 인터페이스

```csharp
public interface IText
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.text/itext/items/) { get; } | 항목을 가져옵니다. |
| [Text](../../aspose.psd.fileformats.psd.layers.text/itext/text/) { get; } | 텍스트를 가져옵니다. |
| [TextOrientation](../../aspose.psd.fileformats.psd.layers.text/itext/textorientation/) { get; set; } | 텍스트 방향을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddPortion](../../aspose.psd.fileformats.psd.layers.text/itext/addportion/)(ITextPortion) | 텍스트 부분을 end 에 추가합니다. |
| [InsertPortion](../../aspose.psd.fileformats.psd.layers.text/itext/insertportion/)(ITextPortion, int) | 삽입[`ITextPortion`](../itextportion/) 지정된 position 로 |
| [ProducePortion](../../aspose.psd.fileformats.psd.layers.text/itext/produceportion/)() | 기본 매개변수 를 사용하여 새 부분을 생성합니다. |
| [ProducePortions](../../aspose.psd.fileformats.psd.layers.text/itext/produceportions/)(string[], ITextStyle, ITextParagraph) | 입력 또는 기본 매개변수로 새 부분을 생성합니다. |
| [RemovePortion](../../aspose.psd.fileformats.psd.layers.text/itext/removeportion/)(int) | 지정된 index 에서 부분을 제거합니다. |
| [UpdateLayerData](../../aspose.psd.fileformats.psd.layers.text/itext/updatelayerdata/)() | 레이어 데이터를 업데이트합니다. |

### 예

다음 코드 예제는 편집 텍스트 부분과 해당 텍스트 스타일을 보여줍니다.

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

            // 모든 부분의 텍스트 확인
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // 단락 데이터 확인
            // 단락마다 정당성이 다릅니다.
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // 첫 번째와 두 번째 단락의 다른 모든 속성은 동일합니다.
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

            // 스타일 데이터 확인
            // 스타일은 색상과 글꼴 크기가 다릅니다.
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

            // 텍스트 편집 예제
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // 텍스트 부분 제거 예시
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // 새로운 텍스트 부분을 추가하는 예
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // 부분에 대한 단락 및 스타일 편집의 예
            // 오른쪽 정렬 설정
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // 스타일마다 다른 색상. 이 변경되지만 렌더링이 완전히 지원되지는 않습니다.
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // 다른 글꼴. 이 변경되지만 렌더링이 완전히 지원되지는 않습니다.
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

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* 집회 [Aspose.PSD](../../)


