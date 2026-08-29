---
title: "클래스 ExposureLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.ExposureLayer 클래스. Exposure 조정 레이어"
type: docs
weight: 1800
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/
---
{{< psd/tize >}}
## ExposureLayer class

노출 조정 레이어.

```csharp
public class ExposureLayer : AdjustmentLayer
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경 색상의 값을 가져오거나 설정합니다. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | 이미지의 픽셀당 비트 수를 가져옵니다. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | 클리핑된 요소의 블렌딩을 가져오거나 설정합니다. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | 블렌딩 옵션을 가져옵니다. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | 블렌드 모드 키를 가져오거나 설정합니다. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | 블렌드 모드 서명을 가져옵니다. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | 하단 레이어 위치를 가져오거나 설정합니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 경계를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | 채널 정보를 가져오거나 설정합니다. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | 레이어의 채널 수를 가져옵니다. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | 레이어 클리핑을 가져오거나 설정합니다. 0 = 기본, 1 = 비기본. |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../../aspose.psd/image/) 컨테이너를 가져옵니다. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 객체의 데이터 스트림을 가져옵니다. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | 레이어의 표시 이름을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [Exposure](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/exposure/) { get; set; } | Exposure를 가져오거나 설정합니다. PS에서 Exposure 범위는 -20에서 +20까지입니다. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | 레이어 추가 정보 길이를 바이트 단위로 가져옵니다. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 파일 형식 값을 가져옵니다. |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | 레이어 필러를 가져오거나 설정합니다. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | 채우기 불투명도를 가져오거나 설정합니다. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | 레이어 플래그를 가져오거나 설정합니다. bit 0 = 투명도 보호; bit 1 = 표시; bit 2 = 사용되지 않음; bit 3 = Photoshop 5.0 이후 버전에서는 1이며, bit 4에 유용한 정보가 있는지 알려줍니다; bit 4 = 문서 외관에 영향을 주지 않는 픽셀 데이터. |
| [GammaCorrection](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/gammacorrection/) { get; set; } | GammaCorrection을 가져오거나 설정합니다. PS에서 GammaCorrection 범위는 9.99에서 +0.01까지입니다. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | 이 인스턴스에 알파가 있는지 여부를 나타내는 값을 가져옵니다. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | 이미지 높이를 가져옵니다. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 이 [`RasterImage`](../../aspose.psd/rasterimage/)의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 이 이미지의 불투명도를 가져옵니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 원시 데이터 로딩이 가능한지 여부를 나타내는 값을 가져옵니다. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | 이 인스턴스가 그룹 내에서 표시되는지 여부를 나타내는 값을 가져옵니다(레이어가 그룹에 없으면 루트 그룹을 의미합니다). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | 레이어 블렌딩 범위 데이터를 가져오거나 설정합니다. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | 레이어 생성 날짜 및 시간을 가져오거나 설정합니다. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | 레이어 잠금을 가져오거나 설정합니다. 플래그 LayerFlags.TransparencyProtected가 설정된 경우 레이어 잠금 플래그에 의해 덮어쓰여진다는 점에 유의하십시오. LayerFlags.TransparencyProtected 플래그를 반환하려면 레이어 옵션 layer.Flags &#x7C;= LayerFlags.TransparencyProtected를 적용해야 합니다. |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | 레이어 마스크 데이터를 가져오거나 설정합니다. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | 레이어 옵션을 가져옵니다. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | 왼쪽 레이어 위치를 가져오거나 설정합니다. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | 전체 레이어 길이를 바이트 단위로 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | 레이어 이름을 가져오거나 설정합니다. |
| [Offset](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/offset/) { get; set; } | Offset을 가져오거나 설정합니다. PS에서 Offset 범위는 -0.5에서 +0.5까지입니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | 레이어 불투명도를 가져오거나 설정합니다. 0 = 투명, 255 = 불투명. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 사용자 정의 색상 변환기를 가져오거나 설정합니다. |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 원시 데이터 형식을 가져옵니다. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 현재 원시 데이터 설정을 가져옵니다. 이러한 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 인덱스 색상 변환기를 가져오거나 설정합니다. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 바이트 단위의 원시 라인 크기를 가져옵니다. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | 레이어 리소스를 가져오거나 설정합니다. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | 오른쪽 레이어 위치를 가져오거나 설정합니다. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | 레이어 목록에서 장식 시트 색상 강조를 가져오거나 설정합니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | 상단 레이어 위치를 가져오거나 설정합니다. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 이미지 투명 색상을 가져옵니다. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 이미지 팔레트를 사용할지 여부를 나타내는 값을 가져옵니다. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 원시 데이터 로딩이 가능할 때 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | 이 [`RasterImage`](../../aspose.psd/rasterimage/)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | 이미지 너비를 가져옵니다. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP 메타데이터를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | 마스크를 현재 레이어에 추가합니다. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 이미지 밝기를 조정합니다. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 이미지 대비 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | 이미지의 감마 보정. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | 이미지의 감마 보정. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | 레이어 마스크를 레이어에 적용한 다음 마스크를 삭제합니다. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 미리 정의된 임계값을 사용한 이미지 이진화 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Otsu 임계값 적용을 통한 이미지 이진화 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 데이터를 캐시하고 기본 [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 이미지를 전달된 저장 옵션으로 표시된 지정된 파일 형식으로 저장할 수 있는지 여부를 결정합니다. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | 이미지를 자릅니다. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 시프트를 사용하여 이미지를 자릅니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 현재 이미지에 디더링을 수행합니다. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 현재 이미지에 디더링을 수행합니다. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | 이미지를 레이어에 그립니다. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 지정된 사각형을 필터링합니다. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 이미지의 32비트 ARGB 픽셀을 가져옵니다. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 기본 원시 데이터 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않고 유지하는 데 도움이 될 수 있습니다. 예를 들어, 1비트/픽셀 흑백 PNG 이미지를 로드한 후 [`Save`](../../aspose.psd/datastreamsupporter/save/) 메서드를 사용하여 저장하면 8비트/픽셀 PNG 이미지가 출력됩니다. 이를 방지하고 1비트/픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 두 번째 매개변수로 [`Save`](../../aspose.psd/image/save/) 메서드에 전달하십시오. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 이미지 픽셀을 가져옵니다. 성능 경고: 모든 이미지 픽셀을 반복하는 데 이 메서드를 사용하면 성능 문제가 크게 발생할 수 있으므로 피하십시오. 보다 효율적인 픽셀 조작을 위해 전체 픽셀 배열을 한 번에 가져오는 `LoadArgb32Pixels` 메서드를 사용하십시오. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 기울기 각도를 가져옵니다. 이 메서드는 스캔된 텍스트 문서에 적용되며, 스캔 시 기울기 각도를 결정하는 데 사용됩니다. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | 이미지를 회색조 표현으로 변환 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32비트 ARGB 픽셀을 로드합니다. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64비트 ARGB 픽셀을 로드합니다. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 형식의 픽셀을 로드합니다. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK 형식의 픽셀을 로드합니다. 이 메서드는 더 이상 사용되지 않습니다. 더 효율적인 [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) 메서드를 사용하십시오. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32비트 ARGB 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 픽셀을 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | 레이어를 지정된 레이어에 병합합니다. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서의 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 및 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 메서드를 사용합니다. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서의 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 및 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 메서드를 사용합니다. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 이미지를 크기 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 이미지를 크기 조정합니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 이미지를 크기 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 너비를 비례적으로 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 이미지를 중심을 기준으로 회전합니다. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | 이미지를 중심을 기준으로 회전합니다. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
| [Save](../../aspose.psd/image/save/)() | 이미지 데이터를 기본 스트림에 저장합니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32비트 ARGB 픽셀을 저장합니다. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 픽셀을 저장합니다. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | 픽셀을 저장합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) 메서드를 사용하십시오. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 픽셀을 저장합니다. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 원시 데이터를 저장합니다. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 지정된 위치에 이미지 픽셀을 설정합니다. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | 이 [`RasterImage`](../../aspose.psd/rasterimage/)의 해상도를 설정합니다. |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | 현재 레이어의 얕은 복사본을 생성합니다. 설명은 [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx)를 참조하십시오. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 래스터 이미지를 비트맵으로 변환합니다. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 전체 스캔 라인을 지정된 스캔 라인 인덱스에 기록합니다. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 전체 스캔 라인을 지정된 스캔 라인 인덱스에 기록합니다. |

### 또 보기

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [AdjustmentLayer](../adjustmentlayer/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


