---
title: Class PsdImage
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.PsdImage 수업. PSD 파일을 로드 편집 저장하고 속성 업데이트 워터마크 추가 그래픽 작업 수행 또는 한 파일 형식을 다른 파일 형식으로 변환하는 기능을 제공하는 PsdImage 클래스를 정의합니다. Aspose.PSD는 레이어로 가져오기 및 다음 형식 Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb 및 선택 가능한 텍스트가 포함된 Pdf로 내보내기
type: docs
weight: 3590
url: /ko/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

PSD 파일을 로드, 편집, 저장하고 속성 업데이트, 워터마크 추가, 그래픽 작업 수행 또는 한 파일 형식을 다른 파일 형식으로 변환하는 기능을 제공하는 PsdImage 클래스를 정의합니다. Aspose.PSD는 레이어로 가져오기 및 다음 형식: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb 및 선택 가능한 텍스트가 포함된 Pdf로 내보내기

```csharp
public sealed class PsdImage : RasterCachedImage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | 의 새 인스턴스를 초기화합니다.`PsdImage`기존 래스터 이미지(psd 이미지가 아님)의 클래스, RGB 색상 모드, 4채널 8비트/채널 및 압축 없음. |
| [PsdImage](psdimage/#constructor_4)(Stream) | 의 새 인스턴스를 초기화합니다.`PsdImage` 래스터 이미지(스트림의 psd 이미지 아님)에서 지정된 경로의 클래스. 기본 매개변수(색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw. )로 psd 이미지를 초기화하는 데 사용됩니다. |
| [PsdImage](psdimage/#constructor_6)(string) | 의 새 인스턴스를 초기화합니다.`PsdImage` 래스터 이미지에서 지정된 경로의 클래스(경로의 psd 이미지가 아님). 기본 매개변수(색상 모드 - rgb, 4채널, 채널당 8비트, 압축 - Raw. )로 psd 이미지를 초기화하는 데 사용됩니다. |
| [PsdImage](psdimage/#constructor_2)(int, int) | 의 새 인스턴스를 초기화합니다.`PsdImage` 너비와 높이가 지정된 클래스. 빈 psd 이미지를 초기화하는데 사용합니다. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | 의 새 인스턴스를 초기화합니다.`PsdImage` 생성자 매개변수가 있는 기존 래스터 이미지(psd 이미지 아님)의 클래스. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | 의 새 인스턴스를 초기화합니다.`PsdImage` 생성자 매개변수가 있는 래스터 이미지(스트림의 psd 이미지 아님)에서 지정된 경로의 클래스. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | 의 새 인스턴스를 초기화합니다.`PsdImage` 생성자 매개변수가 있는 래스터 이미지(경로의 psd 이미지 아님)에서 지정된 경로의 클래스. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | 의 새 인스턴스를 초기화합니다.`PsdImage` 지정된 너비, 높이, 팔레트, 색상 모드, 채널 수, 채널 비트 길이 및 지정된 압축 모드 매개변수가 있는 클래스. 빈 psd 이미지를 초기화하는데 사용합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | 활성 레이어를 가져오거나 설정합니다. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 팔레트 자동 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경색 값을 가져오거나 설정합니다. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | 채널당 비트를 가져옵니다. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | 픽셀당 이미지 비트를 가져옵니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 범위를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | PSD 채널 수를 가져옵니다. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | CMYK PSD 이미지에 대한 CMYK 색상 프로필을 가져오거나 설정합니다. 올바른 색상 변환을 위해 RgbColorProfile과 쌍을 이루어야 합니다. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | 색상 모드를 가져오거나 설정합니다. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | 압축 방법을 가져옵니다. |
| [Container](../../aspose.psd/image/container/) { get; } | 가져오기[`Image`](../../aspose.psd/image/) 컨테이너. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 개체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | 파일 format 의 값을 가져옵니다. |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | 전역 각도를 가져오거나 설정합니다. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | 전역 레이어 마스크 정보를 가져옵니다. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | 전역 계층 리소스를 가져오거나 설정합니다. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | 그레이스케일 PSD 이미지의 GRAY(모노크롬) 색상 프로필을 가져오거나 설정합니다. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | 수직 해상도(인치당 픽셀 수)를 가져오거나 설정합니다.[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | 레이어 데이터를 지정할 때 첫 번째 알파 채널이 병합된 결과에 대한 투명도 데이터를 포함하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 이미지가 투명한 색상인지 여부를 나타내는 값을 가져옵니다. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | 이미지 높이를 가져옵니다. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | 수평 해상도(인치당 픽셀 수)를 가져오거나 설정합니다.`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 이 이미지의 불투명도를 가져옵니다. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | PSD 이미지 리소스를 가져오거나 설정합니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | psd 이미지 병합 여부를 나타내는 값을 가져옵니다. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 원시 데이터 로드 가능 여부를 나타내는 값을 가져옵니다. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | PSD 레이어를 가져오거나 설정합니다. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | 연결된 레이어 관리자를 가져옵니다. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. 픽셀을 직접 표현하는 경우 색상 팔레트를 사용하지 않습니다. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 이미지 구성 요소를 미리 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 사용자 정의 색상 converter 를 가져오거나 설정합니다. |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | 원시 데이터 형식을 가져옵니다. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 현재 원시 데이터 설정을 가져옵니다. 이러한 설정을 사용하면 변환 없이 데이터가 로드됩니다. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 팔레트 인덱스가 범위를 벗어날 때 사용할 폴백 인덱스를 가져오거나 설정합니다. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 인덱스 색상 converter 를 가져오거나 설정합니다. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 원시 라인 크기를 바이트 단위로 가져옵니다. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | CMYK PSD 이미지에 대한 RGB 색상 프로필을 가져오거나 설정합니다. 올바른 색상 변환을 위해 CmykColorProfile과 쌍을 이루어야 합니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | 스마트 개체 공급자를 가져옵니다. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 이미지 투명 색상을 가져옵니다. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP 메타데이터 업데이트 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Raw 데이터 로딩이 가능할 때 Raw 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | 버전을 가져오거나 설정합니다. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | 수직 해상도(인치당 픽셀 수)를 가져오거나 설정합니다.`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | 이미지 너비를 가져옵니다. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | XMP 메타데이터를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | 검정 흰색 조정 레이어를 추가합니다. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | 밝기/대비 조정 레이어를 추가합니다. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | 기본 매개변수 를 사용하여 채널 믹서 조정 레이어를 추가합니다. |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | 색상 균형 조정 레이어를 추가합니다. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | 곡선 조정 레이어를 추가합니다. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | 노출 조정 레이어를 추가합니다. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | 색조/채도 조정 레이어를 추가합니다. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | 반전 조정 레이어를 추가합니다. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | 레이어를 추가합니다. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | 레이어 그룹을 추가합니다. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | 레벨 조정 레이어를 추가합니다. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | PhotoFilter 레이어를 추가합니다. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | 새 일반 레이어를 추가합니다. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | 새 텍스트 레이어를 추가합니다. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | 생동감 조정 레이어를 추가합니다. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | 이미지의 밝기를 조정합니다. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | 이미지 대비 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | 이미지의 감마 보정. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | 이미지의 감마 보정. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | 적분 이미지 thresholding 를 사용하는 Bradley의 적응 임계값 알고리즘을 사용한 이미지의 이진화 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | 적분 이미지 thresholding 를 사용하는 Bradley의 적응 임계값 알고리즘을 사용한 이미지의 이진화 |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | 사전 정의된 threshold 를 사용한 이미지의 이진화 |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Otsu thresholding 를 사용한 이미지의 이진화 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 데이터를 캐시하고 기본에서 추가 데이터 로드가 수행되지 않도록 합니다.[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 전달된 저장 옵션으로 표시되는 지정된 파일 형식으로 이미지를 저장할 수 있는지 여부를 결정합니다. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | 이 이미지 형식을 options. 에 지정된 형식으로 변환합니다. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | 이미지 자르기. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 시프트로 이미지 자르기. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 현재 이미지에서 디더링을 수행합니다. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 현재 이미지에서 디더링을 수행합니다. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | 지정된 사각형을 필터링합니다. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | 모든 레이어를 병합합니다. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 이미지 32비트 ARGB 픽셀을 가져옵니다. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 기본 원시 데이터 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이것은 원본 이미지의 비트 심도 및 기타 매개 변수를 변경하지 않고 유지하는 데 유용할 수 있습니다. 예를 들어 흑백 PNG 이미지를 픽셀당 1비트로 로드한 다음 the 를 사용하여 저장[`Save`](../../aspose.psd/datastreamsupporter/save/) 방법을 사용하면 픽셀당 8비트의 출력 PNG 이미지가 생성됩니다. 이를 피하고 픽셀당 1비트의 PNG 이미지를 저장하려면 이 방법을 사용하여 해당 저장 옵션을 가져오고 them 를[`Save`](../../aspose.psd/image/save/)메소드를 두 번째 매개변수로 지정합니다. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 이미지 픽셀을 가져옵니다. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 기울이기 각도를 가져옵니다. 이 방법은 스캔할 때 기울기 각도를 결정하기 위해 스캔한 텍스트 문서에 적용할 수 있습니다. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | 이미지를 그레이스케일 표현으로 변환 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32비트 ARGB 픽셀을 로드합니다. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64비트 ARGB 픽셀을 로드합니다. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 형식으로 픽셀을 로드합니다. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 팩별로 부분적으로 32비트 ARGB 픽셀을 로드합니다. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 픽셀을 팩 단위로 부분적으로 로드합니다. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 픽셀을 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | 레이어를 병합합니다. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 각도를 정규화합니다. 이 방법은 기울어진 스캔을 제거하기 위해 스캔한 텍스트 문서에 적용할 수 있습니다. 이 방법은 다음을 사용합니다.[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 그리고[`Rotate`](../../aspose.psd/rasterimage/rotate/) 방법. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 각도를 정규화합니다. 이 방법은 기울어진 스캔을 제거하기 위해 스캔한 텍스트 문서에 적용할 수 있습니다. 이 방법은 다음을 사용합니다.[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 그리고[`Rotate`](../../aspose.psd/rasterimage/rotate/) 방법. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 한 색상을 허용되는 차이가 있는 다른 색상으로 바꾸고 원래 알파 값을 유지하여 매끄러운 가장자리를 저장합니다. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | 한 색상을 허용되는 차이가 있는 다른 색상으로 바꾸고 원래 알파 값을 유지하여 매끄러운 가장자리를 저장합니다. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 모든 불투명 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 저장합니다. 참고: 투명하지 않은 이미지에 사용하면 모든 색상이 단일 색상으로 교체됩니다. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | 모든 불투명 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 저장합니다. 참고: 투명하지 않은 이미지에 사용하면 모든 색상이 단일 색상으로 교체됩니다. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 이미지 크기를 조정합니다. 기본값LeftTopToLeftTop사용중입니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 이미지 크기를 조정합니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 이미지 크기를 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 높이를 비례적으로 조정합니다. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 너비를 비례적으로 조정합니다. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | 이미지를 중심으로 회전합니다. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | 이미지를 중심으로 회전합니다. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 이미지를 회전, 뒤집기 또는 회전하고 뒤집습니다. |
| [Save](../../aspose.psd/image/save/)() | 이미지 데이터를 기본 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 개체의 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | 이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32비트 ARGB 픽셀을 저장합니다. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 픽셀을 저장합니다. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 픽셀을 저장합니다. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 원시 데이터를 저장합니다. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 지정된 위치에 대한 이미지 픽셀을 설정합니다. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | 이것에 대한 해상도를 설정합니다.[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 래스터 이미지를 비트맵으로 변환합니다. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 지정된 스캔 라인 인덱스에 전체 스캔 라인을 씁니다. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 지정된 스캔 라인 인덱스에 전체 스캔 라인을 씁니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | 기본 PSD 버전입니다. |

### 예

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

### 또한보십시오

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


