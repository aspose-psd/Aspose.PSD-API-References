---
title: "Aspose.PSD"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "이 네임스페이스는 중첩 네임스페이스의 핵심이며 Aspose.PSD 처리에 사용되는 가장 기본적인 객체들입니다."
type: docs
weight: 10
url: /ko/net/aspose.psd/
---
{{< psd/tize >}}
네임스페이스는 중첩 네임스페이스의 핵심이며 Aspose.PSD 처리에 사용되는 가장 기본적인 객체입니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AggregateException](./aggregateexception/) | 여러 예외를 집계합니다. |
| [Blend](./blend/) | 블렌드 패턴을 정의합니다. 이 클래스는 상속될 수 없습니다. |
| [Brush](./brush/) | 기본 브러시 클래스입니다. |
| [BuildVersionInfo](./buildversioninfo/) | 현재 빌드 버전 정보를 포함합니다. |
| [Cache](./cache/) | 캐시 설정을 포함합니다. |
| [CmykColorHelper](./cmykcolorhelper/) | CMYK 색상을 부호 있는 32비트 정수 값으로 다루는 도우미 메서드입니다. [`CmykColor`](../aspose.psd/cmykcolor/) 구조체와 유사한 API를 제공합니다. CMYK 색상이 내부 필드가 있는 구조체가 아니라 Int32로만 표현되기 때문에 더 가볍습니다. 가능한 경우 폐기된 [`CmykColor`](../aspose.psd/cmykcolor/) 구조체 대신 이 클래스의 정적 메서드를 사용하는 것이 좋습니다. |
| [ColorBlend](./colorblend/) | 다중 색상 그라디언트에서 색상 블렌딩을 보간하는 데 사용되는 색상 및 위치 배열을 정의합니다. 이 클래스는 상속될 수 없습니다. |
| [ColorMap](./colormap/) | 색상 변환을 위한 맵을 정의합니다. [`ImageAttributes`](../aspose.psd/imageattributes/) 클래스의 여러 메서드는 색상 재매핑 테이블(이것은 [`ColorMap`](../aspose.psd/colormap/) 구조체 배열)을 사용하여 이미지 색상을 조정합니다. 상속할 수 없습니다. |
| [ColorMatrix](./colormatrix/) | RGBA 공간의 좌표를 포함하는 5x5 행렬을 정의합니다. [`ImageAttributes`](../aspose.psd/imageattributes/) 클래스의 여러 메서드는 색상 행렬을 사용하여 이미지 색상을 조정합니다. 이 클래스는 상속될 수 없습니다. |
| [ColorPalette](./colorpalette/) | 색상 팔레트를 구성하는 색상 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속할 수 없습니다. |
| [ColorPaletteHelper](./colorpalettehelper/) | 색상 팔레트 조작을 위한 도우미 클래스입니다. |
| [ColorTranslator](./colortranslator/) | 색상을 GDI+ Color 구조체와 상호 변환합니다. 이 클래스는 상속될 수 없습니다. |
| [CompositeException](./compositeexception/) | 복합 예외 |
| [CustomLineCap](./customlinecap/) | 사용자 정의 라인 캡을 캡슐화합니다. |
| [DataStreamSupporter](./datastreamsupporter/) | 데이터 스트림 컨테이너. |
| [DisposableObject](./disposableobject/) | Disposable 객체를 나타냅니다. |
| [Figure](./figure/) | 도형. 도형을 위한 컨테이너. |
| [FileStreamContainer](./filestreamcontainer/) | 파일 스트림 처리를 위한 도우미. |
| [Font](./font/) | 텍스트에 대한 특정 형식을 정의합니다. 여기에는 글꼴, 크기 및 스타일 속성이 포함됩니다. 이 클래스는 상속될 수 없습니다. |
| [FontSettings](./fontsettings/) | 일반 PSD 벡터 형식 렌더러 글꼴 설정. |
| [Graphics](./graphics/) | 현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다. |
| [GraphicsPath](./graphicspath/) | 연결된 선과 곡선의 시리즈를 나타냅니다. 이 클래스는 상속될 수 없습니다. |
| [Image](./image/) | 이미지는 모든 종류의 이미지에 대한 기본 클래스입니다. |
| [ImageAttributes](./imageattributes/) | [`ImageAttributes`](../aspose.psd/imageattributes/) 객체는 렌더링 중 비트맵 및 메타파일 색상이 어떻게 조작되는지에 대한 정보를 포함합니다. [`ImageAttributes`](../aspose.psd/imageattributes/) 객체는 색상 보정 행렬, 그레이스케일 보정 행렬, 감마 보정 값, 색상 매핑 테이블 및 색상 임계값을 포함한 여러 색상 보정 설정을 유지합니다. 렌더링 중에 색상을 보정, 어둡게, 밝게, 제거할 수 있습니다. 이러한 조작을 적용하려면 [`ImageAttributes`](../aspose.psd/imageattributes/) 객체를 초기화하고 해당 [`ImageAttributes`](../aspose.psd/imageattributes/) 객체의 경로(및 [`Image`](../aspose.psd/image/) 객체의 경로)를 DrawImage 메서드에 전달합니다. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | 이미지 생성기 레지스트리를 나타냅니다. |
| [ImageExportersRegistry](./imageexportersregistry/) | 이미지 내보내기 레지스트리를 나타냅니다. |
| [ImageLoadersRegistry](./imageloadersregistry/) | 이미지 로더 레지스트리를 나타냅니다. |
| [ImageOptionsBase](./imageoptionsbase/) | 이미지 기본 옵션. |
| [ImageResizeSettings](./imageresizesettings/) | 이미지 크기 조정 설정 클래스 |
| [IntRange](./intrange/) | 요소 시퀀스를 나타내는 클래스 |
| [License](./license/) | 구성 요소에 라이선스를 부여하는 메서드를 제공합니다. |
| [LoadOptions](./loadoptions/) | 로드 옵션을 나타냅니다. |
| [Matrix](./matrix/) | GDI+ 매트릭스를 대체합니다. |
| [Metered](./metered/) | 계량 키를 설정하는 메서드를 제공합니다. |
| [NonGenericDictionary](./nongenericdictionary/) | 비제네릭 사전을 나타냅니다. |
| [NonGenericList](./nongenericlist/) | 비제네릭 객체 리스트 |
| [ObjectWithBounds](./objectwithbounds/) | 경계가 있는 객체. |
| [OpenTypeFontsCache](./opentypefontscache/) | 시스템에 설치된 OpenType 글꼴에 대한 캐시. |
| [Pen](./pen/) | 선, 곡선 및 도형을 그리는 데 사용되는 객체를 정의합니다. |
| [PixelDataFormat](./pixeldataformat/) | 픽셀 데이터 형식입니다. 이는 불변 객체입니다. |
| [PixelsData](./pixelsdata/) | 이미지 픽셀 데이터와 그 경계를 저장하는 클래스입니다. |
| [PluginLicenseException](./pluginlicenseexception/) | 플러그인 라이선스에 대한 예외 |
| [ProgressEventHandler](./progresseventhandler/) | 진행 이벤트 핸들러 함수 참조 |
| [RasterCachedImage](./rastercachedimage/) | 래스터 그래픽 작업을 지원하는 래스터 이미지를 나타냅니다. 필요할 때 이 이미지가 픽셀 데이터를 캐시합니다. |
| [RasterImage](./rasterimage/) | 래스터 그래픽 작업을 지원하는 래스터 이미지를 나타냅니다. |
| [RawDataSettings](./rawdatasettings/) | 원시 데이터 설정 |
| [Region](./region/) | 사각형 및 경로로 구성된 그래픽 도형의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다. |
| [ResolutionSetting](./resolutionsetting/) | 이미지 저장 옵션에 대한 해상도 설정입니다. |
| [Shape](./shape/) | 도형입니다. 특정 규칙을 사용해 연결된 연속적인 점들의 집합입니다. |
| [ShapeSegment](./shapesegment/) | 도형 세그먼트를 나타냅니다. 세그먼트는 두 점을 연결하는 선 또는 곡선입니다. |
| [Source](./source/) | 소스는 객체 파이프에 대한 모든 관련 정보를 포함하는 데 사용됩니다. |
| [SplitStreamContainer](./splitstreamcontainer/) | 스트림을 포함하고 스트림 처리 루틴을 제공하는 분할 스트림 컨테이너를 나타냅니다. |
| [StreamContainer](./streamcontainer/) | 스트림을 포함하고 스트림 처리 루틴을 제공하는 스트림 컨테이너를 나타냅니다. |
| [StringFormat](./stringformat/) | 텍스트 레이아웃 정보(정렬, 방향 및 탭 정지와 같은)와 표시 조작(생략 부호 삽입 및 국가별 숫자 대체와 같은) 및 OpenType 기능을 캡슐화합니다. 이 클래스는 상속될 수 없습니다. |
| [TransparencySupporter](./transparencysupporter/) | 투명을 지원하는 객체입니다. |
| [VectorImage](./vectorimage/) | 벡터 이미지는 모든 유형의 벡터 이미지에 대한 기본 클래스입니다. |
## Structures

