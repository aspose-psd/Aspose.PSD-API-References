---
title: "Image 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Image 클래스. 이미지는 모든 유형의 이미지에 대한 기본 클래스입니다."
type: docs
weight: 5060
url: /ko/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

이미지는 모든 종류의 이미지에 대한 기본 클래스입니다.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 자동 팔레트 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경 색상의 값을 가져오거나 설정합니다. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 이미지의 픽셀당 비트 수를 가져옵니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 경계를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [Container](../../aspose.psd/image/container/) { get; } | `Image` 컨테이너를 가져옵니다. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 객체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 파일 형식 값을 가져옵니다. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 이미지 높이를 가져옵니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요하지 않은지를 나타내는 값을 가져옵니다. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상 팔레트를 가져오거나 설정합니다. 픽셀이 직접 표현될 때는 색상 팔레트를 사용하지 않습니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 이미지 팔레트를 사용할지 여부를 나타내는 값을 가져옵니다. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 이미지 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | 지정된 스트림에서 새 이미지를 로드합니다. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | 지정된 파일에서 새 이미지를 로드합니다. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | 지정된 스트림에서 새 이미지를 로드합니다. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | 지정된 파일에서 새 이미지를 로드합니다. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 데이터를 캐시하고 기본 [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 이미지를 전달된 저장 옵션으로 표시된 지정된 파일 형식으로 저장할 수 있는지 여부를 결정합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이는 원본 이미지의 비트 깊이 및 기타 매개변수를 변경하지 않도록 유지하는 데 도움이 될 수 있습니다. 예를 들어, 1비트 per 픽셀인 흑백 PNG 이미지를 로드한 다음 [`Save`](../datastreamsupporter/save/) 메서드를 사용하여 저장하면 8비트 per 픽셀인 출력 PNG 이미지가 생성됩니다. 이를 방지하고 1비트 per 픽셀 PNG 이미지를 저장하려면 이 메서드를 사용하여 해당 저장 옵션을 가져오고 두 번째 매개변수로 [`Save`](./save/) 메서드에 전달하십시오. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | 이미지를 크기 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | 이미지를 크기 조정합니다. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | 이미지를 크기 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | 너비를 비례적으로 조정합니다. 기본 NearestNeighbourResample이 사용됩니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다. |
| [Save](../../aspose.psd/image/save/#save)() | 이미지 데이터를 기본 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | 객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | 지정된 스트림에서 이미지를 로드할 수 있는지 확인합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | 지정된 파일 경로에서 이미지를 로드할 수 있는지 확인합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | 지정된 스트림에서 이미지를 로드할 수 있는지, 선택적으로 지정된 *loadOptions*를 사용하여 확인합니다. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | 지정된 파일 경로에서 이미지를 로드할 수 있는지, 선택적으로 지정된 열기 옵션을 사용하여 확인합니다. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | 파일 형식을 가져옵니다. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | 파일 형식을 가져옵니다. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 현재 이미지에 맞는 사각형을 가져옵니다. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | 비례 높이를 가져옵니다. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | 비례적인 너비를 가져옵니다. |

## 예제

이 예제는 PsdOptions 인스턴스의 Source 속성으로 지정된 디스크 위치에 새 Image 파일을 생성합니다. 실제 이미지를 만들기 전에 PsdOptions 인스턴스의 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 가리키는 Source 속성이 설정됩니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource의 인스턴스를 생성하고 이를 PsdOptions 인스턴스의 Source로 할당합니다.
//두 번째 Boolean 매개변수는 생성될 파일이 임시 파일인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image 인스턴스를 생성하고 Create 메서드를 호출하여 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //이미지 처리를 수행합니다.

    // 모든 변경 사항을 저장합니다.
    image.Save();
}
```

### 또 보기

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


