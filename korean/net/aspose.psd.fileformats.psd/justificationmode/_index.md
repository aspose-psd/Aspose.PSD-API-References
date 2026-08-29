---
title: "열거형 JustificationMode"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. 텍스트 정렬 모드"
type: docs
weight: 1690
url: /ko/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

텍스트 정렬 모드입니다.

```csharp
public enum JustificationMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Left | `0` | 텍스트를 왼쪽 정렬합니다. 왼쪽에서 오른쪽 모드에서는 Left 위치가 왼쪽입니다. 오른쪽에서 왼쪽 모드에서는 Left 위치가 오른쪽입니다. |
| Right | `1` | 텍스트를 오른쪽 정렬합니다. 왼쪽에서 오른쪽 모드에서는 Right 위치가 오른쪽입니다. 오른쪽에서 왼쪽 모드에서는 Right 위치가 왼쪽입니다. |
| Center | `2` | 텍스트를 가운데 정렬합니다. |

## 예제

다음 코드는 JustificationMode 열거형을 사용하여 텍스트 부분의 정렬을 설정하는 예를 보여줍니다.

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

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


