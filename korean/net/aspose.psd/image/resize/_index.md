---
title: "Image.Resize"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Image 메서드. 이미지를 크기 조정합니다."
type: docs
weight: 200
url: /ko/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

이미지를 크기 조정합니다.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새로운 너비. |
| newHeight | Int32 | 새로운 높이. |
| resizeType | ResizeType | 크기 조정 유형입니다. |

### 또 보기

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

이미지를 크기 조정합니다. 기본 NearestNeighbourResample이 사용됩니다.

```csharp
public void Resize(int newWidth, int newHeight)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새로운 너비. |
| newHeight | Int32 | 새로운 높이. |

## 예제

다음 예제는 PSD 이미지를 크기 조정하는 방법과 Aspose.PSD를 통해 얻은 결과를 보여줍니다.

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또 보기

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

이미지를 크기 조정합니다.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | Int32 | 새로운 너비. |
| newHeight | Int32 | 새로운 높이. |
| 설정 | ImageResizeSettings | 크기 조정 설정입니다. |

### 또 보기

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


