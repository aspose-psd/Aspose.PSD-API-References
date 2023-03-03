---
title: Delegate ProgressEventHandler
second_title: .NET API 참조용 Aspose.PSD
description: 진행 이벤트 핸들러 함수 reference
type: docs
weight: 5280
url: /ko/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

진행 이벤트 핸들러 함수 reference

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | 진행률 이벤트 처리기 데이터입니다. |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


