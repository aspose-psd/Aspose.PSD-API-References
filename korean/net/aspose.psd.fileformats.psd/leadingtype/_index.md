---
title: "열거형 LeadingType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.LeadingType 열거형. Photoshop 리딩 유형은 줄 사이 거리 유형입니다"
type: docs
weight: 4030
url: /ko/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop 리딩 유형(줄 사이 거리 유형)입니다.

```csharp
public enum LeadingType
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| BottomToBottom | `0` | 아래에서 아래로 리딩입니다. |
| TopToTop | `1` | 위에서 위로 리딩입니다. |

## 예제

다음 코드는 단락 설정에서 Bottom-to-bottom 및 Top-to-Top 리딩 모드 지원을 보여줍니다.

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


