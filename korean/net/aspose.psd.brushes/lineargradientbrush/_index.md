---
title: Class LinearGradientBrush
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Brushes.LinearGradientBrush 수업. 캡슐화Brush 선형 그래디언트로. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 140
url: /ko/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

캡슐화[`Brush`](../../aspose.psd/brush/) 선형 그래디언트로. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 기본 매개 변수가 있는 클래스입니다. 시작 색상은 검은색, 끝 색상은 흰색, 각도는 45도, 직사각형은 크기가 (1,1)인 (0,0)에 있습니다. |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 지정된 포인트와 색상이 있는 클래스. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 지정된 포인트와 색상이 있는 클래스. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 직사각형, 시작 및 끝 색상, 방향 각도를 기반으로 하는 클래스입니다. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 직사각형, 시작 및 끝 색상, 방향 각도를 기반으로 하는 클래스입니다. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 직사각형, 시작 및 끝 색상, 방향 각도를 기반으로 하는 클래스입니다. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | 의 새 인스턴스를 초기화합니다.`LinearGradientBrush` 직사각형, 시작 및 끝 색상, 방향 각도를 기반으로 하는 클래스입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | 그라데이션 각도를 가져오거나 설정합니다. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | 가져오거나 설정합니다.[`Blend`](../../aspose.psd/blend/) gradient. 에 대한 사용자 지정 폴오프를 정의하는 위치 및 요소를 지정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | 끝 그라데이션 색상을 가져오거나 설정합니다. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | 감마 보정이 활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | 여부를 나타내는 값을 가져오거나 설정합니다.[`Angle`](../lineargradientbrushbase/angle/) 이것으로 변환하는 동안 변경됩니다.[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 어떤 식으로든 변환이 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출합니다. 이 속성은 GDI+. 와의 하위 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 값이 0이면 브러시가 완전히 표시되고 값이 1이면 브러시가 완전히 불투명합니다. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | 그래디언트의 시작점과 끝점을 정의하는 직사각형 영역을 가져오거나 설정합니다. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | 시작 그라데이션 색상을 가져오거나 설정합니다. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 복사본을 가져오거나 설정합니다.[`Matrix`](../../aspose.psd/matrix/) 이에 대한 로컬 기하학적 변환을 정의합니다.[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | 가져오거나 설정합니다.[`WrapMode`](../../aspose.psd/wrapmode/) 이것에 대한 래핑 모드를 나타내는 열거[`TransformBrush`](../transformbrush/) . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재의 새로운 딥 클론을 생성합니다.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | 곱하기[`Matrix`](../../aspose.psd/matrix/) 이것은 이것의 국지적 기하학적 변환을 나타냅니다.`LinearGradientBrush` 지정된[`Matrix`](../../aspose.psd/matrix/) 지정된[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 곱하기[`Matrix`](../../aspose.psd/matrix/) 이것은 이것의 국지적 기하학적 변환을 나타냅니다.`LinearGradientBrush` 지정된[`Matrix`](../../aspose.psd/matrix/) 지정된 order. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | 재설정[`Transform`](../transformbrush/transform/) 신원에 재산. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 로컬 기하 변환을 지정된 양만큼 회전합니다. 이 방법은 변환 앞에 회전을 추가합니다. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 지정된 순서로 지정된 양만큼 로컬 기하 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 지정된 양만큼 로컬 기하 변환의 크기를 조정합니다. 이 방법은 스케일링 행렬을 transform. 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 지정된 순서로 지정된 양만큼 로컬 기하 변환을 확장합니다. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 중앙 색상을 사용하여 선형 그래디언트를 만들고 양쪽 끝에서 단일 색상으로 선형 감쇠를 만듭니다. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 중앙 색상을 사용하여 선형 그래디언트를 만들고 양쪽 끝에서 단일 색상으로 선형 감쇠를 만듭니다. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | 종 모양의 곡선을 기반으로 그라데이션 폴오프를 만듭니다. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | 종 모양의 곡선을 기반으로 그라데이션 폴오프를 만듭니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 지정된 치수로 로컬 기하 변환을 변환합니다. 이 방법은 변환을 transform. 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 지정된 순서로 지정된 치수로 로컬 기하 변환을 변환합니다. |

### 또한보십시오

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* 네임스페이스 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 집회 [Aspose.PSD](../../)


