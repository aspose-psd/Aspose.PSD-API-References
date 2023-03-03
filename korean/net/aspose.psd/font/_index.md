---
title: Class Font
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Font 수업. 글꼴 크기 및 스타일 속성을 포함하여 텍스트의 특정 형식을 정의합니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 4280
url: /ko/net/aspose.psd/font/
---
## Font class

글꼴, 크기 및 스타일 속성을 포함하여 텍스트의 특정 형식을 정의합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class Font
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 새 항목을 초기화합니다.`Font` 지정된 기존`Font` 그리고[`FontStyle`](../fontstyle/) 열거형. |
| [Font](font/#constructor_1)(string, float) | 새 항목을 초기화합니다.`Font` 지정된 크기를 사용합니다. 문자 집합은 다음과 같이 설정됩니다.Default , 그래픽 단위Point , 글꼴 스타일Regular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | 새 항목을 초기화합니다.`Font` 지정된 크기와 스타일을 사용합니다. 문자 집합은 다음과 같이 설정됩니다.Default , 그래픽 단위Point . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 새 항목을 초기화합니다.`Font` 지정된 크기와 단위를 사용합니다. 문자 집합은 다음과 같이 설정됩니다.Default 스타일은 다음으로 설정됩니다.Regular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 새 항목을 초기화합니다.`Font` 지정된 크기, 스타일 및 단위를 사용합니다. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 새 항목을 초기화합니다.`Font` 지정된 크기, 스타일, 단위 및 문자 집합을 사용합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`Font` 굵게. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | 이 문자 집합을 지정하는 바이트 값을 가져옵니다.`Font` 사용합니다. |
| [Italic](../../aspose.psd/font/italic/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`Font`기울임꼴입니다. |
| [Name](../../aspose.psd/font/name/) { get; } | 이것의 얼굴 이름을 얻습니다.`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | 이것의 전각 크기를 얻습니다.`Font` 에서 지정한 단위로 측정[`Unit`](./unit/) 속성. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`Font` font. 를 통해 수평선을 지정합니다. |
| [Style](../../aspose.psd/font/style/) { get; } | 이에 대한 스타일 정보를 가져옵니다.`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`Font` 밑줄이 그어져 있습니다. |
| [Unit](../../aspose.psd/font/unit/) { get; } | 이에 대한 측정 단위를 가져옵니다.`Font` . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | 이것의 정확한 딥 카피를 생성합니다.`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | 지정된 개체가`Font` 이것과 동일한 속성 값을 가집니다.`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | 이에 대한 해시 코드를 가져옵니다.`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | 사람이 읽을 수 있는 문자열 표현을 반환합니다.`Font` . |

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

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


