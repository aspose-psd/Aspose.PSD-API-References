---
title: Class Matrix
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Matrix 수업. GDI 매트릭스를 대체합니다.
type: docs
weight: 5090
url: /ko/net/aspose.psd/matrix/
---
## Matrix class

GDI+ 매트릭스를 대체합니다.

```csharp
public class Matrix
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Matrix](matrix/#constructor)() | Matrix 클래스의 새 인스턴스를 항등 행렬로 초기화합니다. |
| [Matrix](matrix/#constructor_1)(Matrix) | 의 복사본을 만듭니다.`Matrix` 클래스. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | 의 새 인스턴스를 초기화합니다.`Matrix` 지정된 사각형과 포인트 배열로 정의된 기하학적 변환 클래스. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | 의 새 인스턴스를 초기화합니다.`Matrix` 지정된 사각형과 포인트 배열로 정의된 기하학적 변환 클래스. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | 의 새 인스턴스를 초기화합니다.`Matrix` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | 이 요소를 나타내는 부동 소수점 값의 배열을 가져옵니다.`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | 첫 번째 행 첫 번째 열에서 행렬 요소를 가져옵니다. X 축을 따라 축척을 나타냅니다. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | 첫 번째 행 두 번째 열에서 행렬 요소를 가져옵니다. Y 축을 따라 전단을 나타냅니다. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | 두 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 전단을 나타냅니다. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | 두 번째 행 두 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 배율을 나타냅니다. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 변환을 나타냅니다. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 변환을 나타냅니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | 지정된Object 이 인스턴스와 같습니다. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | 행렬 요소의 복사본을 가져옵니다. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | 이 행렬에 (기본값) Prepend order. 를 사용하여 행렬 매개 변수에 지정된 행렬을 곱합니다. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | 이 행렬에 행렬 매개 변수에 지정된 행렬을 order 매개 변수에 지정된 순서대로 곱합니다. |
| [Reset](../../aspose.psd/matrix/reset/)() | 항등 행렬의 요소를 갖도록 이 행렬을 재설정합니다. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | 기본(앞에 추가) 순서로 이 매트릭스의 원점(제로 x 및 y 좌표)을 기준으로 각도 매개변수에 지정된 양의 시계 방향 회전을 적용합니다. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | 지정된 순서로 이 매트릭스의 원점(제로 x 및 y 좌표)을 기준으로 각도 매개변수에 지정된 양의 시계 방향 회전을 적용합니다. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | 기본(앞에 추가) 순서로 이 매트릭스에 지정된 지점을 기준으로 시계 방향 회전을 적용합니다. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 지정된 순서로 이 매트릭스에 지정된 지점을 기준으로 시계 방향 회전을 적용합니다. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | 지정된 배율 벡터(scaleX 및 scaleY)를 (기본값) Prepend order. 를 사용하여 이 매트릭스에 적용합니다. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | 지정된 배율 벡터(scaleX 및 scaleY)를 여기에 적용합니다.`Matrix` 지정된 order. 사용 |
| override [ToString](../../aspose.psd/matrix/tostring/)() | 반환String 이 instance. 를 나타냅니다. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | 이 표시되는 기하학적 변환을 적용합니다.`Matrix` 포인트의 지정된 배열로. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | 지정된 변환 벡터를 여기에 적용합니다.`Matrix` (기본값) Prepend order. 사용 |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | 지정된 변환 벡터를 지정된 순서로 이 매트릭스에 적용합니다. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | 두 행렬이 같은지 여부를 결정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | 이 플래그 비트는 이 object 에 의해 정의된 변환이 다른 플래그 비트에 의해 표시된 변환 외에도 일반적으로 오른손 좌표계를 왼손 시스템으로 변경하는 일부 축에 대해 미러 이미지 플립을 수행함을 나타냅니다. 오른손 좌표계 이것은 양의 X 축이 시계 반대 방향으로 회전하여 양의 Y 축 를 오버레이하는 것입니다. 이는 오른손의 손가락 엄지손가락 끝을 응시할 때 말리는 방향과 유사합니다. 왼손 좌표계는 양의 X 축이 회전하는 좌표계입니다. 시계 방향으로 양의 Y 축과 유사한 를 왼손의 손가락이 말리는 방향으로 오버레이합니다. 뒤집기의 모든 각도 가 적절한 조정 회전이 주어지면 동일하기 때문에 원래 뒤집기 또는 미러링 변환의 각도를 결정하는 수학적 방법은 없습니다. 참고: TypeFlip은 GENERAL_TRANSFORM 다음에 추가되었습니다. public 순환 상태였으며 외부 코드에 이진 비호환성을 도입하지 않고 플래그 비트를 더 이상 편리하게 번호를 다시 매길 수 없습니다. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | 이 플래그 비트는 이 개체 에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환 외에 임의의 각도로 회전을 수행함을 나타냅니다. 및 without 벡터의 길이 변경. 이 플래그 비트는 the 와 상호 배타적입니다. |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | 일반 스케일은 수직 벡터 사이의 angle 를 변경하지 않고 x 및 y 방향으로 다른 양만큼 벡터의 길이를 곱합니다. 이 플래그 비트는 TypeUniformScale 플래그와 상호 배타적입니다. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | 이 상수는 이 object 에 의해 정의된 변형이 입력 좌표의 임의 변환을 수행함을 나타냅니다. 이 변환이 수행하는 다양한 coordinate 변환을 위한 비트. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | 항등 변환은 출력 좌표가 항상 입력 좌표와 동일한 변환입니다. 이 변환이 항등 변환이 아닌 경우 유형은 상수 GENERAL_TRANSFORM 또는 a 에 대한 적절한 플래그 비트의 조합입니다. 이 변환이 수행하는 다양한 coordinate 변환. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | 이 상수는 모든 회전 플래그 비트에 대한 비트 마스크입니다. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | 이 상수는 스케일 플래그 비트에 대한 비트 마스크입니다. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | 이 플래그 비트는 이 object 에 의해 정의된 변환이 다른 플래그 비트에 의해 표시된 변환에 추가하여 에서 90도의 배수만큼 사분면 회전을 수행함을 나타냅니다. 벡터의 길이를 변경하지 않고 벡터의 길이를 변경합니다. 이 플래그 비트는 TypeGeneralRotation 플래그와 상호 배타적입니다. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | 이동은 벡터의 길이나 각도를 변경하지 않고 x 및 y에서 일정한 양만큼 좌표를 이동합니다. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | 균일한 배율은 벡터 사이의 각도를 변경하지 않고 x 및 y 방향 모두에서 동일한 양 로 벡터의 길이를 곱합니다. 이 플래그 비트는 TypeGeneralScale 플래그와 상호 배타적입니다. |

### 비고

Sun의 AffineTransform.java에서 가져온 대부분의 알고리즘. 내부적으로 사용되는 행렬 요소에 대한 Java의 이름. Java 이름을 .net 이름과 설명으로 매핑: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scaled Y_m02 X 변환 m12 M32 Y 변환

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


