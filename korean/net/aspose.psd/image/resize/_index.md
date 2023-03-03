---
title: Image.Resize
second_title: .NET API 참조용 Aspose.PSD
description: Image 방법. 이미지 크기를 조정합니다.
type: docs
weight: 190
url: /ko/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

이미지 크기를 조정합니다.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새 너비입니다. |
| newHeight | Int32 | 새 높이입니다. |
| resizeType | ResizeType | 크기 조정 유형입니다. |

### 또한보십시오

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

이미지 크기를 조정합니다. 기본값LeftTopToLeftTop사용중입니다.

```csharp
public void Resize(int newWidth, int newHeight)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새 너비입니다. |
| newHeight | Int32 | 새 높이입니다. |

### 예

다음 예는 Aspose.PSD에서 얻은 PSD 이미지 및 결과의 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또한보십시오

* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

이미지 크기를 조정합니다.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새 너비입니다. |
| newHeight | Int32 | 새 높이입니다. |
| settings | ImageResizeSettings | 크기 조정 설정입니다. |

### 또한보십시오

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)


