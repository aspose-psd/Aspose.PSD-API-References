---
title: Class TextureBrush
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Brushes.TextureBrush 수업. 각 속성은TextureBrush 수업은Brush 도형의 내부를 채우기 위해 이미지를 사용하는 객체. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 210
url: /ko/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

각 속성은`TextureBrush` 수업은[`Brush`](../../aspose.psd/brush/) 도형의 내부를 채우기 위해 이미지를 사용하는 객체. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class TextureBrush : TransformBrush
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | 의 새 인스턴스를 초기화합니다.`TextureBrush` 지정된 이미지를 사용하는 클래스. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | 의 새 인스턴스를 초기화합니다.`TextureBrush` 지정된 이미지와 경계 사각형을 사용하는 클래스. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | 의 새 인스턴스를 초기화합니다.`TextureBrush` 지정된 이미지와 경계 사각형을 사용하는 클래스. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | 의 새 인스턴스를 초기화합니다.`TextureBrush` 지정된 이미지와 랩 모드를 사용하는 클래스. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | 의 새 인스턴스를 초기화합니다.`TextureBrush` 지정된 이미지, 경계 사각형 및 이미지 속성을 사용하는 클래스입니다. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | 의 새 인스턴스를 초기화합니다.`TextureBrush` 지정된 이미지, 경계 사각형 및 이미지 속성을 사용하는 클래스입니다. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | 의 새 인스턴스를 초기화합니다.`TextureBrush`지정된 이미지, 랩 모드 및 경계 사각형을 사용하는 클래스입니다. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | 의 새 인스턴스를 초기화합니다.`TextureBrush`지정된 이미지, 랩 모드 및 경계 사각형을 사용하는 클래스입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | 가져오기[`Image`](../../aspose.psd/image/) 이것과 관련된 객체`TextureBrush` object. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | 가져오기[`ImageAttributes`](./imageattributes/) 이와 관련된`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | 가져오기[`Rectangle`](../../aspose.psd/rectangle/) 이와 관련된`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 어떤 식으로든 변환이 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나 변환 행렬을 변경하는 메서드를 호출합니다. 이 속성은 GDI+. 와의 하위 호환성을 위해 도입되었습니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 값이 0이면 브러시가 완전히 표시되고 값이 1이면 브러시가 완전히 불투명합니다. |
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

### 또한보십시오

* class [TransformBrush](../transformbrush/)
* 네임스페이스 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 집회 [Aspose.PSD](../../)


