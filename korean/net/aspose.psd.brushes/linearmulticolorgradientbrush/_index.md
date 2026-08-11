---
title: "클래스 LinearMulticolorGradientBrush"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.LinearMulticolorGradientBrush 클래스. 여러 색상과 적절한 위치로 정의된 선형 그라디언트를 가진 브러시를 나타냅니다. 이 클래스는 상속될 수 없습니다."
type: docs
weight: 160
url: /ko/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

여러 색상과 적절한 위치로 정의된 선형 그라디언트를 가진 [`Brush`](../../aspose.psd/brush/)를 나타냅니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | 기본 매개변수로 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. 시작 색상은 검정색, 끝 색상은 흰색이며, 각도는 45도이고 사각형은 (0,0)에 위치하고 크기는 (1,1)입니다. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | 지정된 점들을 사용하여 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | 지정된 점들을 사용하여 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | 사각형과 방향 각도를 기반으로 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | 사각형과 방향 각도를 기반으로 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | 사각형과 방향 각도를 기반으로 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | 사각형과 방향 각도를 기반으로 `LinearMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | 그라디언트 각도를 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | 이 [`LinearGradientBrushBase`](../lineargradientbrushbase/)에 대해 감마 보정이 활성화되어 있는지를 나타내는 값을 가져오거나 설정합니다. |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | 다중 색상 선형 그라디언트를 정의하는 [`ColorBlend`](../../aspose.psd/colorblend/)을 가져오거나 설정합니다. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | 이 [`LinearGradientBrushBase`](../lineargradientbrushbase/)와 함께 변환 중에 [`Angle`](../lineargradientbrushbase/angle/)이 변경되는지를 나타내는 값을 가져오거나 설정합니다. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 변환이 어떤 방식으로든 변경되었는지를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 이전 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | 그라디언트의 시작점과 끝점을 정의하는 사각형 영역을 가져오거나 설정합니다. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 이 [`TransformBrush`](../transformbrush/)에 대한 로컬 기하 변환을 정의하는 복사본 [`Matrix`](../../aspose.psd/matrix/)을 가져오거나 설정합니다. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | `[`WrapMode`](../../aspose.psd/wrapmode/)` 열거형을 가져오거나 설정합니다. 이 열거형은 이 [`TransformBrush`](../transformbrush/)의 랩 모드를 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재 [`Brush`](../../aspose.psd/brush/)의 새로운 깊은 복제본을 생성합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | 이 [`LinearGradientBrush`](../lineargradientbrush/)의 로컬 기하 변환을 나타내는 [`Matrix`](../../aspose.psd/matrix/)에 지정된 [`Matrix`](../../aspose.psd/matrix/)을 앞에 추가하여 곱합니다. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 이 [`LinearGradientBrush`](../lineargradientbrush/)의 로컬 기하 변환을 나타내는 [`Matrix`](../../aspose.psd/matrix/)에 지정된 순서대로 지정된 [`Matrix`](../../aspose.psd/matrix/)를 곱합니다. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | `[`Transform`](../transformbrush/transform/)` 속성을 항등 행렬로 재설정합니다. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 지정된 양만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전을 변환 앞에 추가합니다. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 지정된 양만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |

### 또 보기

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


