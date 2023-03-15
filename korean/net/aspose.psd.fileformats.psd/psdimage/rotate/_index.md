---
title: PsdImage.Rotate
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 방법. 이미지를 중심으로 회전합니다.
type: docs
weight: 610
url: /ko/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

이미지를 중심으로 회전합니다.

```csharp
public override void Rotate(float angle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| angle | Single | 회전 각도(도)입니다. 양수 값은 시계 방향으로 회전합니다. |

### 예

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

### 또한보십시오

* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

이미지를 중심으로 회전합니다.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| angle | Single | 회전 각도(도)입니다. 양수 값은 시계 방향으로 회전합니다. |
| resizeProportionally | Boolean | 로 설정된 경우`진실` 치수를 그대로 두고 내부 이미지 내용만 회전하는 경우 회전된 직사각형(모서리 점) 투영에 따라 이미지 크기가 변경됩니다. |
| backgroundColor | Color | 배경색. |

### 또한보십시오

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


