---
title: "클래스 ProgressEventHandlerInfo"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo 클래스. 이 클래스는 외부 애플리케이션에서 변환 진행 상황을 최종 사용자에게 표시하기 위해 사용할 수 있는 이미지 로드/저장/내보내기 작업 진행에 대한 정보를 나타냅니다."
type: docs
weight: 5800
url: /ko/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

이 클래스는 이미지 로드/저장/내보내기 작업 진행에 대한 정보를 나타내며, 외부 애플리케이션에서 최종 사용자에게 변환 진행 상황을 표시하는 데 사용할 수 있습니다.

```csharp
public class ProgressEventHandlerInfo
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | 이벤트의 설명을 가져옵니다 |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | 이벤트의 유형을 가져옵니다. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | 상위 진행 값 한계를 가져옵니다. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | 현재 진행 값을 가져옵니다. |

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

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


