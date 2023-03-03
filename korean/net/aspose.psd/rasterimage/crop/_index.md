---
title: RasterImage.Crop
second_title: .NET API 참조용 Aspose.PSD
description: RasterImage 방법. 지정된 사각형을 자릅니다.
type: docs
weight: 240
url: /ko/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

지정된 사각형을 자릅니다.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rectangle | Rectangle | 직사각형. |

### 예

다음 코드 예제는 이미지를 자르고 저장하는 방법을 보여줍니다.

```csharp
[C#]

// PSD 파일에 대한 올바른 자르기 방법을 구현합니다.
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

### 또한보십시오

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* 네임스페이스 [Aspose.PSD](../../rasterimage/)
* 집회 [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

시프트로 이미지 자르기.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| leftShift | Int32 | 왼쪽 교대. |
| rightShift | Int32 | 오른쪽 교대. |
| topShift | Int32 | 최고 교대. |
| bottomShift | Int32 | 하단 이동. |

### 또한보십시오

* class [RasterImage](../)
* 네임스페이스 [Aspose.PSD](../../rasterimage/)
* 집회 [Aspose.PSD](../../../)


