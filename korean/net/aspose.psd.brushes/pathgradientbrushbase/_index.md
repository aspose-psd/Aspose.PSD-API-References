---
title: "클래스 PathGradientBrushBase"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.PathGradientBrushBase 클래스. 기본 경로 그라디언트 기능을 갖는 브러시를 나타냅니다."
type: docs
weight: 180
url: /ko/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

기본 경로 그라디언트 기능을 갖는 [`Brush`](../../aspose.psd/brush/)를 나타냅니다.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 경로 그라디언트의 중심점을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 그라디언트 감소를 위한 포커스 포인트를 가져오거나 설정합니다. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 이 브러시가 기반으로 하는 그래픽 경로를 가져옵니다. |
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

## 비고

`PathGradientBrushBase` 클래스를 만들 때 최소 2개의 점으로 초기화해야 합니다. 생성된 내부 경로는 항상 닫힌 도형이며, 마지막 점이 첫 번째 점과 연결됩니다. 해당 도형은 이 `PathGradientBrushBase` 로 채워집니다. GDI+ 구현은 빈 배열이나 동일한 좌표를 가진 점 집합을 전달하면 OutOfMemoryException을 발생시킵니다. 점 배열에 2개 미만의 점이 포함된 경우 `PathGradientBrushBase`는 예외를 발생시키며, 이 경우 ArgumentException이 OutOfMemoryException 대신 발생합니다. 중심점은 기본적으로 전달된 점들의 질량 중심으로 계산됩니다. 사용자는 이후에 이 점을 변경할 수 있습니다. 포커스 스케일은 기본적으로 빈 점 (0.0, 0.0)입니다.

### 또 보기

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


