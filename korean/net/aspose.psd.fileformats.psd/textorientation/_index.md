---
title: Enum TextOrientation
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.TextOrientation 열거형. 텍스트 방향 모드에 대한 열거.
type: docs
weight: 4010
url: /ko/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

텍스트 방향 모드에 대한 열거.

```csharp
public enum TextOrientation
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Horizontal | `0` | 가로 텍스트 방향입니다. |
| Vertical | `2` | 세로 텍스트 방향입니다. |

### 예

다음 코드는 새 TextOrientation 속성을 편집하는 기능을 보여줍니다. 이것은 현재 렌더링에 영향을 미치지 않지만 속성 값을 편집할 수만 있습니다.

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

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


