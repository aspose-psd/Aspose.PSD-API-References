---
title: "클래스 PsdLoadOptions"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions 클래스. Psd 로드 옵션"
type: docs
weight: 5250
url: /ko/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

PSD 로드 옵션

```csharp
public class PsdLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | 레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | 왜곡 변환 여부에 관계없이 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | [`Image`](../../aspose.psd/image/) 배경 [`Color`](../../aspose.psd/color/)을 가져오거나 설정합니다. |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | 데이터 복구 모드를 가져오거나 설정합니다. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | [ignore alpha channel] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | PSD 텍스트 레이어 고정 너비가 UpdateText 작업 실행 시 무시될지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | [load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 리소스가 로드되지 않습니다). 이 옵션을 설정하면 지원되는 효과만 최종 병합 이미지에 렌더링됩니다. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | [use read only mode] 여부를 나타내는 값을 가져오거나 설정합니다. 이는 읽기 전용 모드이며 Adobe Photoshop과 동일한 호환성을 지원합니다. 이 옵션을 설정하면 레이어에 적용된 모든 변경 사항이 최종 이미지에 저장되지 않습니다. 모든 데이터는 ImageData 섹션에서 사용되므로 Photoshop과 동일합니다. 기본적으로 모든 로드된 이미지는 Adobe Photoshop과 호환되지 않습니다. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | PSD 이미지를 로드할 때 사용되는 읽기 전용 모드를 가져오거나 설정합니다. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | [use disk for load effects resource] 여부를 나타내는 값을 가져오거나 설정합니다 (기본적으로 효과 리소스를 로드하기 위해 디스크를 사용하지만, 이 값을 false로 설정하면 메모리를 사용할 수 있습니다). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | ICC 프로파일 변환을 적용할지 여부를 나타내는 값을 가져오거나 설정합니다. |

## 예제

다음 예제는 문서 변환 진행 상황이 올바르게 작동하고 예외 없이 수행됨을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### 또 보기

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


