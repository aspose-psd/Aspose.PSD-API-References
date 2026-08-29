---
title: "TextFontInfo.Style"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TextFontInfo 속성. 서브패밀리 이름에서 파싱된 글꼴 스타일을 가져옵니다"
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
{{< psd/tize >}}
## TextFontInfo.Style property

하위 패밀리 이름에서 구문 분석된 글꼴 스타일을 가져옵니다

```csharp
public FontStyle Style { get; }
```

### Property Value

서브패밀리 이름에서 파싱된 글꼴 스타일

## 예제

다음 코드는 Aspose.PSD가 텍스트 레이어의 인라인 서식 속성을 가져오는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // 텍스트 레이어에 포함된 글꼴을 가져옵니다
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### 또 보기

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


