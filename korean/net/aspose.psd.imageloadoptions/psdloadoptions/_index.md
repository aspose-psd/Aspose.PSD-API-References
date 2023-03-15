---
title: Class PsdLoadOptions
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions 수업. Psd 로드 옵션
type: docs
weight: 4770
url: /ko/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd 로드 옵션

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
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | 워프 변환을 사용하거나 사용하지 않고 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | 가져오거나 설정합니다.[`Image`](../../aspose.psd/image/) 배경[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | 데이터 복구 모드를 가져오거나 설정합니다. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | [알파 채널 무시]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | UpdateText 작업 실행 시 PSD 텍스트 레이어 고정 너비를 무시할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | [로드 효과 리소스](기본적으로 리소스가 로드되지 않음) 여부를 나타내는 값을 가져오거나 설정합니다. 이 옵션을 설정하면 지원되는 효과만 최종 병합 이미지로 렌더링됩니다. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | 진행률 이벤트 처리기를 가져오거나 설정합니다. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | [읽기 전용 모드 사용] 여부를 나타내는 값을 가져오거나 설정합니다. Adobe Photoshop과 동일한 호환성을 위해 지원되는 읽기 전용 모드입니다. 이 옵션을 설정하면 레이어에 적용된 모든 변경 사항이 최종 이미지에 저장되지 않습니다. 모든 데이터는 ImageData 섹션에서 사용하므로 Photoshop과 동일합니다. 기본적으로 로드된 모든 이미지는 Adobe Photoshop과 동일하지 않습니다. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | [부하 효과 리소스에 디스크 사용] 여부를 나타내는 값을 가져오거나 설정합니다(기본적으로 효과 리소스를 로드하는 데 디스크를 사용하지만 이 값을 false로 설정하여 충분할 경우 메모리를 사용할 수 있음). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | ICC 프로필 변환을 적용할지 여부를 나타내는 값을 가져오거나 설정합니다. |

### 예

다음 예는 문서 변환 진행이 예외 없이 올바르게 작동함을 보여줍니다.

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

### 또한보십시오

* class [LoadOptions](../../aspose.psd/loadoptions/)
* 네임스페이스 [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* 집회 [Aspose.PSD](../../)


