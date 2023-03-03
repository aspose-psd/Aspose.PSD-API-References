---
title: RasterCachedImage.Resize
second_title: .NET API 참조용 Aspose.PSD
description: RasterCachedImage 방법. 이미지 크기를 조정합니다.
type: docs
weight: 120
url: /ko/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

이미지 크기를 조정합니다.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새 너비입니다. |
| newHeight | Int32 | 새 높이입니다. |
| resizeType | ResizeType | 크기 조정 유형입니다. |

### 예

다음 코드는 새로운 SinC 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Bell 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Mitchell 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CatmullRom 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicBSpline 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicConvolution 크기 조정 유형으로 이미지 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 또한보십시오

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* 네임스페이스 [Aspose.PSD](../../rastercachedimage/)
* 집회 [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

이미지 크기를 조정합니다.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새 너비입니다. |
| newHeight | Int32 | 새 높이입니다. |
| settings | ImageResizeSettings | 크기 조정 설정입니다. |

### 또한보십시오

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* 네임스페이스 [Aspose.PSD](../../rastercachedimage/)
* 집회 [Aspose.PSD](../../../)


