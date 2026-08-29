---
title: "Enum TextOrientation"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation 열거형. 텍스트 방향 모드에 대한 열거형입니다"
type: docs
weight: 4480
url: /ko/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

텍스트 방향 모드에 대한 열거형입니다.

```csharp
public enum TextOrientation
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Horizontal | `0` | 수평 텍스트 방향입니다. |
| Vertical | `2` | 수직 텍스트 방향입니다. |

## 예제

다음 코드는 새로운 TextOrientation 속성을 편집할 수 있음을 보여줍니다. 현재 렌더링에는 영향을 주지 않으며, 속성 값을 편집할 수 있게 해줍니다.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // 올바른 읽기
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // 올바른 읽기
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


