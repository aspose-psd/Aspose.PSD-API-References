---
title: Class Region
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Region 수업. 직사각형과 경로로 구성된 그래픽 모양의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 5360
url: /ko/net/aspose.psd/region/
---
## Region class

직사각형과 경로로 구성된 그래픽 모양의 내부를 설명합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class Region
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Region](region/#constructor)() | 새 항목을 초기화합니다.`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | 새 항목을 초기화합니다.`Region` 지정된[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | 새 항목을 초기화합니다.`Region` 지정된 것에서[`Rectangle`](../rectangle/)구조. |
| [Region](region/#constructor_3)(RectangleF) | 새 항목을 초기화합니다.`Region` 지정된 것에서[`RectangleF`](../rectanglef/)구조. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | 업데이트`Region` 지정된 부분을 포함하려면[`GraphicsPath`](../graphicspath/) 이것과 교차하지 않는`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | 업데이트`Region` 지정된 부분을 포함하려면[`Rectangle`](../rectangle/) 이것과 교차하지 않는 구조`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | 업데이트`Region` 지정된 부분을 포함하려면[`RectangleF`](../rectanglef/) 이것과 교차하지 않는 구조`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | 업데이트`Region` 지정된 부분을 포함하려면`Region` 이것과 교차하지 않는`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | 이것의 정확한 딥 카피를 생성합니다.`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | 지정된`Region` 이것과 동일하다`Region` 지정된 도면 표면에. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | 업데이트`Region` 지정된 것과 교차하지 않는 내부 부분만 포함합니다.[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | 업데이트`Region` 지정된 것과 교차하지 않는 내부 부분만 포함합니다.[`Rectangle`](../rectangle/)구조. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | 업데이트`Region` 지정된 것과 교차하지 않는 내부 부분만 포함합니다.[`RectangleF`](../rectanglef/)구조. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | 업데이트`Region` 지정된 것과 교차하지 않는 내부 부분만 포함합니다.`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | 업데이트`Region` 지정된[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | 업데이트`Region` 지정된[`Rectangle`](../rectangle/)구조. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | 업데이트`Region` 지정된[`RectangleF`](../rectanglef/)구조. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | 업데이트`Region` 지정된`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | 이 여부를 테스트합니다.`Region` 지정된 도면 표면에 빈 내부가 있습니다. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | 이 여부를 테스트합니다.`Region` 지정된 도면 표면에 무한한 내부가 있습니다. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | 지정된[`Point`](../point/) 구조는 이 안에 포함되어 있습니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | 지정된[`PointF`](../pointf/) 구조는 이 안에 포함되어 있습니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | 지정된 부분이[`Rectangle`](../rectangle/) 구조는 이 안에 포함되어 있습니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | 지정된 부분이[`RectangleF`](../rectanglef/) 구조는 이 안에 포함되어 있습니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | 지정된 점이 이 안에 포함되는지 여부를 테스트합니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | 지정된[`Point`](../point/) 구조는 이 안에 포함되어 있습니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | 지정된[`PointF`](../pointf/) 구조는 이 안에 포함되어 있습니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | 지정된 부분이[`Rectangle`](../rectangle/) 구조는 이 안에 포함되어 있습니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | 지정된 부분이[`RectangleF`](../rectanglef/) 구조는 이 안에 포함되어 있습니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | 지정된 점이 이 안에 포함되는지 여부를 테스트합니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | 지정된 점이 이 안에 포함되는지 여부를 테스트합니다.`Region` 지정된 것을 사용하여 그릴 때 개체[`Graphics`](../graphics/) object. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | 지정된 사각형의 일부가 이 안에 포함되는지 여부를 테스트합니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | 지정된 사각형의 일부가 이 안에 포함되는지 여부를 테스트합니다.`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | 지정된 사각형의 일부가 이 안에 포함되는지 여부를 테스트합니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | 지정된 사각형의 일부가 이 안에 포함되는지 여부를 테스트합니다.`Region` 지정된 것을 사용하여 그릴 때[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | 초기화`Region` 텅 빈 실내로. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | 초기화`Region` 무한한 내부에 객체. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | 이것을 변환`Region` 지정된[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | 이 좌표를 오프셋합니다.`Region`지정된 금액만큼. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | 이 좌표를 오프셋합니다.`Region`지정된 금액만큼. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | 업데이트`Region` 자신과 지정된[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | 업데이트`Region` 자신과 지정된[`Rectangle`](../rectangle/)구조. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | 업데이트`Region` 자신과 지정된[`RectangleF`](../rectanglef/)구조. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | 업데이트`Region` 자신과 지정된`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | 업데이트`Region` 유니온에서 지정된 것과의 교집합을 뺀 값[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | 업데이트`Region` 유니온에서 지정된 것과의 교집합을 뺀 값[`Rectangle`](../rectangle/)구조. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | 업데이트`Region` 유니온에서 지정된 것과의 교집합을 뺀 값[`RectangleF`](../rectanglef/)구조. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | 업데이트`Region` 유니온에서 지정된 것과의 교집합을 뺀 값`Region` . |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


