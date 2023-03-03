---
title: Enum JustificationMode
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.JustificationMode 열거형. 텍스트 정렬 모드입니다.
type: docs
weight: 1650
url: /ko/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

텍스트 정렬 모드입니다.

```csharp
public enum JustificationMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Left | `0` | 왼쪽 맞춤 텍스트입니다. |
| Right | `1` | 오른쪽 맞춤 텍스트입니다. |
| Center | `2` | 가운데 텍스트. |

### 예

다음 코드는 텍스트 부분의 텍스트 정렬을 설정하기 위한 JustificationMode enum 지원을 보여줍니다.

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


