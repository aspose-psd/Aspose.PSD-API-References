---
title: "Font 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Font 클래스. 텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴 크기와 스타일 속성이 포함됩니다. 이 클래스는 상속될 수 없습니다."
type: docs
weight: 4750
url: /ko/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

텍스트에 대한 특정 형식을 정의합니다. 여기에는 글꼴, 크기 및 스타일 속성이 포함됩니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class Font
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 지정된 기존 `Font`와 [`FontStyle`](../fontstyle/) 열거형을 사용하는 새 `Font`를 초기화합니다. |
| [Font](font/#constructor_1)(string, float) | 지정된 크기를 사용하여 새 `Font`를 초기화합니다. 문자 집합은 Default로, 그래픽 단위는 Point로, 글꼴 스타일은 Regular로 설정됩니다. |
| [Font](font/#constructor_2)(string, float, FontStyle) | 지정된 크기와 스타일을 사용하여 새 `Font`를 초기화합니다. 문자 집합은 Default로, 그래픽 단위는 Point로 설정됩니다. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 지정된 크기와 단위를 사용하여 새 `Font`를 초기화합니다. 문자 집합은 Default로, 스타일은 Regular로 설정됩니다. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 지정된 크기, 스타일 및 단위를 사용하여 새 `Font`를 초기화합니다. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새 `Font`를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | 이 `Font`가 굵게 표시되는지 여부를 나타내는 값을 가져옵니다. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | 이 `Font`가 사용하는 문자 집합을 지정하는 바이트 값을 가져옵니다. |
| [Italic](../../aspose.psd/font/italic/) { get; } | 이 `Font`가 이탤릭인지 여부를 나타내는 값을 가져옵니다. |
| [Name](../../aspose.psd/font/name/) { get; } | 이 `Font`의 글꼴 이름을 가져옵니다. |
| [Size](../../aspose.psd/font/size/) { get; } | [`Unit`](./unit/) 속성에서 지정한 단위로 측정된 이 `Font`의 em 크기를 가져옵니다. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | 이 `Font`가 글꼴에 가로선을 지정하는지 여부를 나타내는 값을 가져옵니다. |
| [Style](../../aspose.psd/font/style/) { get; } | 이 `Font`의 스타일 정보를 가져옵니다. |
| [Underline](../../aspose.psd/font/underline/) { get; } | 이 `Font`에 밑줄이 있는지 여부를 나타내는 값을 가져옵니다. |
| [Unit](../../aspose.psd/font/unit/) { get; } | 이 `Font`의 측정 단위를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | 이 `Font`의 정확한 깊은 복사본을 생성합니다. |
| override [Equals](../../aspose.psd/font/equals/)(object) | 지정된 객체가 `Font`이며 이 `Font`와 동일한 속성 값을 가지고 있는지 여부를 나타냅니다. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | 이 `Font`의 해시 코드를 가져옵니다. |
| override [ToString](../../aspose.psd/font/tostring/)() | 이 `Font`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


