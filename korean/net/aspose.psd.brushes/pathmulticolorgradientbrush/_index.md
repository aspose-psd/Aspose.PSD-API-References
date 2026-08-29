---
title: "클래스 PathMulticolorGradientBrush"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.PathMulticolorGradientBrush 클래스. 그라디언트를 가진 Brush 객체를 캡슐화합니다. 이 클래스는 상속될 수 없습니다."
type: docs
weight: 190
url: /ko/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
{{< psd/tize >}}
## PathMulticolorGradientBrush class

그라디언트를 가진 [`Brush`](../../aspose.psd/brush/) 객체를 캡슐화합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor)(GraphicsPath) | 지정된 경로를 사용하여 `PathMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_1)(PointF[]) | 지정된 점들을 사용하여 `PathMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_3)(Point[]) | 지정된 점들을 사용하여 `PathMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_2)(PointF[], WrapMode) | 지정된 점들과 랩 모드를 사용하여 `PathMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_4)(Point[], WrapMode) | 지정된 점들과 랩 모드를 사용하여 `PathMulticolorGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 그라디언트 감소를 위한 포커스 포인트를 가져오거나 설정합니다. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 이 브러시가 기반으로 하는 그래픽 경로를 가져옵니다. |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors/) { get; set; } | 다중 색상 선형 그라디언트를 정의하는 [`ColorBlend`](../../aspose.psd/colorblend/)을 가져오거나 설정합니다. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 변환이 어떤 방식으로든 변경되었는지를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 이전 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | 이 브러시가 기반으로 하는 경로 포인트를 가져옵니다. |
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

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


