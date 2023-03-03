---
title: Class Image
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Image 수업. 이미지는 모든 유형의 이미지에 대한 기본 클래스입니다.
type: docs
weight: 4590
url: /ko/net/aspose.psd/image/
---
## Image class

이미지는 모든 유형의 이미지에 대한 기본 클래스입니다.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 팔레트 자동 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경색 값을 가져오거나 설정합니다. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 픽셀당 이미지 비트를 가져옵니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 범위를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [Container](../../aspose.psd/image/container/) { get; } | 가져오기`Image` 컨테이너. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 개체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 파일 format 의 값을 가져옵니다. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 이미지 높이를 가져옵니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 개체의 데이터가 현재 캐시되어 있고 데이터 읽기가 필요하지 않은지 여부를 나타내는 값을 가져옵니다. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. 픽셀을 직접 표현하는 경우 색상 팔레트를 사용하지 않습니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 이미지 너비를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | 지정된 만들기 옵션을 사용하여 새 이미지를 만듭니다. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | 지정된 스트림에서 새 이미지를 로드합니다. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | 지정된 파일에서 새 이미지를 로드합니다. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | 지정된 스트림에서 새 이미지를 로드합니다. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | 지정된 파일에서 새 이미지를 로드합니다. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 데이터를 캐시하고 기본에서 추가 데이터 로드가 수행되지 않도록 합니다.[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 전달된 저장 옵션으로 표시되는 지정된 파일 형식으로 이미지를 저장할 수 있는지 여부를 결정합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이것은 원본 이미지의 비트 심도 및 기타 매개 변수를 변경하지 않고 유지하는 데 유용할 수 있습니다. 예를 들어 흑백 PNG 이미지를 픽셀당 1비트로 로드한 다음 the 를 사용하여 저장[`Save`](../datastreamsupporter/save/) 방법을 사용하면 픽셀당 8비트의 출력 PNG 이미지가 생성됩니다. 이를 피하고 픽셀당 1비트의 PNG 이미지를 저장하려면 이 방법을 사용하여 해당 저장 옵션을 가져오고 them 를[`Save`](./save/)메소드를 두 번째 매개변수로 지정합니다. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | 이미지 크기를 조정합니다. 기본값LeftTopToLeftTop사용중입니다. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | 이미지 크기를 조정합니다. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | 이미지 크기를 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 이미지를 회전, 뒤집기 또는 회전하고 뒤집습니다. |
| [Save](../../aspose.psd/image/save/#save)() | 이미지 데이터를 기본 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 개체의 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | 이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | 저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | 저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | 지정된 스트림에서 이미지를 로드할 수 있는지 여부를 결정합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 여부를 결정합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | 지정된 스트림에서 이미지를 로드할 수 있는지 여부를 결정하고 선택적으로 지정된*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | 지정된 파일 경로에서 선택적으로 지정된 열기 옵션을 사용하여 이미지를 로드할 수 있는지 여부를 결정합니다. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | 파일 형식을 가져옵니다. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | 파일 형식을 가져옵니다. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | 비례 높이를 가져옵니다. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | 비례 너비를 가져옵니다. |

### 예

이 예에서는 PsdOptions 인스턴스의 Source 속성에 지정된 일부 디스크 위치에 새 이미지 파일을 만듭니다. 실제 이미지를 생성하기 전에 PsdOptions 인스턴스에 대한 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 나타내는 Source 속성입니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource의 인스턴스를 생성하고 PsdOptions 인스턴스의 소스로 할당합니다.
//두 번째 부울 매개변수는 생성할 파일이 IsTemporal인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Create 메서드를 호출하여 Image 인스턴스를 만들고 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행

    // 모든 변경 사항 저장
    image.Save();
}
```

### 또한보십시오

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


