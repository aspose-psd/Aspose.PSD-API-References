---
title: "RawColor 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor 클래스. Raw Color 클래스는 채널 수, 색상 모드 및 비트 깊이에 관계없이 색상을 저장하는 데 도움이 됩니다. 일부 내부 클래스는 RawColor를 기본 형식으로 변환하는 데 문제가 있을 수 있으므로 API가 CMYK 색상을 제공하는 경우 제공된 형식을 사용하는 것이 더 신뢰할 수 있습니다. 또한 Raw Color가 변환될 수 있는 경우도 있습니다."
type: docs
weight: 1650
url: /ko/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class는 채널 수, 색상 모드 및 비트 깊이에 관계없이 색상을 저장하는 데 도움이 됩니다. 일부 내부 클래스는 RawColor를 기본 형식으로 변환하는 데 문제가 있을 수 있으므로 API가 CMYK 색상을 제공하는 경우 제공된 형식을 사용하는 것이 더 신뢰할 수 있습니다. 또한 Raw Color가 변환될 수 있는 경우도 있습니다.

```csharp
public sealed class RawColor
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | `RawColor` 클래스의 새 인스턴스를 초기화합니다. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | 미리 정의된 색상 모드를 사용하여 픽셀 데이터 형식에서 `RawColor` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | 색상이 따를 모드. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | 색상의 구성 요소를 가져옵니다. 각 구성 요소는 별개의 채널이며, 일반적이지 않은 색상 체계를 사용하는 경우 각 채널을 별도로 작업하는 것이 좋습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | 지정된 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | 가능한 경우 색상을 int 형식으로 가져옵니다. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | 가능한 경우 색상을 long 형식으로 가져옵니다. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Raw Color의 비트 깊이를 가져옵니다. 예를 들어, 채널/구성 요소당 8비트인 ARGB 색상의 경우 전체 ARGB 색상의 비트 깊이는 32비트이며, 채널당 16비트인 경우 64비트입니다. 비트 깊이는 채널 비트 깊이의 합계로 누적됩니다. 서로 다른 채널이 서로 다른 비트 깊이를 가질 수도 있습니다. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | 색상 모드의 이름을 가져옵니다. 색상 모드 이름은 채널/구성 요소 이름에서 누적됩니다. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | 현재 객체의 해시 코드를 가져옵니다. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | 가능한 경우 int 인수를 사용하여 모든 채널에 데이터를 설정합니다. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | 가능한 경우 int 인수를 사용하여 모든 채널에 데이터를 설정합니다. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | 연산자 ==를 구현합니다. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | 연산자 !=를 구현합니다. |

## 예제

다음 코드는 구식 Color 구조체 대신 RawColor 클래스를 지원하는 예시를 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


