---
title: "Class Region"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Region 클래스. 사각형과 경로로 구성된 그래픽 형태의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다."
type: docs
weight: 5860
url: /ko/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

사각형 및 경로로 구성된 그래픽 도형의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class Region
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Region](region/#constructor)() | 새 `Region`을 초기화합니다. |
| [Region](region/#constructor_1)(GraphicsPath) | 지정된 [`GraphicsPath`](../graphicspath/)를 사용하여 새 `Region`을 초기화합니다. |
| [Region](region/#constructor_2)(Rectangle) | 지정된 [`Rectangle`](../rectangle/) 구조체에서 새 `Region`을 초기화합니다. |
| [Region](region/#constructor_3)(RectangleF) | 지정된 [`RectangleF`](../rectanglef/) 구조체에서 새 `Region`을 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | 지정된 [`GraphicsPath`](../graphicspath/) 중 이 `Region`과 교차하지 않는 부분을 포함하도록 이 `Region`을 업데이트합니다. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | 지정된 [`Rectangle`](../rectangle/) 구조체 중 이 `Region`과 교차하지 않는 부분을 포함하도록 이 `Region`을 업데이트합니다. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | 이 `Region`을 업데이트하여 지정된 [`RectangleF`](../rectanglef/) 구조 중 이 `Region`과 교차하지 않는 부분을 포함합니다. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | 이 `Region`을 업데이트하여 지정된 `Region` 중 이 `Region`과 교차하지 않는 부분을 포함합니다. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | 이 `Region`의 정확한 깊은 복사본을 생성합니다. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | 객체가 동일한지 확인합니다. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | 지정된 `Region`이 지정된 그리기 표면에서 이 `Region`과 동일한지 테스트합니다. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | 이 `Region`을 업데이트하여 지정된 [`GraphicsPath`](../graphicspath/)와 교차하지 않는 내부 부분만 포함합니다. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | 이 `Region`을 업데이트하여 지정된 [`Rectangle`](../rectangle/) 구조와 교차하지 않는 내부 부분만 포함합니다. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | 이 `Region`을 업데이트하여 지정된 [`RectangleF`](../rectanglef/) 구조와 교차하지 않는 내부 부분만 포함합니다. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | 이 `Region`을 업데이트하여 지정된 `Region`과 교차하지 않는 내부 부분만 포함합니다. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | 현재 객체의 해시 코드를 가져옵니다. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | 이 `Region`을 지정된 [`GraphicsPath`](../graphicspath/)와의 교차 영역으로 업데이트합니다. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | 이 `Region`을 지정된 [`Rectangle`](../rectangle/) 구조와의 교차 영역으로 업데이트합니다. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | 이 `Region`을 지정된 [`RectangleF`](../rectanglef/) 구조와의 교차 영역으로 업데이트합니다. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | 이 `Region`을 지정된 `Region`과의 교차 영역으로 업데이트합니다. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | 지정된 그리기 표면에서 이 `Region`이 비어 있는 내부를 가지고 있는지 테스트합니다. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | 지정된 그리기 표면에서 이 `Region`이 무한한 내부를 가지고 있는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | 지정된 [`Point`](../point/) 구조가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | 지정된 [`PointF`](../pointf/) 구조가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | 지정된 [`Rectangle`](../rectangle/) 구조의 일부가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | 지정된 [`RectangleF`](../rectanglef/) 구조의 일부가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | 지정된 점이 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 지정된 [`Point`](../point/) 구조가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 지정된 [`PointF`](../pointf/) 구조가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 지정된 [`Rectangle`](../rectangle/) 구조의 일부가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 지정된 [`RectangleF`](../rectanglef/) 구조의 일부가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 지정된 점이 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | 지정된 [`Graphics`](../graphics/) 객체를 사용하여 그릴 때 지정된 점이 이 `Region` 객체에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | 지정된 사각형의 일부가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | 지정된 사각형의 일부가 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | 지정된 사각형의 일부가 지정된 [`Graphics`](../graphics/)를 사용하여 그린 경우 이 `Region`에 포함되는지 테스트합니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | 지정된 사각형의 일부가 지정된 [`Graphics`](../graphics/)를 사용하여 그린 경우 이 `Region`에 포함되는지 테스트합니다. |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | 이 `Region`을 빈 내부로 초기화합니다. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | 이 `Region` 객체를 무한한 내부로 초기화합니다. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | 지정된 [`Matrix`](../matrix/)를 사용하여 이 `Region`을 변환합니다. |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | 지정된 양만큼 이 `Region`의 좌표를 오프셋합니다. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | 지정된 양만큼 이 `Region`의 좌표를 오프셋합니다. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | 이 `Region`을 자체와 지정된 [`GraphicsPath`](../graphicspath/)의 합집합으로 업데이트합니다. |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | 이 `Region`을 자체와 지정된 [`Rectangle`](../rectangle/) 구조의 합집합으로 업데이트합니다. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | 이 `Region`을 자체와 지정된 [`RectangleF`](../rectanglef/) 구조의 합집합으로 업데이트합니다. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | 이 `Region`을 자체와 지정된 `Region`의 합집합으로 업데이트합니다. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | 이 `Region`을 자체와 지정된 [`GraphicsPath`](../graphicspath/)의 교차를 제외한 합집합으로 업데이트합니다. |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | 이 `Region`을 자체와 지정된 [`Rectangle`](../rectangle/) 구조의 교차를 제외한 합집합으로 업데이트합니다. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | 이 `Region`을 자체와 지정된 [`RectangleF`](../rectanglef/) 구조의 교차를 제외한 합집합으로 업데이트합니다. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | 이 `Region`을 자체와 지정된 `Region`의 교차를 제외한 합집합으로 업데이트합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


