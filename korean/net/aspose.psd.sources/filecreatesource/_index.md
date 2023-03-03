---
title: Class FileCreateSource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Sources.FileCreateSource 수업. 생성할 파일 소스를 나타냅니다.
type: docs
weight: 5590
url: /ko/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

생성할 파일 소스를 나타냅니다.

```csharp
public sealed class FileCreateSource : FileSource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | 의 새 인스턴스를 초기화합니다.`FileCreateSource` 클래스. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | 의 새 인스턴스를 초기화합니다.`FileCreateSource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | 생성할 파일 경로를 가져옵니다. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | 파일이 일시적인지 여부를 나타내는 값을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | 스트림 컨테이너를 가져옵니다. |

### 예

이 예제는 Font 및 SolidBrush 클래스를 사용하여 이미지 표면에 문자열을 그리는 방법을 보여줍니다. 이 예에서는 Figures 및 GraphicsPath를 사용하여 새 이미지를 만들고 도형을 그립니다.

```csharp
[C#]

//이미지 인스턴스 생성
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics 클래스의 인스턴스 생성 및 초기화
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //그래픽 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //Font 인스턴스 생성
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //빨간색을 갖는 SolidBrush의 인스턴스 생성
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //문자열 그리기
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 내보내기 옵션을 만듭니다.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 모든 변경 사항 저장
    image.Save("C:\\temp\\output.gif", options);
}
```

### 또한보십시오

* class [FileSource](../filesource/)
* 네임스페이스 [Aspose.PSD.Sources](../../aspose.psd.sources/)
* 집회 [Aspose.PSD](../../)


