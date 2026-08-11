---
title: "클래스 TextureBrush"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.TextureBrush 클래스. TextureBrush 클래스의 각 속성은 이미지를 사용하여 도형 내부를 채우는 Brush 객체입니다. 이 클래스는 상속할 수 없습니다."
type: docs
weight: 210
url: /ko/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

각 `TextureBrush` 클래스의 속성은 이미지를 사용하여 도형 내부를 채우는 [`Brush`](../../aspose.psd/brush/) 객체입니다. 이 클래스는 상속할 수 없습니다.

```csharp
public sealed class TextureBrush : TransformBrush
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | 지정된 이미지를 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | 지정된 이미지와 경계 사각형을 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | 지정된 이미지와 경계 사각형을 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | 지정된 이미지와 랩 모드를 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | 지정된 이미지, 경계 사각형 및 이미지 속성을 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | 지정된 이미지, 경계 사각형 및 이미지 속성을 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | 지정된 이미지, 랩 모드 및 경계 사각형을 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | 지정된 이미지, 랩 모드 및 경계 사각형을 사용하는 `TextureBrush` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | 이 `TextureBrush` 객체와 연결된 [`Image`](../../aspose.psd/image/) 객체를 가져옵니다. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | 이 `TextureBrush`와 연결된 [`ImageAttributes`](./imageattributes/)를 가져옵니다. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | 이 `TextureBrush`와 연결된 [`Rectangle`](../../aspose.psd/rectangle/)을 가져옵니다. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 변환이 어떤 방식으로든 변경되었는지를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 이전 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


