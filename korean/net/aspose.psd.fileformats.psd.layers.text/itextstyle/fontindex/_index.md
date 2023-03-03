---
title: ITextStyle.FontIndex
second_title: .NET API 참조용 Aspose.PSD
description: ITextStyle 재산. 글꼴 인덱스를 가져옵니다.
type: docs
weight: 110
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
## ITextStyle.FontIndex property

글꼴 인덱스를 가져옵니다.

```csharp
public int FontIndex { get; }
```

### 자산 가치

글꼴입니다.

### 예

다음 코드는 Aspose.PSD가 텍스트 레이어의 인라인 서식 속성을 가져오는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
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

        // 텍스트 레이어에 포함된 글꼴 가져오기
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

### 또한보십시오

* interface [ITextStyle](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* 집회 [Aspose.PSD](../../../)


