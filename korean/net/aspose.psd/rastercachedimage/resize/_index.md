---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RasterCachedImage 메서드. 이미지 크기 조정"
type: docs
weight: 120
url: /ko/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

이미지를 크기 조정합니다.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새로운 너비. |
| newHeight | Int32 | 새로운 높이. |
| resizeType | ResizeType | 크기 조정 유형입니다. |

## 예제

다음 코드는 새로운 SinC 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Bell 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 Mitchell 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CatmullRom 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicBSpline 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

다음 코드는 새로운 CubicConvolution 리사이즈 유형으로 이미지를 크기 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 또 보기

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

이미지를 크기 조정합니다.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새로운 너비. |
| newHeight | Int32 | 새로운 높이. |
| 설정 | ImageResizeSettings | 크기 조정 설정입니다. |

### 또 보기

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


