---
title: PsdImage.PsdImage
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 건설자. 의 새 인스턴스를 초기화합니다.PsdImage 래스터 이미지에서 지정된 경로의 클래스경로의 psd 이미지가 아님. 기본 매개변수색상 모드  rgb 4채널 채널당 8비트 압축  Raw. 로 psd 이미지를 초기화하는 데 사용됩니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 래스터 이미지에서 지정된 경로의 클래스(경로의 psd 이미지가 아님). 기본 매개변수(색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw. )로 psd 이미지를 초기화하는 데 사용됩니다.

```csharp
public PsdImage(string path)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |

### 또한보십시오

* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 생성자 매개변수가 있는 래스터 이미지(경로의 psd 이미지 아님)에서 지정된 경로의 클래스.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |
| colorMode | ColorModes | 색상 모드입니다. |
| channelBitDepth | Int16 | 채널당 PSD 비트 심도입니다. |
| channels | Int16 | PSD 채널이 계산됩니다. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축입니다. |

### 또한보십시오

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 래스터 이미지(스트림의 psd 이미지 아님)에서 지정된 경로의 클래스. 기본 매개변수(색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw. )로 psd 이미지를 초기화하는 데 사용됩니다.

```csharp
public PsdImage(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |

### 또한보십시오

* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 생성자 매개변수가 있는 래스터 이미지(스트림의 psd 이미지 아님)에서 지정된 경로의 클래스.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |
| colorMode | ColorModes | 색상 모드입니다. |
| channelBitDepth | Int16 | 채널당 PSD 비트 심도입니다. |
| channels | Int16 | PSD 채널이 계산됩니다. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축입니다. |

### 또한보십시오

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../)기존 래스터 이미지(psd 이미지가 아님)의 클래스, RGB 색상 모드, 4채널 8비트/채널 및 압축 없음.

```csharp
public PsdImage(RasterImage rasterImage)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rasterImage | RasterImage | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |

### 또한보십시오

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 생성자 매개변수가 있는 기존 래스터 이미지(psd 이미지 아님)의 클래스.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rasterImage | RasterImage | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |
| colorMode | ColorModes | 색상 모드입니다. |
| channelBitDepth | Int16 | 채널당 PSD 비트 심도입니다. |
| channels | Int16 | PSD 채널이 계산됩니다. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축입니다. |

### 또한보십시오

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 너비와 높이가 지정된 클래스. 빈 psd 이미지를 초기화하는데 사용합니다.

```csharp
public PsdImage(int width, int height)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| width | Int32 | 이미지 너비입니다. |
| height | Int32 | 이미지 높이입니다. |

### 또한보십시오

* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`PsdImage`](../) 지정된 너비, 높이, 팔레트, 색상 모드, 채널 수, 채널 비트 길이 및 지정된 압축 모드 매개변수가 있는 클래스. 빈 psd 이미지를 초기화하는데 사용합니다.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| width | Int32 | 이미지 너비입니다. |
| height | Int32 | 이미지 높이입니다. |
| colorPalette | IColorPalette | 색상 팔레트입니다. |
| colorMode | ColorModes | 색상 모드입니다. |
| channelBitDepth | Int16 | 채널당 PSD 비트 심도입니다. |
| channels | Int16 | PSD 채널이 계산됩니다. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축입니다. |

### 또한보십시오

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


