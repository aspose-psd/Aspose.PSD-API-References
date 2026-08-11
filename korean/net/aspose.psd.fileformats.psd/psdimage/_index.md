---
title: "클래스 PsdImage"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.PsdImage 클래스. PSD 파일을 로드, 편집, 저장하고 속성을 업데이트하고 워터마크를 추가하며 그래픽 작업을 수행하거나 파일 형식을 다른 형식으로 변환할 수 있는 기능을 제공하는 PsdImage 클래스를 정의합니다. Aspose.PSD는 레이어로 가져오기와 다음 형식으로 내보내기를 지원합니다: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb 및 선택 가능한 텍스트가 있는 Pdf."
type: docs
weight: 4050
url: /ko/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

PsdImage 클래스를 정의하며, 이 클래스는 PSD 파일을 로드, 편집, 저장하고 속성을 업데이트하며 워터마크를 추가하고 그래픽 작업을 수행하거나 파일 형식을 다른 형식으로 변환할 수 있는 기능을 제공합니다. Aspose.PSD는 레이어로 가져오기를 지원하고 다음 형식으로 내보낼 수 있습니다: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb 및 선택 가능한 텍스트가 포함된 Pdf로 내보내기.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | `PsdImage` 클래스의 새 인스턴스를 기존 래스터 이미지(PSD 이미지가 아님)에서 RGB 색상 모드, 4채널, 8비트/채널, 압축 없음으로 초기화합니다. |
| [PsdImage](psdimage/#constructor_4)(Stream) | 지정된 경로의 래스터 이미지(스트림의 PSD 이미지가 아님)에서 `PsdImage` 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수로 PSD 이미지를 초기화하는 데 사용됩니다 - 색상 모드: rgb, 4채널, 8비트/채널, 압축: Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | 지정된 경로의 래스터 이미지(경로의 PSD 이미지가 아님)에서 `PsdImage` 클래스의 새 인스턴스를 초기화합니다. 기본 매개변수로 PSD 이미지를 초기화하는 데 사용됩니다 - 색상 모드: rgb, 4채널, 8비트/채널, 압축: Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | 지정된 너비와 높이로 `PsdImage` 클래스의 새 인스턴스를 초기화합니다. 빈 PSD 이미지를 초기화하는 데 사용됩니다. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | 기존 래스터 이미지(PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 `PsdImage` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | 지정된 경로의 래스터 이미지(스트림의 PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 `PsdImage` 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | 지정된 경로의 래스터 이미지(경로에 있는 psd 이미지가 아님)에서 생성자 매개변수를 사용하여 `PsdImage` 클래스를 새 인스턴스로 초기화합니다. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | 지정된 너비, 높이, paletter, 색 모드, 채널 수 및 채널 비트 길이와 지정된 압축 모드 매개변수를 사용하여 `PsdImage` 클래스를 새 인스턴스로 초기화합니다. 빈 psd 이미지를 초기화하는 데 사용됩니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | 활성 레이어를 가져오거나 설정합니다. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경 색상의 값을 가져오거나 설정합니다. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | 채널당 비트를 가져옵니다. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | 이미지의 픽셀당 비트 수를 가져옵니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 경계를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | PSD 채널 수를 가져옵니다. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | CMYK PSD 이미지에 대한 CMYK 색 프로파일을 가져오거나 설정합니다. 올바른 색 변환을 위해 RgbColorProfile과 쌍을 이루어야 합니다. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | 색 모드를 가져오거나 설정합니다. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | 압축 방식을 가져옵니다. |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../../aspose.psd/image/) 컨테이너를 가져옵니다. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 객체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | 파일 형식 값을 가져옵니다. |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | 전역 각도를 가져오거나 설정합니다. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | 전역 레이어 마스크 정보를 가져옵니다. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | 전역 레이어 리소스를 가져오거나 설정합니다. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | 그레이스케일 PSD 이미지에 대한 GRAY(단색) 색 프로파일을 가져오거나 설정합니다. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | 이 [`RasterImage`](../../aspose.psd/rasterimage/)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | 레이어 데이터를 지정할 때 첫 번째 알파 채널이 병합 결과에 대한 투명도 데이터를 포함하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | 이미지 높이를 가져옵니다. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | 이 `PsdImage`의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 이 이미지의 불투명도를 가져옵니다. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | PSD 이미지 리소스를 가져오거나 설정합니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | PSD 이미지가 평탄화되었는지 여부를 나타내는 값을 가져옵니다. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 원시 데이터 로딩이 가능한지 여부를 나타내는 값을 가져옵니다. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | PSD 레이어를 가져오거나 설정합니다. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | 연결된 레이어 관리자를 가져옵니다. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 사용자 정의 색상 변환기를 가져오거나 설정합니다. |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | 원시 데이터 형식을 가져옵니다. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 현재 원시 데이터 설정을 가져옵니다. 이러한 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 인덱스 색상 변환기를 가져오거나 설정합니다. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 바이트 단위의 원시 라인 크기를 가져옵니다. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | CMYK PSD 이미지에 대한 RGB 색 프로파일을 가져오거나 설정합니다. 올바른 색 변환을 위해 CmykColorProfile과 쌍을 이루어야 합니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | 스마트 객체 제공자를 가져옵니다. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | `PsdImage`의 [`Timeline`](./timeline/)을 가져옵니다. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 이미지 투명 색상을 가져옵니다. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 이미지 팔레트를 사용할지 여부를 나타내는 값을 가져옵니다. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 원시 데이터 로딩이 가능할 때 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | 버전을 가져오거나 설정합니다. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | 이 `PsdImage`의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | 이미지 너비를 가져옵니다. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | XMP 메타데이터를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | 흑백 조정 레이어를 추가합니다. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | 밝기/대비 조정 레이어를 추가합니다. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | 기본 매개변수로 채널 믹서 조정 레이어를 추가합니다 |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | 색 균형 조정 레이어를 추가합니다. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | 곡선 조정 레이어를 추가합니다. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | 노출 조정 레이어를 추가합니다. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | 그라디언트 맵 조정 레이어를 추가합니다. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | 색조/채도 조정 레이어를 추가합니다. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | 반전 조정 레이어를 추가합니다. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | 레이어를 추가합니다. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | 레이어 그룹을 추가합니다. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | 레벨 조정 레이어를 추가합니다. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | 포토 필터 레이어를 추가합니다. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | 포스터라이즈 조정 레이어를 추가합니다. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | 새 일반 레이어를 추가합니다. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | 선택 색상 조정 레이어를 추가합니다. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | 빈 쉐이프 레이어를 추가합니다. 경로 없이. 저장하기 전에 쉐이프 레이어에 추가되어야 합니다. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | 새 텍스트 레이어를 추가합니다. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | 임계값 조정 레이어를 추가합니다. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | 비브런스 조정 레이어를 추가합니다. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | 이미지 밝기를 조정합니다. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | 이미지 대비 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | 이미지의 감마 보정. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | 이미지의 감마 보정. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | 미리 정의된 임계값을 사용한 이미지 이진화 |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Otsu 임계값 적용을 통한 이미지 이진화 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 데이터를 캐시하고 기본 [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 이미지를 전달된 저장 옵션으로 표시된 지정된 파일 형식으로 저장할 수 있는지 여부를 결정합니다. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | 이 이미지 형식을 옵션에 지정된 형식으로 변환합니다. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | 이미지를 자릅니다. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 시프트를 사용하여 이미지를 자릅니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 현재 이미지에 디더링을 수행합니다. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 현재 이미지에 디더링을 수행합니다. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | 지정된 사각형을 필터링합니다. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | 모든 레이어를 평탄화합니다. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 이미지의 32비트 ARGB 픽셀을 가져옵니다. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 기본 원시 데이터 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않고 유지하는 데 도움이 될 수 있습니다. 예를 들어, 1비트/픽셀 흑백 PNG 이미지를 로드한 후 [`Save`](../../aspose.psd/datastreamsupporter/save/) 메서드를 사용하여 저장하면 8비트/픽셀 PNG 이미지가 출력됩니다. 이를 방지하고 1비트/픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 두 번째 매개변수로 [`Save`](../../aspose.psd/image/save/) 메서드에 전달하십시오. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 이미지 픽셀을 가져옵니다. 성능 경고: 모든 이미지 픽셀을 반복하는 데 이 메서드를 사용하면 성능 문제가 크게 발생할 수 있으므로 피하십시오. 보다 효율적인 픽셀 조작을 위해 전체 픽셀 배열을 한 번에 가져오는 `LoadArgb32Pixels` 메서드를 사용하십시오. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 기울기 각도를 가져옵니다. 이 메서드는 스캔된 텍스트 문서에 적용되며, 스캔 시 기울기 각도를 결정하는 데 사용됩니다. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | 이미지를 회색조 표현으로 변환 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32비트 ARGB 픽셀을 로드합니다. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64비트 ARGB 픽셀을 로드합니다. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 형식의 픽셀을 로드합니다. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK 형식의 픽셀을 로드합니다. 이 메서드는 더 이상 사용되지 않습니다. 더 효율적인 [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) 메서드를 사용하십시오. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32비트 ARGB 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 픽셀을 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | 레이어를 병합합니다. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서의 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 및 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 메서드를 사용합니다. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서의 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 및 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 메서드를 사용합니다. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 이미지를 크기 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 이미지를 크기 조정합니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 이미지를 크기 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 높이를 비례적으로 조정합니다. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 너비를 비례적으로 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | 이미지를 중심을 기준으로 회전합니다. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | 이미지를 중심을 기준으로 회전합니다. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
| [Save](../../aspose.psd/image/save/)() | 이미지 데이터를 기본 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32비트 ARGB 픽셀을 저장합니다. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 픽셀을 저장합니다. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | 픽셀을 저장합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) 메서드를 사용하십시오. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 픽셀을 저장합니다. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 원시 데이터를 저장합니다. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 지정된 위치에 이미지 픽셀을 설정합니다. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | `PsdImage`의 해상도를 설정합니다. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 래스터 이미지를 비트맵으로 변환합니다. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 전체 스캔 라인을 지정된 스캔 라인 인덱스에 기록합니다. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 전체 스캔 라인을 지정된 스캔 라인 인덱스에 기록합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | 기본 PSD 버전입니다. |

## 예제

다음 코드는 특정 각도 값으로 이미지를 회전하는 기능을 보여줍니다.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 전체 이미지 회전
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// 레이어 회전
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### 또 보기

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


