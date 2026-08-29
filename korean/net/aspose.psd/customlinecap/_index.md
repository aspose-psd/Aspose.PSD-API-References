---
title: "클래스 CustomLineCap"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.CustomLineCap 클래스. 사용자 정의 라인 캡을 캡슐화합니다."
type: docs
weight: 710
url: /ko/net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

사용자 정의 라인 캡을 캡슐화합니다.

```csharp
public class CustomLineCap
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | 지정된 외곽선과 채우기를 사용하여 `CustomLineCap` 클래스의 새 인스턴스를 초기화합니다. |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | 지정된 기존 [`LineCap`](../linecap/) 열거형과 지정된 외곽선 및 채우기를 사용하여 `CustomLineCap` 클래스의 새 인스턴스를 초기화합니다. |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | 지정된 기존 [`LineCap`](../linecap/) 열거형을 사용하여 지정된 외곽선, 채우기 및 삽입값으로 `CustomLineCap` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | `CustomLineCap`이 기반으로 하는 [`LineCap`](../linecap/) 열거형을 가져오거나 설정합니다. |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | 캡과 선 사이의 거리를 가져오거나 설정합니다. |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | 사용자 정의 캡의 채우기를 정의하는 객체를 가져오거나 설정합니다. |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | `CustomLineCap` 객체를 구성하는 선들이 어떻게 연결되는지를 결정하는 [`LineJoin`](../linejoin/) 열거형을 가져오거나 설정합니다. |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | 사용자 정의 캡의 외곽선을 정의하는 객체를 가져오거나 설정합니다. |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | Pen 객체의 너비에 대한 비율로 이 `CustomLineCap` 클래스 객체를 스케일링할 양을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | 이 사용자 정의 캡을 구성하는 선들의 시작 및 끝에 사용되는 캡을 가져옵니다. |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | 이 사용자 정의 캡을 구성하는 선들의 시작 및 끝에 사용되는 캡을 설정합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


