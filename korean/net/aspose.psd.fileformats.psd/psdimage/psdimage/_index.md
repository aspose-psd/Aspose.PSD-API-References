---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 생성자. 지정된 경로의 래스터 이미지(경로에 PSD 이미지가 아님)에서 PsdImage 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수인 색상 모드 rgb, 4채널, 채널당 8비트, 압축 Raw로 PSD 이미지를 초기화하는 데 사용됩니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

지정된 경로의 래스터 이미지(경로에 PSD 이미지가 아님)에서 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수인 색상 모드 rgb, 4채널, 채널당 8비트, 압축 Raw로 PSD 이미지를 초기화하는 데 사용됩니다.

```csharp
public PsdImage(string path)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | String | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |

### 또 보기

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

지정된 경로에 있는 래스터 이미지(경로에 있는 PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | String | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |
| colorMode | ColorModes | 색상 모드. |
| channelBitDepth | Int16 | 채널당 PSD 비트 깊이입니다. |
| channels | Int16 | PSD 채널 수. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축 방식입니다. |

### 또 보기

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

스트림에 있는 래스터 이미지(스트림에 있는 PSD 이미지가 아님)에서 지정된 경로를 사용하여 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수(색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw)로 PSD 이미지를 초기화하는 데 사용됩니다.

```csharp
public PsdImage(Stream stream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |

### 또 보기

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

스트림에 있는 래스터 이미지(스트림에 있는 PSD 이미지가 아님)에서 지정된 경로를 사용하고 생성자 매개변수를 통해 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |
| colorMode | ColorModes | 색상 모드. |
| channelBitDepth | Int16 | 채널당 PSD 비트 깊이입니다. |
| channels | Int16 | PSD 채널 수. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축 방식입니다. |

### 또 보기

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

기존 래스터 이미지(PSD 이미지가 아님)에서 RGB 색상 모드, 4채널, 채널당 8비트, 압축 없음으로 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public PsdImage(RasterImage rasterImage)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rasterImage | RasterImage | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |

### 또 보기

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

기존 래스터 이미지(PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rasterImage | RasterImage | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |
| colorMode | ColorModes | 색상 모드. |
| channelBitDepth | Int16 | 채널당 PSD 비트 깊이입니다. |
| channels | Int16 | PSD 채널 수. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축 방식입니다. |

### 또 보기

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

지정된 너비와 높이로 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다.

```csharp
public PsdImage(int width, int height)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | Int32 | 이미지 너비입니다. |
| height | Int32 | 이미지 높이입니다. |

### 또 보기

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

지정된 너비, 높이, 팔레트, 색상 모드, 채널 수 및 채널 비트 길이와 지정된 압축 모드 매개변수를 사용하여 [`PsdImage`](../) 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | Int32 | 이미지 너비입니다. |
| height | Int32 | 이미지 높이입니다. |
| colorPalette | IColorPalette | 색상 팔레트. |
| colorMode | ColorModes | 색상 모드. |
| channelBitDepth | Int16 | 채널당 PSD 비트 깊이입니다. |
| channels | Int16 | PSD 채널 수. |
| psdVersion | Int32 | PSD 버전입니다. |
| compression | CompressionMethod | 사용할 압축 방식입니다. |

### 또 보기

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


