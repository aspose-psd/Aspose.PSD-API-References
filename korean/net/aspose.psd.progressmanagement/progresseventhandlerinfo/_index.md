---
title: Class ProgressEventHandlerInfo
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo 수업. 이 클래스는 최종 사용자 에 대한 변환 진행률을 표시하기 위해 외부 응용 프로그램에서 사용할 수 있는 이미지 로드/저장/내보내기 작업 진행률 에 대한 정보를 나타냅니다.
type: docs
weight: 5300
url: /ko/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

이 클래스는 최종 사용자 에 대한 변환 진행률을 표시하기 위해 외부 응용 프로그램에서 사용할 수 있는 이미지 로드/저장/내보내기 작업 진행률, 에 대한 정보를 나타냅니다.

```csharp
public class ProgressEventHandlerInfo
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | event 에 대한 설명을 가져옵니다. |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | 이벤트 유형을 가져옵니다. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | 상한 진행 값 제한을 가져옵니다. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | 현재 진행 값을 가져옵니다. |

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

* 네임스페이스 [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* 집회 [Aspose.PSD](../../)


