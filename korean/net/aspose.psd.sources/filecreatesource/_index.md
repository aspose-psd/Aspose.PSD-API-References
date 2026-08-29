---
title: "클래스 FileCreateSource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Sources.FileCreateSource 클래스. 생성용 파일 소스를 나타냅니다."
type: docs
weight: 6090
url: /ko/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

생성을 위한 파일 소스를 나타냅니다.

```csharp
public sealed class FileCreateSource : FileSource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | `FileCreateSource` 클래스의 새 인스턴스를 초기화합니다. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | `FileCreateSource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | 생성할 파일 경로를 가져옵니다. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | 파일이 일시적인지 여부를 나타내는 값을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | 스트림 컨테이너를 가져옵니다. |

## 예제

이 예제는 Font 및 SolidBrush 클래스를 사용하여 Image 표면에 문자열을 그리는 방법을 보여줍니다. 예제는 새 Image를 생성하고 Figures와 GraphicsPath를 사용하여 도형을 그립니다.

```csharp
[C#]

//Image의 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //Font의 인스턴스를 생성합니다.
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Red 색상을 가진 SolidBrush의 인스턴스를 생성합니다.
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //문자열을 그립니다.
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 내보내기 옵션을 생성합니다.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.gif", options);
}
```

### 또 보기

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


