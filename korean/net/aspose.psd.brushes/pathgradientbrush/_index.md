---
title: "클래스 PathGradientBrush"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.PathGradientBrush 클래스. 그라디언트를 가진 Brush 객체를 캡슐화합니다. 이 클래스는 상속될 수 없습니다."
type: docs
weight: 170
url: /ko/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

그라디언트를 가진 [`Brush`](../../aspose.psd/brush/) 객체를 캡슐화합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | 지정된 경로를 사용하여 `PathGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | 지정된 포인트를 사용하여 `PathGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | 지정된 포인트를 사용하여 `PathGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | 지정된 포인트와 랩 모드를 사용하여 `PathGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | 지정된 포인트와 랩 모드를 사용하여 `PathGradientBrush` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 [`Blend`](../../aspose.psd/blend/)을 가져오거나 설정합니다. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | 경로 그라디언트 중심의 색상을 가져오거나 설정합니다. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 그라디언트 감소를 위한 포커스 포인트를 가져오거나 설정합니다. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 이 브러시가 기반으로 하는 그래픽 경로를 가져옵니다. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | 다중 색상 선형 그라디언트를 정의하는 [`ColorBlend`](../../aspose.psd/colorblend/)을 가져오거나 설정합니다. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 변환이 어떤 방식으로든 변경되었는지를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 이전 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | 이 브러시가 기반으로 하는 경로 포인트를 가져옵니다. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | `PathGradientBrush`가 채우는 경로의 포인트에 해당하는 색상 배열을 가져오거나 설정합니다. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 중심 색상과 하나의 주변 색상으로 선형 감쇠되는 그라디언트를 생성합니다. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 중심 색상과 각 주변 색상으로 선형 감쇠되는 그라디언트를 생성합니다. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | 경로의 중심에서 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 한 색상에서 다른 색상으로의 전환은 종 모양 곡선을 기반으로 합니다. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | 경로의 중심에서 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 한 색상에서 다른 색상으로의 전환은 종 모양 곡선을 기반으로 합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |

## 비고

중심 색상은 기본적으로 흰색입니다. 사용자는 나중에 언제든지 이 값을 변경할 수 있습니다.

주변 색상 배열은 기본적으로 흰색을 포함하는 단일 요소로 초기화됩니다. 주변 색상은 나중에 변경될 수 있지만, 주변 색상을 설정할 때 최소 하나의 요소가 필요합니다.

초기화에 대한 자세한 내용은 [`Blend`](./blend/)를 참조하십시오.

### 또 보기

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


