---
title: "AiImage"
second_title: "Java용 Aspose.PSD API 참조"
description: "Adobe Illustrator AI 이미지"
type: docs
weight: 14
url: /ko/java/com.aspose.psd.fileformats.ai/aiimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)
```
public final class AiImage extends Image
```

Adobe Illustrator (AI) 이미지
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AiImage()](#AiImage--) | [AiImage](../../com.aspose.psd.fileformats.ai/aiimage) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | 이미지가 로드될 때 발생합니다. |
| [OnLoad_internalized](#OnLoad-internalized) | 이미지가 createFirstSupportedLoader에 의해 로드될 때 발생합니다. |
| [OnSave_internalized](#OnSave-internalized) | 이미지가 로드되거나 저장될 때 발생합니다. |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | 크레딧이 사용될 때 발생합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addLayer(AiLayerSection layer)](#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-) | AI 레이어 섹션을 추가합니다. |
| [cacheData()](#cacheData--) | 데이터를 캐시하고 기본 P:Aspose.PSD.DataStreamSupporter.DataStreamContainer 에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 이미지를 지정된 스트림에서 로드할 수 있는지 여부를 결정합니다. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 이미지를 지정된 스트림에서 로드할 수 있는지 여부를 결정하고, 선택적으로 지정된 loadOptions를 사용합니다. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 지정된 파일 경로에서 이미지를 로드할 수 있는지, 그리고 선택적으로 지정된 열기 옵션을 사용할 수 있는지 확인합니다. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 전달된 저장 옵션으로 표시된 지정된 파일 형식에 이미지를 저장할 수 있는지 확인합니다. |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps 형식으로 변환합니다. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 지정된 이미지를 페이지로 사용하여 새 이미지를 생성합니다. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 지정된 이미지를 페이지로 하여 새 이미지를 생성합니다. |
| [create_internalized(AiContentSource contentSource)](#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-) |  |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActivePageIndex()](#getActivePageIndex--) | 활성 페이지의 인덱스를 가져오거나 설정합니다. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 자동 팔레트 조정 여부를 나타내는 값을 가져옵니다. |
| [getBackgroundColor()](#getBackgroundColor--) | 배경 색상의 값을 가져오거나 설정합니다. |
| [getBitsPerPixel()](#getBitsPerPixel--) | 이미지의 픽셀당 비트 수를 가져옵니다. |
| [getBounds()](#getBounds--) | 이미지 경계를 가져옵니다. |
| [getBufferSizeHint()](#getBufferSizeHint--) | 내부 버퍼 전체에 허용되는 최대 크기로 정의된 버퍼 크기 힌트를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | 이미지 컨테이너를 가져옵니다. |
| [getDataSection()](#getDataSection--) | 데이터 섹션을 가져옵니다. |
| [getDataStreamContainer()](#getDataStreamContainer--) | 객체의 데이터 스트림을 가져옵니다. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 깊이 조정 팔레트를 가져옵니다. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 기본 옵션을 가져옵니다. |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getFileFormat()](#getFileFormat--) | 파일 형식 값을 가져옵니다. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | 파일 형식을 가져옵니다. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | 파일 형식을 가져옵니다. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | 파일 형식을 가져옵니다. |
| [getFinalizeSection()](#getFinalizeSection--) | 마무리 섹션을 가져옵니다. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| [getHeader()](#getHeader--) | 헤더를 가져옵니다. |
| [getHeight()](#getHeight--) | 이미지 높이를 가져옵니다. |
| [getInterruptMonitor()](#getInterruptMonitor--) | 인터럽트 모니터를 가져옵니다. |
| [getLayers()](#getLayers--) | 레이어 섹션을 가져옵니다. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | 메모리 관리자를 가져옵니다. |
| [getOriginalOptions()](#getOriginalOptions--) | 원본 파일 설정을 기반으로 옵션을 가져옵니다. |
| [getPageCount()](#getPageCount--) | 페이지 수. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | 그릴 수 있는 이미지를 가져옵니다. |
| [getPalette()](#getPalette--) | 색상 팔레트를 가져옵니다. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | 개인 폰트 캐시를 생성합니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러 정보를 가져옵니다. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | 진행 이벤트 핸들러 정보를 가져옵니다. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | 비례 높이를 가져옵니다. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | 비례 너비를 가져옵니다. |
| [getSetupSection()](#getSetupSection--) | 설정 섹션을 가져옵니다. |
| [getSize()](#getSize--) | 이미지 크기를 가져옵니다. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | 소스 이미지가 존재하는 경우 파일 경로를 가져옵니다. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | 객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값을 가져옵니다. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 벤처 라이선스를 가져옵니다. |
| [getVersion()](#getVersion--) | Adobe Illustrator 형식의 버전을 가져옵니다. |
| [getWidth()](#getWidth--) | 이미지 너비를 가져옵니다. |
| [getXmpData()](#getXmpData--) | XMP 메타데이터를 가져옵니다. |
| [hasBackgroundColor()](#hasBackgroundColor--) | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져옵니다. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 로드 후 이미지 인스턴스가 변경되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 진행 최대 값을 가져오거나 설정합니다. |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 진행을 나타냅니다. |
| [isCached()](#isCached--) | 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값을 가져옵니다. |
| [isUsePalette()](#isUsePalette--) | 이미지 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다. |
| [load(InputStream stream)](#load-java.io.InputStream-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load(String filePath)](#load-java.lang.String-) | 지정된 파일에서 새 이미지를 로드합니다. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | 지정된 파일에서 새 이미지를 로드합니다. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | 지정된 스트림에서 새 이미지를 로드합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | 이 [Image](../../com.aspose.psd/image)의 컨테이너가 설정될 때 호출합니다. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 이미지 크기를 조정합니다. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 이미지 크기를 조정합니다. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 이미지 크기를 조정합니다. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | 높이를 비례적으로 조정합니다. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | 높이를 비례적으로 조정합니다. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 높이를 비례적으로 조정합니다. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | 너비를 비례적으로 조정합니다. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | 너비를 비례적으로 조정합니다. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 너비를 비례적으로 조정합니다. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setActivePageIndex(int value)](#setActivePageIndex-int-) | 활성 페이지의 인덱스를 가져오거나 설정합니다. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 자동 팔레트 조정 여부를 나타내는 값을 설정합니다. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 배경 색상의 값을 가져오거나 설정합니다. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 설정합니다. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | 이미지 컨테이너를 설정합니다. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | 객체의 데이터 스트림을 설정합니다. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 저장 후 무시 여부를 나타내는 값을 설정합니다. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 로드 후 이미지 인스턴스가 변경되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 인터럽트 모니터를 설정합니다. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | 메모리 관리자를 설정합니다. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 색상 팔레트를 설정합니다. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 이미지 팔레트를 설정합니다. |
| [setRenderedImage_internalized(RasterImage value)](#setRenderedImage-internalized-com.aspose.psd.RasterImage-) | 렌더링된 이미지를 가져옵니다. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | 모든 Aspose 제품은 이 메서드를 구현해야 합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AiImage() {#AiImage--}
```
public AiImage()
```


[AiImage](../../com.aspose.psd.fileformats.ai/aiimage) 클래스의 새 인스턴스를 초기화합니다.

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

### addLayer(AiLayerSection layer) {#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-}
```
public final void addLayer(AiLayerSection layer)
```


AI 레이어 섹션을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layer | [AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection) | AI 레이어 섹션. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


데이터를 캐시하고 기본 P:Aspose.PSD.DataStreamSupporter.DataStreamContainer 에서 추가 데이터 로드가 수행되지 않도록 보장합니다.

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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


aps 형식으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 옵션. |
| 모드 | int | 모드. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 클리핑 사각형. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - ApsPage 인스턴스.
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
### create_internalized(AiContentSource contentSource) {#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-}
```
public static AiImage create_internalized(AiContentSource contentSource)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contentSource | com.aspose.internal.fileformats.ai.AiContentSource |  |

**Returns:**
[AiImage](../../com.aspose.psd.fileformats.ai/aiimage)
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getActivePageIndex() {#getActivePageIndex--}
```
public final int getActivePageIndex()
```


활성 페이지의 인덱스를 가져오거나 설정합니다.

값: 이 속성은 PDF 형식 AI 이미지에만 적용됩니다. 이미지가 PDF 형식이 아니거나 페이지가 없으면 이 속성은 -1이 됩니다. 이 속성은 렌더링의 기준이 될 AI 이미지의 페이지를 나타냅니다.

**Returns:**
int
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


이미지 컨테이너를 가져옵니다.

값: 이미지 컨테이너.

이 속성이 null이 아니면 이미지가 다른 이미지 안에 포함되어 있음을 나타냅니다.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataSection() {#getDataSection--}
```
public final AiDataSection getDataSection()
```


데이터 섹션을 가져옵니다.

값: 데이터 섹션.

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
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


파일 형식 값을 가져옵니다.

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
### getFinalizeSection() {#getFinalizeSection--}
```
public final AiFinalizeSection getFinalizeSection()
```


마무리 섹션을 가져옵니다.

값: 마무리 섹션.

**Returns:**
[AiFinalizeSection](../../com.aspose.psd.fileformats.ai/aifinalizesection)
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
### getHeader() {#getHeader--}
```
public final AiHeader getHeader()
```


헤더를 가져옵니다.

값: 헤더.

**Returns:**
[AiHeader](../../com.aspose.psd.fileformats.ai/aiheader)
### getHeight() {#getHeight--}
```
public int getHeight()
```


이미지 높이를 가져옵니다.

값: 이미지 높이.

**Returns:**
int
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


인터럽트 모니터를 가져옵니다.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayers() {#getLayers--}
```
public final AiLayerSection[] getLayers()
```


레이어 섹션을 가져옵니다.

값: 레이어 섹션.

**Returns:**
com.aspose.psd.fileformats.ai.AiLayerSection[]
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


메모리 관리자를 가져옵니다.

값: 메모리 관리자.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - 메모리 관리자.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


원본 파일 설정을 기반으로 옵션을 가져옵니다. 이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다. 예를 들어, 1비트/픽셀 흑백 PNG 이미지를 로드한 후 DataStreamSupporter.Save(string) 메서드를 사용하여 저장하면 8비트/픽셀 PNG 이미지가 출력됩니다. 이를 방지하고 1비트/픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 얻은 다음 두 번째 매개변수로 Image.Save(string, ImageOptionsBase) 메서드에 전달하십시오.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


페이지 수. 오래된 AI 형식 이미지의 경우 항상 0입니다.

값: 페이지 수.

**Returns:**
int
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
### getSetupSection() {#getSetupSection--}
```
public final AiSetupSection getSetupSection()
```


설정 섹션을 가져옵니다.

값: 설정 섹션.

**Returns:**
[AiSetupSection](../../com.aspose.psd.fileformats.ai/aisetupsection)
### getSize() {#getSize--}
```
public Size getSize()
```


이미지 크기를 가져옵니다.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


소스 이미지가 존재하는 경우 파일 경로를 가져옵니다. 소스 경로를 찾을 수 없으면 빈 문자열을 반환합니다.

**Returns:**
java.lang.String - 소스 이미지의 파일 경로.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값을 가져옵니다.

값:  true  if 객체가 메모리 최적화 전략을 사용하는 경우; 그렇지 않으면  false .

**Returns:**
boolean - 객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값
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


Adobe Illustrator 형식의 버전을 가져옵니다.

값: 버전.

**Returns:**
int
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
public final XmpPacketWrapper getXmpData()
```


XMP 메타데이터를 가져옵니다.

값: XMP 데이터.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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

**Returns:**
boolean -  true  이 인스턴스의 이미지가 변경되었으면; 그렇지 않으면  false .
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

### isCached() {#isCached--}
```
public boolean isCached()
```


객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값을 가져옵니다.

값: 객체의 데이터가 캐시된 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


이미지 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다.

값:  true  이미지에서 팔레트를 사용하면; 그렇지 않으면  false .

**Returns:**
boolean - 이미지 팔레트가 사용되는지 여부를 나타내는 값.
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateFlipType | int | 회전 뒤집기의 유형. |

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




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setActivePageIndex(int value) {#setActivePageIndex-int-}
```
public final void setActivePageIndex(int value)
```


활성 페이지의 인덱스를 가져오거나 설정합니다.

값: 이 속성은 PDF 형식 AI 이미지에만 적용됩니다. 이미지가 PDF 형식이 아니거나 페이지가 없으면 이 속성은 -1이 됩니다. 이 속성은 렌더링의 기준이 될 AI 이미지의 페이지를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


이미지 컨테이너를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image 컨테이너. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


객체의 데이터 스트림을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | 객체의 데이터 스트림. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


인터럽트 모니터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | 인터럽트 모니터. |

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

### setRenderedImage_internalized(RasterImage value) {#setRenderedImage-internalized-com.aspose.psd.RasterImage-}
```
public final void setRenderedImage_internalized(RasterImage value)
```


렌더링된 이미지를 가져옵니다.

값: 렌더링된 이미지.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


모든 Aspose 제품은 이 메서드를 구현해야 합니다. 이 메서드는 GroupDocs 제품에 의해 호출되어 GroupDocs 자체가 라이선스가 있는지 여부를 표시하고 사용자 지정 워터마크를 지정합니다. GroupDocs가 라이선스가 있는 경우, Aspose 제품이 라이선스가 없더라도 이 문서 인스턴스는 라이선스가 있는 것처럼 동작해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Venture 라이선스 객체. |

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

