---
title: "RasterImage.Crop"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RasterImage 메서드. 지정된 사각형을 잘라냅니다"
type: docs
weight: 240
url: /ko/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

지정된 사각형을 잘라냅니다.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 사각형 | Rectangle | 직사각형입니다. |

## 예제

다음 코드 예제는 이미지를 잘라내고 저장하는 방법을 보여줍니다.

```csharp
[C#]

// PSD 파일에 대한 올바른 Crop 메서드를 구현하십시오.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또 보기

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

시프트를 사용하여 이미지를 자릅니다.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| leftShift | Int32 | 왼쪽 시프트입니다. |
| rightShift | Int32 | 오른쪽 시프트입니다. |
| topShift | Int32 | 위쪽 시프트입니다. |
| bottomShift | Int32 | 아래쪽 시프트입니다. |

### 또 보기

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


