---
title: Class PathGradientBrushBase
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Brushes.PathGradientBrushBase 수업. 는Brush 기본 경로 그래디언트 기능 포함.
type: docs
weight: 180
url: /ko/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

는[`Brush`](../../aspose.psd/brush/) 기본 경로 그래디언트 기능 포함.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 경로 그라데이션의 중심점을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 그래디언트 폴오프의 초점 포인트를 가져오거나 설정합니다. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 이 브러시가 빌드된 그래픽 경로를 가져옵니다. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 어떤 식으로든 변환이 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출합니다. 이 속성은 GDI+. 와의 하위 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 값이 0이면 브러시가 완전히 표시되고 값이 1이면 브러시가 완전히 불투명합니다. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | 이 브러시가 빌드된 경로 지점을 가져옵니다. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 복사본을 가져오거나 설정합니다.[`Matrix`](../../aspose.psd/matrix/) 이에 대한 로컬 기하학적 변환을 정의합니다.[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | 가져오거나 설정합니다.[`WrapMode`](../../aspose.psd/wrapmode/) 이것에 대한 래핑 모드를 나타내는 열거[`TransformBrush`](../transformbrush/) . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재의 새로운 딥 클론을 생성합니다.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | 곱하기[`Matrix`](../../aspose.psd/matrix/) 이것은 이것의 국지적 기하학적 변환을 나타냅니다.[`LinearGradientBrush`](../lineargradientbrush/) 지정된[`Matrix`](../../aspose.psd/matrix/) 지정된[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 곱하기[`Matrix`](../../aspose.psd/matrix/) 이것은 이것의 국지적 기하학적 변환을 나타냅니다.[`LinearGradientBrush`](../lineargradientbrush/) 지정된[`Matrix`](../../aspose.psd/matrix/) 지정된 order. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | 재설정[`Transform`](../transformbrush/transform/) 신원에 재산. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 로컬 기하 변환을 지정된 양만큼 회전합니다. 이 방법은 변환 앞에 회전을 추가합니다. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 지정된 순서로 지정된 양만큼 로컬 기하 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 지정된 양만큼 로컬 기하 변환의 크기를 조정합니다. 이 방법은 스케일링 행렬을 transform. 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 지정된 순서로 지정된 양만큼 로컬 기하 변환을 확장합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 지정된 치수로 로컬 기하 변환을 변환합니다. 이 방법은 변환을 transform. 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 지정된 순서로 지정된 치수로 로컬 기하 변환을 변환합니다. |

### 비고

생성할 때`PathGradientBrushBase` 클래스는 최소 2포인트로 초기화되어야 합니다. 내부 경로 created 는 항상 닫힌 그림이 될 것이며 마지막 점이 첫 번째 점을 연결합니다. 그 모양은 이것으로 채워져`PathGradientBrushBase`. GDI+ 구현은OutOfMemoryException 동일한 좌표를 갖는 빈 배열 또는 포인트 세트를 전달할 때. The`PathGradientBrushBase` 포인트 배열에 2개 미만의 포인트가 포함된 경우 예외가 발생합니다.ArgumentException is 가 아닌OutOfMemoryException 점 배열이 허용되지 않는 경우. 중심점은 기본적으로 전달된 점의 질량 중심으로 계산됩니다. 사용자는 나중에 이 포인트를 변경할 수 있습니다. 포커스 스케일은 기본적으로 빈 포인트(0.0, 0.0)입니다.

### 또한보십시오

* class [TransformBrush](../transformbrush/)
* 네임스페이스 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 집회 [Aspose.PSD](../../)


