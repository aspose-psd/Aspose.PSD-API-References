---
title: "PsdImage"
second_title: "Java용 Aspose.PSD API 참조"
description: "PsdImage 클래스를 정의하며, PSD 파일을 로드, 편집, 저장하고, 속성을 업데이트하고, 워터마크를 추가하며, 그래픽 작업을 수행하거나 파일 형식을 다른 형식으로 변환하는 기능을 제공합니다."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

PsdImage 클래스를 정의하며, PSD 파일을 로드, 편집, 저장하고, 속성을 업데이트하고, 워터마크를 추가하며, 그래픽 작업을 수행하거나 파일 형식을 다른 형식으로 변환하는 기능을 제공합니다. Aspose.PSD는 레이어로 가져오기 및 다음 형식으로 내보내기를 지원합니다: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb와 선택 가능한 텍스트가 있는 Pdf 내보내기.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | 지정된 경로의 래스터 이미지(경로에 PSD 이미지가 아님)에서 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | 지정된 경로의 래스터 이미지(경로에 PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | 지정된 스트림의 래스터 이미지(스트림에 PSD 이미지가 아님)에서 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | 지정된 스트림의 래스터 이미지(스트림에 PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | 기존 래스터 이미지(PSD 이미지가 아님)에서 RGB 색상 모드, 4채널, 8비트/채널, 압축 없음으로 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | 기존 래스터 이미지(PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | 지정된 너비와 높이로 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | 지정된 너비, 높이, paletter, 색상 모드, 채널 수 및 채널 비트 길이와 지정된 압축 모드 매개변수로 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | 기본 인코딩 이름 |
| [DefaultVersion](#DefaultVersion) | 기본 PSD 버전. |
| [OnCreate_internalized](#OnCreate-internalized) | 이미지가 로드될 때 발생합니다. |
| [OnLoad_internalized](#OnLoad-internalized) | 이미지가 createFirstSupportedLoader에 의해 로드될 때 발생합니다. |
| [OnSave_internalized](#OnSave-internalized) | 이미지가 로드되거나 저장될 때 발생합니다. |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | 크레딧이 사용될 때 발생합니다. |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | 레이어에 대한 접근을 동기화하는 데 사용할 수 있는 객체. |
| [horizontalResolution](#horizontalResolution) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | 흑백 조정 레이어를 추가합니다. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | 밝기/대비 조정 레이어를 추가합니다. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | 채널 믹서 조정 레이어를 기본 매개변수와 함께 추가합니다 |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | 색상 균형 조정 레이어를 추가합니다. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Curves Adjustment 레이어를 추가합니다. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | 노출 조정 레이어를 추가합니다. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | GradientMap Adjustment 레이어를 추가합니다. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | 색조/채도 조정 레이어를 추가합니다. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | 반전 조정 레이어를 추가합니다. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | 레이어를 추가합니다. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | 레이어 그룹을 추가합니다. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | 지정된 인덱스에 레이어를 추가합니다. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Levels 조정 레이어를 추가합니다. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | 포토필터 레이어를 추가합니다. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Posterize Adjustment 레이어를 추가합니다. |
| [addRegularLayer()](#addRegularLayer--) | 새 일반 레이어를 추가합니다. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | 선택 색상 조정 레이어를 추가합니다. |
| [addShapeLayer()](#addShapeLayer--) | 빈 Shape 레이어를 추가합니다. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | 새 Text 레이어를 추가합니다. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Threshold 조정 레이어를 추가합니다. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Vibrance 조정 레이어를 추가합니다. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 이미지 밝기를 조정합니다. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 이미지 대비 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 이미지의 감마 보정. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 이미지의 감마 보정. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | 크기 조정 프로세스를 시작합니다. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 미리 정의된 임계값으로 이미지를 이진화합니다. |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu 임계값을 사용하여 이미지를 이진화합니다. |
| [cacheData()](#cacheData--) | 데이터를 캐시하고 기본 DataStreamSupporter.DataStreamContainer에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 이미지를 지정된 스트림에서 로드할 수 있는지 여부를 결정합니다. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 이미지를 지정된 스트림에서 로드할 수 있는지 여부를 결정하고, 선택적으로 지정된 loadOptions를 사용합니다. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 지정된 파일 경로에서 이미지를 로드할 수 있는지, 그리고 선택적으로 지정된 열기 옵션을 사용할 수 있는지 확인합니다. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 전달된 저장 옵션으로 표시된 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다. |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | 옵션에 지정된 형식으로 이 이미지 형식을 변환합니다. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps 형식으로 변환합니다. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 지정된 이미지를 페이지로 사용하여 새 이미지를 생성합니다. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 지정된 이미지를 페이지로 하여 새 이미지를 생성합니다. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | 새 인스턴스를 생성합니다 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | 이미지를 자릅니다. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 시프트를 사용하여 이미지를 자릅니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | 현재 이미지에 디더링을 수행합니다. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | 현재 이미지에 디더링을 수행합니다. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | 이미지를 자릅니다. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | 이미지 크기를 조정합니다. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | 지정된 사각형을 필터링합니다. |
| [flattenImage()](#flattenImage--) | 모든 레이어를 평탄화합니다. |
| [getActiveLayer()](#getActiveLayer--) | 활성 레이어를 가져오거나 설정합니다. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | 이미지의 32비트 ARGB 픽셀을 가져옵니다. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 자동 팔레트 조정 여부를 나타내는 값을 가져옵니다. |
| [getBackgroundColor()](#getBackgroundColor--) | 배경 색상의 값을 가져오거나 설정합니다. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | 배경 색상을 가져오거나 설정합니다. |
| [getBitsPerChannel()](#getBitsPerChannel--) | 채널당 비트를 가져옵니다. |
| [getBitsPerPixel()](#getBitsPerPixel--) | 이미지의 픽셀당 비트 수를 가져옵니다. |
| [getBounds()](#getBounds--) | 이미지 경계를 가져옵니다. |
| [getBufferSizeHint()](#getBufferSizeHint--) | 내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다. |
| [getChannelsCount()](#getChannelsCount--) | PSD 채널 수를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK PSD 이미지에 대한 CMYK 색상 프로필을 가져오거나 설정합니다. |
| [getColorMode()](#getColorMode--) | 색상 모드를 가져오거나 설정합니다. |
| [getCompression()](#getCompression--) | 압축 방식을 가져옵니다. |
| [getContainer()](#getContainer--) | 이미지 컨테이너를 가져옵니다. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | 현재 이미지 옵션을 가져옵니다. |
| [getDataStreamContainer()](#getDataStreamContainer--) | 객체의 데이터 스트림을 가져옵니다. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 깊이 조정 팔레트를 가져옵니다. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | 기본 32비트 ARGB 픽셀 배열을 가져옵니다. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 기본 옵션을 가져옵니다. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | 부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | 기본 원시 데이터 배열을 가져옵니다. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | 기본 교체 글꼴을 가져오거나 설정합니다. |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getFileFormat()](#getFileFormat--) | 파일 형식 값을 가져옵니다 |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | 파일 형식을 가져옵니다. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | 파일 형식을 가져옵니다. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | 파일 형식을 가져옵니다. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | 형식별 위치에서 팔레트를 가져옵니다 |
| [getGlobalAngle()](#getGlobalAngle--) | 전역 각도를 가져오거나 설정합니다. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | 전역 레이어 마스크 정보를 가져옵니다. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | 전역 레이어 리소스를 가져오거나 설정합니다. |
| [getGrayColorProfile()](#getGrayColorProfile--) | 그레이스케일 PSD 이미지에 대한 GRAY(단색) 색상 프로필을 가져오거나 설정합니다. |
| [getHeight()](#getHeight--) | 이미지 높이를 가져옵니다. |
| [getHorizontalResolution()](#getHorizontalResolution--) | 이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | PSD 레이어를 가져오거나 설정합니다. |
| [getImageOpacity()](#getImageOpacity--) | 이 이미지의 불투명도를 가져옵니다. |
| [getImageResources()](#getImageResources--) | PSD 이미지 리소스를 가져오거나 설정합니다. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | 내부 데이터 변환기를 가져옵니다. |
| [getInterruptMonitor()](#getInterruptMonitor--) | 인터럽트 모니터를 가져옵니다. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | 레이어와 마스크를 가져옵니다. |
| [getLayers()](#getLayers--) | PSD 레이어를 가져오거나 설정합니다. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | 연결된 레이어 관리자를 가져옵니다. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | 부분 회전 저장을 위한 허용 최대 할당량을 가져오거나 설정합니다. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | 메모리 관리자를 가져옵니다. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | 리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | 원본 파일 설정을 기반으로 옵션을 가져옵니다. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | 그릴 수 있는 이미지를 가져옵니다. |
| [getPalette()](#getPalette--) | 색상 팔레트를 가져옵니다. |
| [getPixel(int x, int y)](#getPixel-int-int-) | 이미지 픽셀을 가져옵니다. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | 개인 폰트 캐시를 생성합니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러 정보를 가져옵니다. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | 진행 이벤트 핸들러 정보를 가져옵니다. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | 비례 높이를 가져옵니다. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | 비례 너비를 가져옵니다. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | PSD 헤더를 가져오거나 설정합니다. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | 사용자 정의 색상 변환기를 가져오거나 설정합니다 |
| [getRawDataFormat()](#getRawDataFormat--) | 원시 데이터 형식을 가져옵니다. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다 |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | 인덱스 색상 변환기를 가져오거나 설정합니다 |
| [getRawLineSize()](#getRawLineSize--) | 원시 라인 크기를 바이트 단위로 가져옵니다. |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK PSD 이미지에 대한 RGB 색상 프로필을 가져오거나 설정합니다. |
| [getRotateMode()](#getRotateMode--) | 회전 모드를 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 이미지 크기를 가져옵니다. |
| [getSkewAngle()](#getSkewAngle--) | 왜곡 각도를 가져옵니다. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | 스마트 객체 제공자를 가져옵니다. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | 소스 이미지가 존재하는 경우 파일 경로를 가져옵니다. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | 동기화 루트를 가져옵니다. |
| [getTimeline()](#getTimeline--) | 이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 타임라인([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-))을 가져옵니다. |
| [getTransparentColor()](#getTransparentColor--) | 이미지 투명 색상을 가져옵니다. |
| [getUpdateXmpData()](#getUpdateXmpData--) | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | 새로운 리소스 블록이 포함된 업데이트된 리소스를 가져옵니다. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | 객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값을 가져옵니다. |
| [getUseRawData()](#getUseRawData--) | 원시 데이터 로딩이 가능한 경우 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | 사용된 팔레트를 가져옵니다. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 벤처 라이선스를 가져옵니다. |
| [getVersion()](#getVersion--) | 버전을 가져오거나 설정합니다. |
| [getVerticalResolution()](#getVerticalResolution--) | 이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 이미지 너비를 가져옵니다. |
| [getXmpData()](#getXmpData--) | XMP 메타데이터를 가져오거나 설정합니다. |
| [grayscale()](#grayscale--) | 이미지를 회색조 표현으로 변환합니다. |
| [hasAlpha()](#hasAlpha--) | 이  RasterImage의 세로 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| [hasBackgroundColor()](#hasBackgroundColor--) | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져옵니다. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 로드 후 이미지 인스턴스가 변경되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hasTransparencyData()](#hasTransparencyData--) | 레이어 데이터를 지정할 때 첫 번째 알파 채널이 병합 결과에 대한 투명도 데이터를 포함하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hasTransparentColor()](#hasTransparentColor--) | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 진행 최대 값을 가져오거나 설정합니다. |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 진행을 나타냅니다. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | 지정된 레이어 뒤에 모든 준비와 함께 레이어를 삽입합니다. |
| [isCached()](#isCached--) | 이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [isFlatten()](#isFlatten--) | PSD 이미지가 평탄화되었는지 여부를 나타내는 값을 가져옵니다. |
| [isRawDataAvailable()](#isRawDataAvailable--) | 원시 데이터 로딩이 가능한지 여부를 나타내는 값을 가져옵니다. |
| [isUsePalette()](#isUsePalette--) | 이미지 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(String filePath)](#load-java.lang.String-) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | 지정된 파일에서 새 이미지를 로드합니다. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | 32비트 ARGB 픽셀을 로드합니다. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | 64비트 ARGB 픽셀을 로드합니다. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | CMYK 형식의 픽셀을 로드합니다. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | CMYK 형식의 픽셀을 로드합니다. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 32비트 ARGB 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | 픽셀을 패키지 단위로 부분적으로 로드합니다. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | 픽셀을 로드합니다. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 부분 처리 메커니즘을 사용하여 원시 이미지 데이터를 로드합니다. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 원시 데이터를 로드합니다. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | 레이어를 병합합니다. |
| [normalizeAngle()](#normalizeAngle--) | 각도를 정규화합니다. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | 각도를 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | 이 [Image](../../com.aspose.psd/image)의 컨테이너가 설정될 때 호출합니다. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | 지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | 전역 텍스트 엔진 리소스를 제거합니다 - 이 메서드는 처리 후 Adobe Photoshop에서 열 수 없는 일부 텍스트 레이어 PSD 파일에 사용됩니다(주로 폰트가 없는 텍스트 레이어와 관련됨). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | 투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 이미지 크기를 조정합니다. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 이미지 크기를 조정합니다. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 이미지 크기를 조정합니다. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | 높이를 비례적으로 조정합니다. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | 높이를 비례적으로 조정합니다. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 높이를 비례적으로 조정합니다. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | 너비를 비례적으로 조정합니다. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | 너비를 비례적으로 조정합니다. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 너비를 비례적으로 조정합니다. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | 지정된 역배율로 레이어를 크기 조정합니다 |
| [rotate(float angle)](#rotate-float-) | 이미지를 중심을 기준으로 회전합니다. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | 이미지를 중심을 기준으로 회전합니다. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | 이미지 데이터를 기본 스트림에 저장합니다. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| [save(String filePath)](#save-java.lang.String-) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | 32비트 ARGB 픽셀을 저장합니다. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | 픽셀을 저장합니다. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | 픽셀을 저장합니다. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | 픽셀을 저장합니다. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | 원시 데이터를 저장합니다. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | 지정된 저장 옵션과 경계를 사용하여 이미지 데이터를 지정된 스트림에 저장합니다. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | 활성 레이어를 가져오거나 설정합니다. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | 지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 자동 팔레트 조정 여부를 나타내는 값을 설정합니다. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 배경 색상의 값을 가져오거나 설정합니다. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 배경 색상을 가져오거나 설정합니다. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK PSD 이미지에 대한 CMYK 색상 프로필을 가져오거나 설정합니다. |
| [setColorMode(short value)](#setColorMode-short-) | 색상 모드를 가져오거나 설정합니다. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | 이미지 컨테이너를 설정합니다. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | 데이터 로더를 직접 설정합니다. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | 객체의 데이터 스트림을 설정합니다. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | 형식별 위치에 팔레트를 설정합니다. |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | 전역 각도입니다. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | 전역 레이어 리소스를 가져오거나 설정합니다. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | 그레이(흑백) 색상 프로파일은 그레이스케일 PSD 이미지용입니다. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 저장 후 무시 여부를 나타내는 값을 설정합니다. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 로드 후 이미지 인스턴스가 변경되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | PSD 이미지 리소스를 가져오거나 설정합니다. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | 내부 데이터 변환기를 설정합니다. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 인터럽트 모니터를 설정합니다. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | PSD 레이어를 가져오거나 설정합니다. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | 부분 회전 저장을 위한 허용 최대 할당량을 가져오거나 설정합니다. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | 메모리 관리자를 설정합니다. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 색상 팔레트를 설정합니다. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 이미지 팔레트를 설정합니다. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | 지정된 위치에 이미지 픽셀을 설정합니다. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | 사용자 정의 색상 변환기를 가져오거나 설정합니다 |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다 |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | 인덱스 색상 변환기를 가져오거나 설정합니다 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 해상도를 설정합니다. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK PSD 이미지에 대한 RGB 색상 프로필을 가져오거나 설정합니다. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | 회전 모드를 가져오거나 설정합니다. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | 레이어 데이터를 지정할 때 첫 번째 알파 채널이 병합 결과에 대한 투명도 데이터를 포함하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | 이미지 투명 색상을 가져옵니다. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | 원시 데이터 로딩이 가능한 경우 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | 벤처 라이선스를 설정합니다. |
| [setVersion(int value)](#setVersion-int-) | 버전을 가져오거나 설정합니다. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP 메타데이터를 가져오거나 설정합니다. |
| [toBitmap()](#toBitmap--) | 래스터 이미지를 비트맵으로 변환합니다. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | 전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | 전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


지정된 경로에 있는 래스터 이미지(경로에 있는 psd 이미지가 아님)에서 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스를 새 인스턴스로 초기화합니다. 기본 매개변수로 psd 이미지를 초기화하는 데 사용됩니다 - 색상 모드 - rgb, 4 채널, 채널당 8비트, 압축 - Raw.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | java.lang.String | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


지정된 경로의 래스터 이미지(경로에 PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | java.lang.String | 픽셀 및 팔레트 데이터를 로드하고 초기화할 경로입니다. |
| colorMode | short | 색상 모드. |
| channelBitDepth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psdVersion | int | PSD 버전. |
| compression | short | 사용할 압축입니다. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


지정된 스트림에 있는 래스터 이미지(스트림에 있는 psd 이미지가 아님)에서 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스를 새 인스턴스로 초기화합니다. 기본 매개변수로 psd 이미지를 초기화하는 데 사용됩니다 - 색상 모드 - rgb, 4 채널, 채널당 8비트, 압축 - Raw.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


지정된 스트림의 래스터 이미지(스트림에 PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 픽셀 및 팔레트 데이터를 로드하고 초기화할 스트림입니다. |
| colorMode | short | 색상 모드. |
| channelBitDepth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psdVersion | int | PSD 버전. |
| compression | short | 사용할 압축입니다. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


기존 래스터 이미지(PSD 이미지가 아님)에서 RGB 색상 모드, 4채널, 8비트/채널, 압축 없음으로 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


기존 래스터 이미지(PSD 이미지가 아님)에서 생성자 매개변수를 사용하여 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | 픽셀 및 팔레트 데이터를 로드하고 초기화할 이미지입니다. |
| colorMode | short | 색상 모드. |
| channelBitDepth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psdVersion | int | PSD 버전. |
| compression | short | 사용할 압축입니다. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


지정된 너비와 높이로 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스를 새 인스턴스로 초기화합니다. 빈 psd 이미지를 초기화하는 데 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int | 이미지 너비입니다. |
| 높이 | int | 이미지 높이입니다. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


지정된 너비, 높이, paletter, 색상 모드, 채널 수 및 채널 비트 길이와 지정된 압축 모드 매개변수로 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스를 새 인스턴스로 초기화합니다. 빈 psd 이미지를 초기화하는 데 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int | 이미지 너비입니다. |
| 높이 | int | 이미지 높이입니다. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |
| colorMode | short | 색상 모드. |
| channelBitDepth | short | 채널당 PSD 비트 깊이입니다. |
| channels | short | PSD 채널 수입니다. |
| psdVersion | int | PSD 버전. |
| compression | short | 사용할 압축입니다. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


기본 인코딩 이름

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


기본 PSD 버전.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


이미지가 로드될 때 발생합니다.

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


이미지가 createFirstSupportedLoader에 의해 로드될 때 발생합니다.

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


이미지가 로드되거나 저장될 때 발생합니다.

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


크레딧이 사용될 때 발생합니다.

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


레이어에 대한 접근을 동기화하는 데 사용할 수 있는 객체.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


흑백 조정 레이어를 추가합니다.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


밝기/대비 조정 레이어를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 밝기 | int | 밝기입니다. |
| 대비 | int | 대비입니다. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


채널 믹서 조정 레이어를 기본 매개변수와 함께 추가합니다

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


색상 균형 조정 레이어를 추가합니다.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Curves Adjustment 레이어를 추가합니다.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| exposure | float |  |
| 오프셋 | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


노출 조정 레이어를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| exposure | float | 노출입니다. |
| 오프셋 | float | 오프셋. |
| gammaCorrection | float | 감마 보정. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


GradientMap Adjustment 레이어를 추가합니다.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


색조/채도 조정 레이어를 추가합니다.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


반전 조정 레이어를 추가합니다.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


레이어를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 레이어. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


레이어 그룹을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| groupName | java.lang.String | 그룹의 이름. |
| 인덱스 | int | 삽입 후 레이어의 인덱스. |
| startBehaviour | boolean | true 로 설정하면 [start behaviour] 그룹이 시작 시 열려 있는 상태가 되며, 그렇지 않으면 최소화된 상태가 됩니다. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


지정된 인덱스에 레이어를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 레이어. |
| 인덱스 | int | 해당 인덱스. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Levels 조정 레이어를 추가합니다.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


포토필터 레이어를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 색상. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Posterize Adjustment 레이어를 추가합니다.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


새 일반 레이어를 추가합니다.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


선택 색상 조정 레이어를 추가합니다.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


빈 Shape 레이어를 추가합니다. 경로 없이. 저장하기 전에 Shape 레이어에 추가해야 합니다.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


새 Text 레이어를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 레이어의 텍스트. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 레이어의 사각형. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Threshold 조정 레이어를 추가합니다.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Vibrance 조정 레이어를 추가합니다.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


이미지 밝기를 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 밝기 | int | 밝기 값. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


이미지 대비

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 대비 | float | 대비 값 (범위 [-100; 100] 내) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


이미지의 감마 보정.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 감마 | float | 빨강, 초록 및 파랑 채널 계수에 대한 감마 |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


이미지의 감마 보정.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| gammaRed | float | 빨간 채널 계수용 감마 |
| gammaGreen | float | 초록 채널 계수용 감마 |
| gammaBlue | float | 파란 채널 계수용 감마 |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


크기 조정 프로세스를 시작합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 새 이미지 너비. |
| newHeight | int | 새 이미지 높이. |

**Returns:**
com.aspose.internal.IResizeController - 리사이즈 컨트롤러.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brightnessDifference | double | 픽셀과 해당 픽셀을 중심으로 하는 s x s 창의 픽셀 평균 사이의 밝기 차이. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Bradley의 적응형 임계값 알고리즘과 적분 이미지 임계값을 사용하여 이미지를 이진화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brightnessDifference | double | 픽셀과 해당 픽셀을 중심으로 하는 s x s 창의 픽셀 평균 사이의 밝기 차이. |
| windowSize | int | 해당 픽셀을 중심으로 하는 s x s 픽셀 창의 크기 |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


미리 정의된 임계값으로 이미지를 이진화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| threshold | byte | 임계값. 픽셀의 해당 회색 값이 임계값보다 크면 255가 할당되고, 그렇지 않으면 0이 할당됩니다. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Otsu 임계값을 사용하여 이미지를 이진화합니다.

### cacheData() {#cacheData--}
```
public void cacheData()
```


데이터를 캐시하고 기본 DataStreamSupporter.DataStreamContainer에서 추가 데이터 로드가 수행되지 않도록 보장합니다.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


이미지를 지정된 스트림에서 로드할 수 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 로드할 스트림. |

**Returns:**
boolean -  true  지정된 스트림에서 이미지를 로드할 수 있으면 true, 그렇지 않으면 false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


이미지를 지정된 스트림에서 로드할 수 있는지 여부를 결정하고, 선택적으로 지정된 loadOptions를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 로드할 스트림. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
boolean -  true  지정된 스트림에서 이미지를 로드할 수 있으면 true, 그렇지 않으면 false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 파일 경로. |

**Returns:**
boolean - 지정된 파일에서 이미지를 로드할 수 있으면 true, 그렇지 않으면 false.
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


지정된 파일 경로에서 이미지를 로드할 수 있는지, 그리고 선택적으로 지정된 열기 옵션을 사용할 수 있는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 파일 경로. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
boolean - 지정된 파일에서 이미지를 로드할 수 있으면 true, 그렇지 않으면 false.
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


전달된 저장 옵션으로 표시된 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 사용할 저장 옵션. |

**Returns:**
boolean - 전달된 저장 옵션으로 표시된 지정된 파일 형식에 이미지를 저장할 수 있으면 true, 그렇지 않으면 false.
### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


옵션에 지정된 형식으로 이 이미지 형식을 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | 새 옵션. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


aps 형식으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |
| 모드 | int | 모드. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 클리핑 사각형. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - APS 페이지.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


지정된 생성 옵션을 사용하여 새 이미지를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 옵션. |
| 너비 | int | 너비. |
| 높이 | int | 높이. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


지정된 이미지를 페이지로 사용하여 새 이미지를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | 이미지. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


지정된 이미지를 페이지로 하여 새 이미지를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | 이미지. |
| disposeImages | boolean | true 로 설정하면 [dispose images]합니다. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


새 인스턴스를 생성합니다 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | PSD 헤더. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | 색상 데이터. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | 이미지 리소스. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | 레이어 및 마스크 정보. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | 이미지 데이터. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |
| version | int | PSD 버전. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |
| noLayerLoad | boolean | 레이어 로드 안 함 |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 리사이저 | com.aspose.internal.rotaters.PartialRotater |  |
| 픽셀 저장기 | com.aspose.internal.IPixelsSaver |  |
| 너비 | int |  |
| 높이 | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


이미지를 자릅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 그 사각형. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


시프트를 사용하여 이미지를 자릅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 왼쪽 시프트 | int | 그 왼쪽 시프트. |
| 오른쪽 시프트 | int | 그 오른쪽 시프트. |
| 위쪽 시프트 | int | 그 위쪽 시프트. |
| 아래쪽 시프트 | int | 그 아래쪽 시프트. |

### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


현재 이미지에 디더링을 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 디더링 방법 | int | 그 디더링 방법. |
| 비트 수 | int | 그 디더링을 위한 최종 비트 수. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


현재 이미지에 디더링을 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 디더링 방법 | int | 그 디더링 방법. |
| 비트 수 | int | 그 디더링을 위한 최종 비트 수. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 그 디더링을 위한 사용자 정의 팔레트. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


이미지를 자릅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 그 사각형. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


이미지 크기를 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |
| newHeight | int | 그 새로운 높이. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 그 크기 조정 설정. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| 크기 조정 유형 | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateFlipType | int | rotate flip type입니다. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


지정된 사각형을 필터링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 그 사각형. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | 옵션. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


모든 레이어를 평탄화합니다.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


활성 레이어를 가져오거나 설정합니다.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


이미지의 32비트 ARGB 픽셀을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | pixel x 위치입니다. |
| y | int | pixel y 위치입니다. |

**Returns:**
int - 지정된 위치에 대한 32비트 ARGB pixel.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


자동 팔레트 조정 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 자동 팔레트 조정이 활성화되면 true; 그렇지 않으면 false.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


배경 색상의 값을 가져오거나 설정합니다.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


배경 색상을 가져오거나 설정합니다. 투명 객체 아래에서 볼 수 있습니다.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


채널당 비트를 가져옵니다.

값: 채널당 비트 수.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


이미지의 픽셀당 비트 수를 가져옵니다.

Value: 이미지 비트당 픽셀 수.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


이미지 경계를 가져옵니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Returns:**
int - 정의된 최대 허용 크기로, 모든 내부 버퍼에 대한 버퍼 크기 힌트입니다.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


PSD 채널 수를 가져옵니다.

값: PSD 채널 수.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


CMYK PSD 이미지에 대한 CMYK 색상 프로필을 가져오거나 설정합니다. 올바른 색상 변환을 위해 RgbColorProfile과 쌍을 이루어야 합니다.

값: CMYK 색상 프로필.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


색상 모드를 가져오거나 설정합니다.

값: 색상 모드.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


압축 방식을 가져옵니다.

값: 압축.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


이미지 컨테이너를 가져옵니다.

값: 이미지 컨테이너.

이 속성이 null이 아니면 이미지가 다른 이미지 안에 포함되어 있음을 나타냅니다.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


현재 이미지 옵션을 가져옵니다.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


객체의 데이터 스트림을 가져옵니다.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


깊이 조정 팔레트를 가져옵니다.

**Returns:**
boolean - 깊이 조정 팔레트.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


기본 32비트 ARGB 픽셀 배열을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 가져올 사각형. |

**Returns:**
int[] - 기본 픽셀 배열.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


기본 옵션을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | java.lang.Object[] | 인수. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


부분 픽셀 로더를 사용하여 기본 픽셀 배열을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 가져올 사각형. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 부분 픽셀 로더. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


부분 픽셀 로더를 사용하여 기본 원시 데이터 배열을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 가져올 사각형. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 부분 원시 데이터 로더. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 원시 데이터 설정. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


기본 원시 데이터 배열을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 원시 데이터를 가져올 사각형. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 원시 데이터 설정. |

**Returns:**
byte[] - 기본 원시 데이터 배열.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


기본 대체 글꼴을 가져오거나 설정합니다. 대체 글꼴이 설정되면 렌더링에 사용됩니다. 내부 지원을 위해 이 메서드가 필요합니다.

**Returns:**
java.lang.String - 대체 글꼴의 이름
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


파일 형식 값을 가져옵니다

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


파일 형식을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | 스트림. |

--------------------

결정된 파일 형식이 지정된 이미지를 로드할 수 있다는 의미는 아닙니다. 스트림을 로드할 수 있는지 확인하려면 CanLoad 메서드 오버로드 중 하나를 사용하십시오. |

**Returns:**
long - 결정된 파일 형식.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


파일 형식을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 스트림. |

결정된 파일 형식이 지정된 이미지를 로드할 수 있다는 의미는 아닙니다. 스트림을 로드할 수 있는지 확인하려면 CanLoad 메서드 오버로드 중 하나를 사용하십시오. |

**Returns:**
long - 결정된 파일 형식.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


파일 형식을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 파일 경로. |

결정된 파일 형식이 지정된 이미지를 로드할 수 있다는 의미는 아닙니다. 파일을 로드할 수 있는지 확인하려면 CanLoad 메서드 오버로드 중 하나를 사용하십시오. |

**Returns:**
long - 결정된 파일 형식.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


현재 이미지에 맞는 사각형을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 맞는 사각형을 얻기 위한 사각형. |
| 너비 | int | 객체 너비. |
| 높이 | int | 객체 높이. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


현재 이미지에 맞는 사각형을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 맞는 사각형을 얻기 위한 사각형. |
| 픽셀 | int[] | 32비트 ARGB 픽셀. |
| 너비 | int | 객체 너비. |
| 높이 | int | 객체 높이. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


형식별 위치에서 팔레트를 가져옵니다

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


전역 각도를 가져오거나 설정합니다.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


전역 레이어 마스크 정보를 가져옵니다.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


전역 레이어 리소스를 가져오거나 설정합니다.

값: 전역 레이어 리소스.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


그레이스케일 PSD 이미지에 대한 GRAY(단색) 색상 프로필을 가져오거나 설정합니다.

값: GRAY(흑백) 색상 프로필.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


이미지 높이를 가져옵니다.

값: 이미지 높이.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다.

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


PSD 레이어를 가져오거나 설정합니다.

값: PSD 레이어.

--------------------

레이어가 없을 경우 레이어 및 마스크 정보 섹션 내의 기타 관련 정보(레이어 마스크, 리소스 등)가 보존되지 않음을 유의하십시오.

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


이 이미지의 불투명도를 가져옵니다.

**Returns:**
float - 0.0(완전 투명)에서 1.0(완전 불투명) 사이의 불투명도 값.
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


PSD 이미지 리소스를 가져오거나 설정합니다.

값: PSD 이미지 리소스.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


내부 데이터 변환기를 가져옵니다.

값: 내부 데이터 변환기.

**Returns:**
com.aspose.internal.IInnerDataTransformer - 내부 데이터 변환기.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


인터럽트 모니터를 가져옵니다.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


레이어와 마스크를 가져옵니다.

값: 레이어 및 마스크.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


PSD 레이어를 가져오거나 설정합니다.

값: PSD 레이어.

--------------------

레이어가 없을 경우 레이어 및 마스크 정보 섹션 내의 기타 관련 정보(레이어 마스크, 리소스 등)가 보존되지 않음을 유의하십시오.

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


연결된 레이어 관리자를 가져옵니다.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


부분 회전 저장을 위한 허용 최대 할당량을 가져오거나 설정합니다.

**Returns:**
int - 부분 회전 저장을 위한 최대 허용 할당량.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


메모리 관리자를 가져옵니다.

값: 메모리 관리자.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - 메모리 관리자.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


리소스 이미지가 마지막으로 수정된 날짜와 시간을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| useDefault | boolean | true 로 설정하면 FileInfo의 정보를 기본값으로 사용합니다. |

**Returns:**
java.util.Date - 리소스 이미지가 마지막으로 수정된 날짜 및 시간.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


원본 파일 설정을 기반으로 옵션을 가져옵니다. 이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다. 예를 들어, 1비트/픽셀 흑백 PNG 이미지를 로드한 후 DataStreamSupporter.Save(string) 메서드를 사용하여 저장하면 8비트/픽셀 PNG 이미지가 출력됩니다. 이를 방지하고 1비트/픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 얻은 다음 두 번째 매개변수로 Image.Save(string, ImageOptionsBase) 메서드에 전달하십시오.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


그릴 수 있는 이미지를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


색상 팔레트를 가져옵니다. 픽셀이 직접 표시될 때 색상 팔레트는 사용되지 않습니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


이미지 픽셀을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | pixel x 위치입니다. |
| y | int | pixel y 위치입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean -  true  if 이미지 구성 요소를 사전 곱해야 하는 경우; 그렇지 않으면  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


개인 폰트 캐시를 생성합니다.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - 개인 글꼴 캐시입니다.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


진행 이벤트 핸들러 정보를 가져옵니다.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


진행 이벤트 핸들러 정보를 가져옵니다.

값: 진행 이벤트 핸들러 정보.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


비례 높이를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int | 너비. |
| 높이 | int | 높이. |
| newWidth | int | 그 새로운 너비. |

**Returns:**
int - 비례 높이.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


비례 너비를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int | 너비. |
| 높이 | int | 높이. |
| newHeight | int | 그 새로운 높이. |

**Returns:**
int - 비례 너비.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


PSD 헤더를 가져오거나 설정합니다.

값: PSD 헤더.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


사용자 정의 색상 변환기를 가져오거나 설정합니다

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


원시 데이터 형식을 가져옵니다.

값: 원시 데이터 형식.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


현재 원시 데이터 설정을 가져옵니다. 이러한 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다

**Returns:**
int - 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


인덱스 색상 변환기를 가져오거나 설정합니다

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


원시 라인 크기를 바이트 단위로 가져옵니다.

**Returns:**
int - 바이트 단위의 원시 라인 크기.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


CMYK PSD 이미지에 대한 RGB 색상 프로필을 가져오거나 설정합니다. 올바른 색상 변환을 위해 CmykColorProfile과 쌍을 이루어야 합니다.

값: RGB 색상 프로필.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


회전 모드를 가져오거나 설정합니다.

**Returns:**
int - 회전 모드.
### getSize() {#getSize--}
```
public Size getSize()
```


이미지 크기를 가져옵니다.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


기울기 각도를 가져옵니다. 이 메서드는 스캔된 텍스트 문서에 적용되며, 스캔 시 기울기 각도를 결정하는 데 사용됩니다.

**Returns:**
float - 기울기 각도(도).
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


스마트 객체 제공자를 가져옵니다.

값: 스마트 오브젝트 제공자.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


소스 이미지가 존재하는 경우 파일 경로를 가져옵니다. 소스 경로를 찾을 수 없으면 빈 문자열을 반환합니다.

**Returns:**
java.lang.String - 소스 이미지의 파일 경로.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


동기화 루트를 가져옵니다.

값: 동기화 루트.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 타임라인([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-))을 가져옵니다.

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


이미지 투명 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean -  true  if XMP 메타데이터를 업데이트하는 경우; 그렇지 않으면  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


새로운 리소스 블록이 포함된 업데이트된 리소스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | 리소스. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | 기존 리소스에 추가할 리소스. |
| removeDuplicates | boolean | true로 설정하면 동일한 ID를 가진 리소스를 제거합니다. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - 업데이트된 리소스 블록 배열을 반환합니다.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값을 가져옵니다.

값:  true  if 객체가 메모리 최적화 전략을 사용하는 경우; 그렇지 않으면  false .

**Returns:**
boolean - 객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


원시 데이터 로딩이 가능한 경우 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean -  true  if 원시 데이터 로딩이 가능한 경우 원시 데이터 로딩을 사용하는 경우; 그렇지 않으면  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


사용된 팔레트를 가져옵니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


벤처 라이선스를 가져옵니다.

**Returns:**
java.lang.Object - 객체로서의 Teh 벤처 라이선스.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


버전을 가져오거나 설정합니다.

값: 버전.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다.

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


이미지 너비를 가져옵니다.

값: 이미지 너비.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP 메타데이터를 가져오거나 설정합니다.

값: XMP 메타데이터.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


이미지를 회색조 표현으로 변환합니다.

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


이  RasterImage의 세로 해상도(인치당 픽셀)를 가져오거나 설정합니다.

값:  true  이 인스턴스에 알파가 있으면; 그렇지 않으면  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


이미지에 배경색이 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


로드 후 이미지 인스턴스가 변경되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스의 이미지가 변경된 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


레이어 데이터를 지정할 때 첫 번째 알파 채널이 병합 결과에 대한 투명도 데이터를 포함하는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  첫 번째 알파 채널에 레이어 데이터를 지정할 때 병합 결과의 투명도 데이터가 포함되어 있으면 true, 그렇지 않으면 false.

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


진행 최대 값을 가져오거나 설정합니다.

값: 진행 최대값

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


진행을 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


지정된 레이어 뒤에 모든 준비와 함께 레이어를 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 레이어. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 삽입할 레이어. |

### isCached() {#isCached--}
```
public boolean isCached()
```


이미지 데이터가 현재 캐시되어 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  true  이미지 데이터가 캐시되어 있으면; 그렇지 않으면  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


PSD 이미지가 평탄화되었는지 여부를 나타내는 값을 가져옵니다.

값:  true  이 인스턴스가 평탄화된 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


원시 데이터 로딩이 가능한지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  true  이 원시 데이터 로딩이 가능하면; 그렇지 않으면  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


이미지 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다.

값:  true  이미지에서 팔레트를 사용하면; 그렇지 않으면  false .

**Returns:**
boolean - 이미지 팔레트가 사용되는지 여부를 나타내는 값.
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지를 로드할 스트림. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지를 로드할 스트림. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.io.RandomAccessFile | 이미지를 로드할 파일. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.io.RandomAccessFile | 이미지를 로드할 파일. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


지정된 파일에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 이미지를 로드할 파일 경로. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


지정된 파일에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 이미지를 로드할 파일 경로. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


32비트 ARGB 픽셀을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns:**
int[] - 로드된 32비트 ARGB 픽셀 배열.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


64비트 ARGB 픽셀을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns:**
long[] - 로드된 64비트 ARGB 픽셀 배열.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


CMYK 형식의 픽셀을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns:**
int[] - 로드된 CMYK 픽셀을 32비트 정수 값으로 표현.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


CMYK 형식으로 픽셀을 로드합니다. 이 메서드는 사용 중단되었습니다. 보다 효율적인  loadCmyk32Pixels(Rectangle)  메서드를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns:**
com.aspose.psd.CmykColor[] - 로드된 CMYK 픽셀 배열.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


32비트 ARGB 픽셀을 패키지 단위로 부분적으로 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 원하는 사각형. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 32비트 ARGB 픽셀 로더. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


픽셀을 패키지 단위로 부분적으로 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 원하는 사각형. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | 픽셀 로더. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


픽셀을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 로드할 사각형. |

**Returns:**
com.aspose.psd.Color[] - 로드된 픽셀 배열.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


부분 처리 메커니즘을 사용하여 원시 이미지 데이터를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 데이터를 로드할 이미지의 원하는 사각형 영역. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 원시 데이터 설정. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 원시 데이터 로더. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


원시 데이터를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 원시 데이터를 로드할 사각형. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 로드된 데이터에 사용할 원시 데이터 설정. 지정된 형식이 아닌 경우 데이터 변환이 수행됩니다. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 원시 데이터 로더. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 이미지를 로드할 스트림. |
| startPosition | long | 이미지를 로드할 시작 위치. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


지정된 스트림에서 새 이미지를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 이미지를 로드할 스트림. |
| startPosition | long | 이미지를 로드할 시작 위치. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


레이어를 병합합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 하단 레이어. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 상단 레이어. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서에서 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [.getSkewAngle](../../null/\#getSkewAngle) 및 [.rotate(float)](../../null/\#rotate-float-) 메서드를 사용합니다.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


각도를 정규화합니다. 이 메서드는 스캔된 텍스트 문서에서 기울어진 스캔을 제거하는 데 적용됩니다. 이 메서드는 [.getSkewAngle](../../null/\#getSkewAngle) 및 [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) 메서드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resizeProportionally | boolean | true 로 설정하면 회전된 사각형(코너 포인트) 투영에 따라 이미지 크기가 변경됩니다. 그렇지 않은 경우 차원은 그대로 유지되고 내부 이미지 내용만 회전됩니다. |
| backgroundColor | [Color](../../com.aspose.psd/color) | 배경 색상. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


이 [Image](../../com.aspose.psd/image)의 컨테이너가 설정될 때 호출합니다.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scanLineIndex | int | 스캔 라인의 0 기반 인덱스. |

**Returns:**
int[] - 스캔 라인의 32비트 ARGB 색상 값 배열.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


지정된 스캔 라인 인덱스로 전체 스캔 라인을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scanLineIndex | int | 스캔 라인의 0 기반 인덱스. |

**Returns:**
com.aspose.psd.Color[] - 스캔 라인 픽셀 색상 값 배열.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


전역 텍스트 엔진 리소스를 제거합니다 - 이 메서드는 일부 텍스트 레이어가 포함된 PSD 파일에서 사용되며, 처리 후 Adobe Photoshop에서 열 수 없게 됩니다(주로 누락된 폰트 텍스트 레이어와 관련). 이 옵션을 사용한 후에는 Photoshop에서 열린 파일에서 다음을 수행해야 합니다: 메뉴 \"Text\" -> \"Process absent fonts\". 그 작업을 수행하면 모든 텍스트가 다시 나타납니다. 이 작업은 최종 레이아웃에 약간의 변경을 일으킬 수 있습니다.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | 교체될 이전 색상. |
| oldColorDiff | byte | 교체된 색조를 넓게 적용할 수 있도록 허용되는 이전 색상의 차이. |
| newColor | [Color](../../com.aspose.psd/color) | 이전 색상을 교체할 새로운 색상. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


허용된 차이로 한 색상을 다른 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldColorArgb | int | 교체될 이전 색상 ARGB 값입니다. |
| oldColorDiff | byte | 교체된 색조를 넓게 적용할 수 있도록 허용되는 이전 색상의 차이. |
| newColorArgb | int | 이전 색상을 교체할 새로운 색상 ARGB 값입니다. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


모든 비투명 색상을 새로운 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색으로 교체됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | 비투명 색상을 교체할 새로운 색상입니다. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


모든 비투명 색상을 새로운 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색으로 교체됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorArgb | int | 비투명 색상을 교체할 새로운 색상 ARGB 값입니다. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


이미지의 크기를 조정합니다. 기본값인 ResizeType.LeftTopToLeftTop이 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |
| newHeight | int | 그 새로운 높이. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


이미지 크기를 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |
| newHeight | int | 그 새로운 높이. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 그 크기 조정 설정. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


이미지 크기를 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |
| newHeight | int | 그 새로운 높이. |
| 크기 조정 유형 | int | 크기 조정 유형입니다. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


높이를 비례적으로 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newHeight | int | 그 새로운 높이. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


높이를 비례적으로 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newHeight | int | 그 새로운 높이. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 이미지 크기 조정 설정입니다. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


높이를 비례적으로 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newHeight | int | 그 새로운 높이. |
| 크기 조정 유형 | int | 크기 조정 유형입니다. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


너비를 비례적으로 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


너비를 비례적으로 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 이미지 크기 조정 설정입니다. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


너비를 비례적으로 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newWidth | int | 그 새로운 너비. |
| 크기 조정 유형 | int | 크기 조정 유형입니다. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


지정된 역배율로 레이어의 크기를 조정합니다. (새 너비 = 기존 너비 / 배율; 새 높이 = 기존 높이 / 배율)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | double | X 배율입니다. |
| scaleY | double | Y 배율입니다. |
| 크기 조정 유형 | int | 크기 조정 유형입니다. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


이미지를 중심을 기준으로 회전합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도(도)입니다. 양수 값은 시계 방향으로 회전합니다. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


이미지를 중심을 기준으로 회전합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도(도)입니다. 양수 값은 시계 방향으로 회전합니다. |
| resizeProportionally | boolean | true 로 설정하면 회전된 사각형(코너 포인트) 투영에 따라 이미지 크기가 변경됩니다. 그렇지 않은 경우 차원은 그대로 유지되고 내부 이미지 내용만 회전됩니다. |
| backgroundColor | [Color](../../com.aspose.psd/color) | 배경 색상. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


이미지 데이터를 기본 스트림에 저장합니다.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


객체 데이터를 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 객체 데이터를 저장할 스트림입니다. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 이미지 데이터를 저장할 스트림입니다. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 저장 옵션입니다. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 이미지 데이터를 저장할 스트림입니다. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 저장 옵션입니다. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계 사각형입니다. 소스 경계를 사용하려면 빈 사각형을 설정합니다. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


객체 데이터를 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.io.RandomAccessFile | 객체 데이터를 저장할 스트림입니다. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.io.RandomAccessFile | 이미지 데이터를 저장할 파일입니다. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.io.RandomAccessFile | 이미지 데이터를 저장할 파일입니다. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 저장 옵션입니다. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계 사각형입니다. 빈 사각형을 설정하면 소스 경계를 사용합니다. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


객체 데이터를 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 객체의 데이터를 저장할 파일 경로. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


객체 데이터를 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 객체의 데이터를 저장할 파일 경로. |
| 덮어쓰기 | boolean | true 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 파일 경로. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 파일 경로. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계 사각형입니다. 빈 사각형을 설정하면 소스 경계를 사용합니다. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


32비트 ARGB 픽셀을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| 픽셀 | int[] | 32비트 ARGB 픽셀 배열. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


픽셀을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| 픽셀 | int[] | 32비트 정수 값으로 표현된 CMYK 픽셀. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


픽셀을 저장합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 saveCmyk32Pixels(Rectangle, int[]) 메서드를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 픽셀 배열. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


픽셀을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 저장할 사각형. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 픽셀 배열. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


원시 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 원시 데이터. |
| dataOffset | int | 시작 원시 데이터 오프셋. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 원시 데이터 사각형. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 데이터가 포함된 원시 데이터 설정. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


지정된 저장 옵션 및 경계를 사용하여 이미지 데이터를 지정된 스트림에 저장합니다. 선택적으로 지정된 레이어만 내보내어 미리보기 렌더링에 사용할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 이미지 데이터가 저장될 스트림. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 사용할 저장 옵션. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계 사각형. 소스 경계를 사용하려면 Rectangle.Empty 로 설정합니다. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | 내보낼 특정 레이어. null 값은 모든 레이어를 포함하는 기본 동작을 나타냅니다. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 이미지 데이터를 저장할 스트림입니다. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 저장 옵션입니다. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 대상 이미지 경계 사각형입니다. 소스 경계를 사용하려면 빈 사각형을 설정합니다. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


활성 레이어를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


지정된 위치에 이미지 32비트 ARGB 픽셀을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | pixel x 위치입니다. |
| y | int | pixel y 위치입니다. |
| argb32Color | int | 지정된 위치의 32비트 ARGB 픽셀. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


자동 팔레트 조정 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  자동 팔레트를 조정하도록 활성화하면; 그렇지 않으면  false . |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


배경 색상의 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


배경 색상을 가져오거나 설정합니다. 투명 객체 아래에서 볼 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 내부 버퍼 전체에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


CMYK PSD 이미지에 대한 CMYK 색상 프로필을 가져오거나 설정합니다. 올바른 색상 변환을 위해 RgbColorProfile과 쌍을 이루어야 합니다.

값: CMYK 색상 프로필.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


색상 모드를 가져오거나 설정합니다.

값: 색상 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


이미지 컨테이너를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image 컨테이너. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


데이터 로더를 직접 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | 데이터 로더. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


객체의 데이터 스트림을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | 객체의 데이터 스트림. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


형식별 위치에 팔레트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 새 32비트 ARGB 팔레트. |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


전역 각도입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


전역 레이어 리소스를 가져오거나 설정합니다.

값: 전역 레이어 리소스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


그레이(흑백) 색상 프로파일은 그레이스케일 PSD 이미지용입니다.

값: GRAY(흑백) 색상 프로필.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수평 해상도(인치당 픽셀)를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


저장 후 무시 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  인 경우 [ignore after save]; 그렇지 않으면,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


로드 후 이미지 인스턴스가 변경되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  인 경우 이 인스턴스가 이미지가 변경되었습니다; 그렇지 않으면,  false . |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


PSD 이미지 리소스를 가져오거나 설정합니다.

값: PSD 이미지 리소스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


내부 데이터 변환기를 설정합니다.

값: 내부 데이터 변환기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.IInnerDataTransformer | 내부 데이터 변환기. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


인터럽트 모니터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | 인터럽트 모니터. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


PSD 레이어를 가져오거나 설정합니다.

값: PSD 레이어.

--------------------

레이어가 없을 경우 레이어 및 마스크 정보 섹션 내의 기타 관련 정보(레이어 마스크, 리소스 등)가 보존되지 않음을 유의하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


부분 회전 저장을 위한 허용 최대 할당량을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 부분 회전 저장에 허용되는 최대 할당량. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


메모리 관리자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | 메모리 관리자. |
| needDispose | boolean | 설정된 경우  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


색상 팔레트를 설정합니다. 픽셀이 직접 표현될 때 색상 팔레트는 사용되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


이미지 팔레트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 설정할 팔레트. |
| updateColors | boolean | 설정된 경우  true  색상이 새 팔레트에 따라 업데이트됩니다; 그렇지 않으면 색인은 변경되지 않은 상태로 유지됩니다. 변경되지 않은 색인은 일부 색인에 해당하는 팔레트 항목이 없을 경우 이미지 로드 시 충돌할 수 있습니다. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


지정된 위치에 이미지 픽셀을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | pixel x 위치입니다. |
| y | int | pixel y 위치입니다. |
| color | [Color](../../com.aspose.psd/color) | 지정된 위치의 픽셀 색상. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


이미지 구성 요소가 사전 곱셈되어야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  인 경우 이미지 구성 요소가 사전 곱셈되어야 합니다; 그렇지 않으면,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


사용자 정의 색상 변환기를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | 사용자 정의 색상 변환기 |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 팔레트 인덱스가 범위를 벗어났을 때 사용할 대체 인덱스 |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


인덱스 색상 변환기를 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | 인덱스 색상 변환기 |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 해상도를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dpiX | double | RasterImage의 수평 해상도(인치당 도트 수)입니다. |
| dpiY | double | RasterImage의 수직 해상도(인치당 도트 수)입니다. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


CMYK PSD 이미지에 대한 RGB 색상 프로필을 가져오거나 설정합니다. 올바른 색상 변환을 위해 CmykColorProfile과 쌍을 이루어야 합니다.

값: RGB 색상 프로필.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


회전 모드를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 회전 모드입니다. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


레이어 데이터를 지정할 때 첫 번째 알파 채널이 병합 결과에 대한 투명도 데이터를 포함하는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  첫 번째 알파 채널에 레이어 데이터를 지정할 때 병합 결과의 투명도 데이터가 포함되어 있으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


이미지에 투명 색상이 있는지 여부를 나타내는 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


이미지 투명 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


XMP 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  XMP 메타데이터를 업데이트하는 경우; 그렇지 않으면  false . |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


원시 데이터 로딩이 가능한 경우 원시 데이터 로딩을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  원시 데이터 로딩이 가능한 경우 원시 데이터 로딩을 사용하는 경우; 그렇지 않으면  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


벤처 라이선스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ventureLicense | java.lang.Object | 벤처 라이선스. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


버전을 가져오거나 설정합니다.

값: 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


이 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)의 수직 해상도(인치당 픽셀)를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP 메타데이터를 가져오거나 설정합니다.

값: XMP 메타데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


래스터 이미지를 비트맵으로 변환합니다.

**Returns:**
java.awt.image.BufferedImage - 비트맵
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scanLineIndex | int | 스캔 라인의 0 기반 인덱스. |
| argb32Pixels | int[] | 쓰기 위한 32비트 ARGB 색상 배열입니다. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


전체 스캔 라인을 지정된 스캔 라인 인덱스로 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scanLineIndex | int | 스캔 라인의 0 기반 인덱스. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 쓰기 위한 픽셀 색상 배열입니다. |

