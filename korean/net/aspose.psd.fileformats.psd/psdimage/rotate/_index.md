---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. 이미지를 중심을 기준으로 회전합니다"
type: docs
weight: 670
url: /ko/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

이미지를 중심을 기준으로 회전합니다.

```csharp
public override void Rotate(float angle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | 단일 | 회전 각도(도). 양수 값은 시계 방향으로 회전합니다. |

## 예제

다음 코드는 특정 각도 값으로 이미지를 회전하는 기능을 보여줍니다.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 전체 이미지 회전
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// 레이어 회전
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### 또 보기

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

이미지를 중심을 기준으로 회전합니다.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | 단일 | 회전 각도(도). 양수 값은 시계 방향으로 회전합니다. |
| resizeProportionally | Boolean | `true`로 설정하면 회전된 사각형(코너 포인트) 투영에 따라 이미지 크기가 변경됩니다. 그렇지 않으면 차원은 그대로 유지되고 내부 이미지 내용만 회전합니다. |
| backgroundColor | 색상 | 배경 색상. |

### 또 보기

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


