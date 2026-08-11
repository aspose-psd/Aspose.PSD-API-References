---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ColorPaletteHelper 메서드. 래스터 이미지에서 색상 팔레트를 가져오며, 이미지에 팔레트가 없을 경우 이미지를 팔레트화합니다. 팔레트가 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다"
type: docs
weight: 60
url: /ko/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

이미지에 팔레트가 없는 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 이미 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | RasterImage | 래스터 이미지. |
| entriesCount | Int32 | 원하는 항목 수. |

### 반환 값

이미지에서 가장 빈번한 색상으로 시작하고 *entriesCount* 개의 항목을 포함하는 색상 팔레트.

### 또 보기

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

이미지에 팔레트가 없는 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 이미 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | RasterImage | 래스터 이미지. |
| destBounds | Rectangle | 대상 이미지 경계. |
| entriesCount | Int32 | 원하는 항목 수. |

### 반환 값

이미지에서 가장 빈번한 색상으로 시작하고 *entriesCount* 개의 항목을 포함하는 색상 팔레트.

### 또 보기

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

이미지에 팔레트가 없는 경우 래스터 이미지에서 색상 팔레트를 가져옵니다(이미지를 팔레트화). 팔레트가 이미 존재하는 경우 계산을 수행하는 대신 해당 팔레트를 사용합니다.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | RasterImage | 래스터 이미지. |
| destBounds | Rectangle | 대상 이미지 경계. |
| entriesCount | Int32 | 원하는 항목 수. |
| useImagePalette | Boolean | 설정된 경우, 사용 가능한 경우 자체 이미지 팔레트를 사용합니다 |

### 반환 값

이미지에서 가장 빈번한 색상으로 시작하고 *entriesCount* 개의 항목을 포함하는 색상 팔레트.

### 또 보기

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