| 구조 | 설명 |
| --- | --- |
| [CmykColor](./cmykcolor/) | 픽셀의 CMYK 색상입니다. |
| [Color](./color/) | 픽셀의 색상입니다. |
| [Point](./point/) | 2차원 평면에서 점을 정의하는 정수 x 및 y 좌표의 순서쌍을 나타냅니다. |
| [PointF](./pointf/) | 2차원 평면에서 점을 정의하는 부동소수점 x 및 y 좌표의 순서쌍을 나타냅니다. |
| [Rectangle](./rectangle/) | 사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다. |
| [RectangleF](./rectanglef/) | 사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자 집합을 저장합니다. |
| [Size](./size/) | 크기를 나타냅니다. |
| [SizeF](./sizef/) | 보통 사각형의 너비와 높이를 나타내는 부동 소수점 숫자 쌍을 저장합니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | 고급 버퍼 프로세서입니다. |
| [IBufferProcessor](./ibufferprocessor/) | 버퍼 프로세서입니다. |
| [IColorConverter](./icolorconverter/) | 색상 변환기입니다. |
| [IColorPalette](./icolorpalette/) | 색상 팔레트 인터페이스입니다. |
| [IImageCreator](./iimagecreator/) | 이미지 생성기입니다. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | 생성기 속성을 지정하는 이미지 생성기 설명자입니다. 생성기 설명자는 각 이미지 생성기 인스턴스를 메모리에 보관하고 멀티스레딩 문제를 피하기 위해 사용됩니다. |
| [IImageDescriptor](./iimagedescriptor/) | 이미지 설명자입니다. 다른 모든 이미지 설명자 유형에 대한 기본 속성과 메서드를 포함합니다. |
| [IImageExporter](./iimageexporter/) | 이미지 내보내기 도구입니다. 내부 Aspose.PSD 형식의 데이터를 지정된 데이터 형식으로 내보낼 수 있습니다. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | 이미지 내보내기 설명자를 나타냅니다. 내보내기 설명자는 각 내보내기 인스턴스를 메모리에 보관하고 멀티스레딩 문제를 피하기 위해 사용됩니다. |
| [IImageLoader](./iimageloader/) | 이미지 로더입니다. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | 로드 속성을 지정하는 이미지 로더 설명자입니다. 로더 설명자는 각 이미지 로더 인스턴스를 메모리에 보관하고 멀티스레딩 문제를 피하기 위해 사용됩니다. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | 인덱스 이미지 형식을 위한 색상 변환기입니다. |
| [IKeyedObject](./ikeyedobject/) | 키를 가진 객체에 대한 인터페이스를 나타냅니다. |
| [IObjectWithBounds](./iobjectwithbounds/) | 경계가 있는 객체를 나타냅니다. |
| [IOrderedShape](./iorderedshape/) | 정렬된 형태를 나타냅니다. 정렬된 형태는 시작점과 끝점을 갖는 연속적인 점들의 집합입니다. 특정 규칙을 사용하여 연결된 연속적인 점들의 집합입니다. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | 32비트 ARGB 픽셀이 부분적으로 로드되는 것에 부합합니다. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | 64비트 ARGB 픽셀 로더입니다. |
| [IPartialPixelLoader](./ipartialpixelloader/) | 픽셀이 부분적으로 로드되는 것에 부합합니다. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | 부분 데이터 로더입니다. |
| [IPsdColorPalette](./ipsdcolorpalette/) | pasd 색상 팔레트 |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | 래스터 이미지 32비트 ARGB 픽셀 로더입니다. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | 래스터 이미지 픽셀 로더입니다. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | 래스터 이미지 원시 데이터 로더. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [CacheType](./cachetype/) | 사용할 캐시 유형을 지정합니다. |
| [CharacterSet](./characterset/) | 사용되는 문자 집합을 나타냅니다. |
| [ColorAdjustType](./coloradjusttype/) | 어떤 객체가 색상 조정 정보를 사용하는지 지정합니다. |
| [ColorChannelFlag](./colorchannelflag/) | CMYK (cyan, magenta, yellow, black) 색 공간에서 개별 채널을 지정합니다. 이 열거형은 SetOutputChannel 메서드에서 사용됩니다. |
| [ColorCompareMethod](./colorcomparemethod/) | 가장 가까운 이웃에 맞추기 위한 색상 비교 방법 |
| [ColorMatrixFlag](./colormatrixflag/) | 색상 및 그레이스케일 조정 설정에 의해 영향을 받는 이미지 및 색상의 유형을 지정합니다. [`ImageAttributes`](../aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](./colorquantizationmethod/) | 색상 양자화 방법 |
| [CompositingQuality](./compositingquality/) | 합성 중에 사용할 품질 수준을 지정합니다. |
| [DashCap](./dashcap/) | 점선의 각 대시 양쪽 끝에 사용할 그래픽 모양 유형을 지정합니다. |
| [DashStyle](./dashstyle/) | [`Pen`](../aspose.psd/pen/) 객체로 그린 점선의 스타일을 지정합니다. |
| [DataRecoveryMode](./datarecoverymode/) | 데이터 복구 모드입니다. |
| [DitheringMethod](./ditheringmethod/) | 디더링 방법. |
| [DitheringMethods](./ditheringmethods/) | 색상 변환을 제어하는 데 사용되는 디더링 방법입니다. |
| [FileFormat](./fileformat/) | 지원되는 PSD 파일 형식 중 하나입니다. |
| [FillMode](./fillmode/) | 닫힌 경로 내부가 어떻게 채워지는지 지정합니다. |
| [FontStyle](./fontstyle/) | 텍스트에 적용되는 스타일 정보를 지정합니다. |
| [GraphicsUnit](./graphicsunit/) | 주어진 데이터의 측정 단위를 지정합니다. |
| [HatchStyle](./hatchstyle/) | [`HatchBrush`](../aspose.psd.brushes/hatchbrush/) 객체에 사용할 수 있는 다양한 패턴을 지정합니다. |
| [HotkeyPrefix](./hotkeyprefix/) | 텍스트와 관련된 단축키 접두사의 표시 유형을 지정합니다. |
| [ImageFilterType](./imagefiltertype/) | 사용할 이미지 필터 |
| [InterpolationMode](./interpolationmode/) | [`InterpolationMode`](../aspose.psd/interpolationmode/) 열거형은 이미지가 확대/축소되거나 회전될 때 사용되는 알고리즘을 지정합니다. |
| [KnownColor](./knowncolor/) | 알려진 시스템 색상을 지정합니다. |
| [LineCap](./linecap/) | [`Pen`](../aspose.psd/pen/) 객체가 선을 끝낼 때 사용할 수 있는 캡 스타일을 지정합니다. |
| [LineJoin](./linejoin/) | [`GraphicsPath`](../aspose.psd/graphicspath/) 객체에 포함된 도형(서브패스)에서 연속적인 선 또는 곡선 세그먼트를 연결하는 방법을 지정합니다. |
| [MatrixOrder](./matrixorder/) | 행렬 변환 작업의 순서를 지정합니다. |
| [PdfComplianceVersion](./pdfcomplianceversion/) | 출력 파일에 대한 PDF 준수 수준을 지정합니다. |
| [PenAlignment](./penalignment/) | 이론적인, 너비가 0인 선에 대한 [`Pen`](../aspose.psd/pen/) 객체의 정렬을 지정합니다. |
| [PenType](./pentype/) | 라인을 채우는 데 사용되는 [`Pen`](../aspose.psd/pen/) 객체의 채우기 유형을 지정합니다. |
| [PixelFormat](./pixelformat/) | 픽셀 데이터 형식의 실제 의미입니다. |
| [ResizeType](./resizetype/) | 크기 조정 유형을 지정합니다. |
| [ResolutionUnit](./resolutionunit/) | 해상도 단위 열거형. |
| [RotateFlipType](./rotatefliptype/) | 이미지가 회전되는 각도와 이미지를 뒤집는 데 사용되는 축을 지정합니다. |
| [SeekOrigin](./seekorigin/) | 검색을 위해 [`StreamContainer`](../aspose.psd/streamcontainer/)에서 참조점을 나타내는 필드를 제공합니다. |
| [SmoothingMode](./smoothingmode/) | 선과 곡선 및 채워진 영역의 가장자리에 스무딩(안티앨리어싱)이 적용되는지 여부를 지정합니다. |
| [StringAlignment](./stringalignment/) | 텍스트 문자열을 레이아웃 사각형에 상대적으로 정렬하는 방식을 지정합니다. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | 열거형은 사용자의 로케일 또는 언어에 따라 문자열의 숫자를 대체하는 방법을 지정합니다. |
| [StringFormatFlags](./stringformatflags/) | 텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다. |
| [StringTrimming](./stringtrimming/) | 레이아웃 형태에 완전히 맞지 않는 문자열에서 문자를 잘라내는 방법을 지정합니다. |
| [TextRenderingHint](./textrenderinghint/) | 텍스트 렌더링 품질을 지정합니다. |
| [WarpMode](./warpmode/) | 적용되는 왜곡 변환 유형을 지정합니다. |
| [WrapMode](./wrapmode/) | 텍스처 또는 그라디언트가 채워지는 영역보다 작을 때 타일링되는 방식을 지정합니다. |


