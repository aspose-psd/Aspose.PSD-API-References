---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: .NET API 참조용 Aspose.PSD
description: ColorPaletteHelper 방법. 이미지에 색상 팔레트가 없는 경우 래스터 이미지이미지 팔레트화에서 색상 팔레트를 가져옵니다. 팔레트가 있는 경우 계산을 수행하는 대신 사용됩니다.
type: docs
weight: 60
url: /ko/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

이미지에 색상 팔레트가 없는 경우 래스터 이미지(이미지 팔레트화)에서 색상 팔레트를 가져옵니다. 팔레트가 있는 경우 계산을 수행하는 대신 사용됩니다.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | RasterImage | 래스터 이미지입니다. |
| entriesCount | Int32 | 원하는 항목이 계산됩니다. |

### 반환 값

가장 자주 사용되는 색상으로 시작하는 색상 팔레트*image* 포함*entriesCount* 항목.

### 또한보십시오

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* 네임스페이스 [Aspose.PSD](../../colorpalettehelper/)
* 집회 [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

이미지에 색상 팔레트가 없는 경우 래스터 이미지(이미지 팔레트화)에서 색상 팔레트를 가져옵니다. 팔레트가 있는 경우 계산을 수행하는 대신 사용됩니다.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | RasterImage | 래스터 이미지입니다. |
| destBounds | Rectangle | 대상 이미지 경계입니다. |
| entriesCount | Int32 | 원하는 항목이 계산됩니다. |

### 반환 값

가장 자주 사용되는 색상으로 시작하는 색상 팔레트*image* 포함*entriesCount* 항목.

### 또한보십시오

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* 네임스페이스 [Aspose.PSD](../../colorpalettehelper/)
* 집회 [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

이미지에 색상 팔레트가 없는 경우 래스터 이미지(이미지 팔레트화)에서 색상 팔레트를 가져옵니다. 팔레트가 있는 경우 계산을 수행하는 대신 사용됩니다.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | RasterImage | 래스터 이미지입니다. |
| destBounds | Rectangle | 대상 이미지 경계입니다. |
| entriesCount | Int32 | 원하는 항목이 계산됩니다. |
| useImagePalette | Boolean | 설정하면 사용 가능한 경우 자체 이미지 팔레트를 사용합니다. |

### 반환 값

가장 자주 사용되는 색상으로 시작하는 색상 팔레트*image* 포함*entriesCount* 항목.

### 또한보십시오

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* 네임스페이스 [Aspose.PSD](../../colorpalettehelper/)
* 집회 [Aspose.PSD](../../../)


