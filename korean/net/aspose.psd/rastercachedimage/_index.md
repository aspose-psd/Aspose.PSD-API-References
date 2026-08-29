---
title: "클래스 RasterCachedImage"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.RasterCachedImage 클래스. 래스터 그래픽 작업을 지원하는 래스터 이미지를 나타냅니다. 필요할 때 이 이미지가 픽셀 데이터를 캐시합니다."
type: docs
weight: 5810
url: /ko/net/aspose.psd/rastercachedimage/
---
{{< psd/tize >}}
## RasterCachedImage class

래스터 그래픽 작업을 지원하는 래스터 이미지를 나타냅니다. 필요할 때 이 이미지가 픽셀 데이터를 캐시합니다.

```csharp
public abstract class RasterCachedImage : RasterImage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경 색상의 값을 가져오거나 설정합니다. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 이미지의 픽셀당 비트 수를 가져옵니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 경계를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../image/) 컨테이너를 가져옵니다. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 객체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 파일 형식 값을 가져옵니다. |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | 이 인스턴스에 알파가 있는지 여부를 나타내는 값을 가져옵니다. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 이미지 높이를 가져옵니다. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 이 [`RasterImage`](../rasterimage/)의 가로 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 이 이미지의 불투명도를 가져옵니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 원시 데이터 로딩이 가능한지 여부를 나타내는 값을 가져옵니다. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 사용자 정의 색상 변환기를 가져오거나 설정합니다. |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 원시 데이터 형식을 가져옵니다. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 현재 원시 데이터 설정을 가져옵니다. 이러한 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 인덱스 색상 변환기를 가져오거나 설정합니다. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 바이트 단위의 원시 라인 크기를 가져옵니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 이미지 투명 색상을 가져옵니다. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 이미지 팔레트를 사용할지 여부를 나타내는 값을 가져옵니다. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 원시 데이터 로딩이 가능할 때 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | 이 [`RasterImage`](../rasterimage/)의 세로 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 이미지 너비를 가져옵니다. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP 메타데이터를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 이미지 밝기를 조정합니다. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 이미지 대비 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | 이미지의 감마 보정. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | 이미지의 감마 보정. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 미리 정의된 임계값을 사용한 이미지 이진화 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Otsu 임계값 적용을 통한 이미지 이진화 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 데이터를 캐시하고 기본 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 이미지를 전달된 저장 옵션으로 표시된 지정된 파일 형식으로 저장할 수 있는지 여부를 결정합니다. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | 이미지를 자릅니다. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 시프트를 사용하여 이미지를 자릅니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 현재 이미지에 디더링을 수행합니다. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 현재 이미지에 디더링을 수행합니다. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 지정된 사각형을 필터링합니다. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 이미지의 32비트 ARGB 픽셀을 가져옵니다. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 기본 원시 데이터 배열을 가져옵니다. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다. 예를 들어, 1비트/픽셀 흑백 PNG 이미지를 로드한 후 [`Save`](../datastreamsupporter/save/) 메서드를 사용해 저장하면 출력 PNG 이미지가 8비트/픽셀로 생성됩니다. 이를 방지하고 1비트/픽셀 PNG 이미지를 저장하려면 이 메서드를 사용해 해당 저장 옵션을 가져오고 두 번째 매개변수로 [`Save`](../image/save/) 메서드에 전달하십시오. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 이미지 픽셀을 가져옵니다. 성능 경고: 모든 이미지 픽셀을 반복하는 데 이 메서드를 사용하면 성능 문제가 크게 발생할 수 있으므로 피하십시오. 보다 효율적인 픽셀 조작을 위해 전체 픽셀 배열을 한 번에 가져오는 `LoadArgb32Pixels` 메서드를 사용하십시오. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 기울기 각도를 가져옵니다. 이 메서드는 스캔된 텍스트 문서에 적용되며, 스캔 시 기울기 각도를 결정하는 데 사용됩니다. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | 이미지를 회색조 표현으로 변환 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32비트 ARGB 픽셀을 로드합니다. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64비트 ARGB 픽셀을 로드합니다. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 형식의 픽셀을 로드합니다. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK 형식으로 픽셀을 로드합니다. 이 메서드는 사용 중단되었습니다. 보다 효율적인 [`LoadCmyk32Pixels`](../rasterimage/loadcmyk32pixels/) 메서드를 사용하십시오. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32비트 ARGB 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 픽셀을 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 원시 데이터를 로드합니다. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서에서 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [`GetSkewAngle`](../rasterimage/getskewangle/) 및 [`Rotate`](../rasterimage/rotate/) 메서드를 사용합니다. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서에서 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [`GetSkewAngle`](../rasterimage/getskewangle/) 및 [`Rotate`](../rasterimage/rotate/) 메서드를 사용합니다. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 이미지를 크기 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | 이미지를 크기 조정합니다. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | 이미지를 크기 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 너비를 비례적으로 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 이미지를 중심을 기준으로 회전합니다. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | 이미지를 중심을 기준으로 회전합니다. |
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
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | 픽셀을 저장합니다. 이 메서드는 사용 중단되었습니다. 보다 효율적인 [`SaveCmyk32Pixels`](../rasterimage/savecmyk32pixels/) 메서드를 사용하십시오. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 픽셀을 저장합니다. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 원시 데이터를 저장합니다. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 지정된 위치에 이미지 픽셀을 설정합니다. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | 이 [`RasterImage`](../rasterimage/)의 해상도를 설정합니다. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 래스터 이미지를 비트맵으로 변환합니다. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 전체 스캔 라인을 지정된 스캔 라인 인덱스에 기록합니다. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 전체 스캔 라인을 지정된 스캔 라인 인덱스에 기록합니다. |

## 예제

다음 코드는 특정 사각형으로 이미지를 자르는 기능을 보여줍니다.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // psd 저장
    image.Save(exportPath, new PsdOptions());

    // png 저장
    image.Save(exportPathPng, new PngOptions());
}
```

### 또 보기

* class [RasterImage](../rasterimage/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


