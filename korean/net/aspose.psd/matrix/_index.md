---
title: "클래스 Matrix"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Matrix 클래스. GDI Matrix를 대체합니다"
type: docs
weight: 5580
url: /ko/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

GDI+ 매트릭스를 대체합니다.

```csharp
public class Matrix
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Matrix](matrix/#constructor)() | Matrix 클래스를 항등 행렬로 초기화합니다. |
| [Matrix](matrix/#constructor_1)(Matrix) | `Matrix` 클래스의 복사본을 만듭니다. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | 지정된 사각형 및 점 배열에 의해 정의된 기하 변환으로 `Matrix` 클래스의 새 인스턴스를 초기화합니다. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | 지정된 사각형 및 점 배열에 의해 정의된 기하 변환으로 `Matrix` 클래스의 새 인스턴스를 초기화합니다. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | `Matrix` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | 이 `Matrix`의 요소를 나타내는 부동 소수점 값 배열을 가져옵니다. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | 첫 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 스케일을 나타냅니다. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | 첫 번째 행 두 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 전단을 나타냅니다. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | 두 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 전단을 나타냅니다. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | 두 번째 행 두 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 스케일을 나타냅니다. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 변환을 나타냅니다. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 변환을 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | 지정된 Object가 이 인스턴스와 같은지 여부를 판단합니다. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | 행렬 요소의 복사본을 가져옵니다. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | 이 Matrix에 matrix 매개변수에 지정된 행렬을 (기본) Prepend 순서로 곱합니다. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | 이 Matrix에 matrix 매개변수에 지정된 행렬을 곱하고, order 매개변수에 지정된 순서대로 수행합니다. |
| [Reset](../../aspose.psd/matrix/reset/)() | 이 Matrix를 항등 행렬의 요소로 재설정합니다. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | 이 Matrix에 대해 기본 (Prepend) 순서로 원점(좌표 x와 y가 0인 위치) 주위를 각도 매개변수에 지정된 양만큼 시계 방향으로 회전시킵니다. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | 이 Matrix에 대해 지정된 순서로 원점(좌표 x와 y가 0인 위치) 주위를 각도 매개변수에 지정된 양만큼 시계 방향으로 회전시킵니다. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | 이 Matrix에 대해 기본 (Prepend) 순서로 지정된 점을 중심으로 시계 방향으로 회전시킵니다. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 이 Matrix에 대해 지정된 순서로 지정된 점을 중심으로 시계 방향으로 회전시킵니다. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | 이 Matrix에 (기본) Prepend 순서를 사용하여 지정된 스케일 벡터(scaleX 및 scaleY)를 적용합니다. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | 이 `Matrix`에 지정된 순서를 사용하여 지정된 스케일 벡터(scaleX 및 scaleY)를 적용합니다. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | 이 `Matrix`가 나타내는 기하 변환을 지정된 점 배열에 적용합니다. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | 이 `Matrix`에 (기본) Prepend 순서를 사용하여 지정된 변환 벡터를 적용합니다. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | 이 Matrix에 지정된 순서로 지정된 변환 벡터를 적용합니다. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | 두 행렬이 같은지 여부를 결정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | 이 플래그 비트는 이 객체가 정의한 변환이 다른 플래그 비트가 나타내는 변환에 추가로, 일부 축을 기준으로 거울 이미지 플립을 수행하여 일반적인 오른손 좌표계를 왼손 좌표계로 변경함을 나타냅니다. 오른손 좌표계는 양의 X 축이 반시계 방향으로 회전하여 양의 Y 축과 겹치는 형태이며, 이는 엄지를 정면에서 바라볼 때 오른손의 손가락이 말리는 방향과 유사합니다. 왼손 좌표계는 양의 X 축이 시계 방향으로 회전하여 양의 Y 축과 겹치는 형태이며, 이는 왼손의 손가락이 말리는 방향과 유사합니다. 적절한 보정 회전을 적용하면 모든 플립 각도가 동일해지므로 원래 플립 또는 미러링 변환의 각도를 수학적으로 구할 방법이 없습니다. NOTE: TypeFlip은 GENERAL_TRANSFORM이 공개된 이후에 추가되었으며, 플래그 비트를 편리하게 다시 번호 매기기 하면 외부 코드와의 바이너리 호환성이 깨지게 됩니다. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | 이 플래그 비트는 이 객체가 정의한 변환이 다른 플래그 비트가 나타내는 변환에 추가로 임의의 각도만큼 회전을 수행함을 나타냅니다. 회전은 벡터의 원래 방향에 관계없이 모든 벡터의 각도를 동일하게 변경하며 벡터의 길이는 변하지 않습니다. 이 플래그 비트는 the와 상호 배타적입니다. |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | 일반 스케일은 x와 y 방향에서 서로 다른 비율로 벡터의 길이를 곱하여, 직교 벡터 사이의 각도는 변경하지 않습니다. 이 플래그 비트는 TypeUniformScale 플래그와 상호 배타적입니다. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | 이 상수는 이 객체가 정의한 변환이 입력 좌표에 대한 임의의 변환을 수행함을 나타냅니다. 이 변환이 위의 상수 중 하나로 분류될 수 있는 경우, 유형은 상수 TypeIdentity이 되거나 이 변환이 수행하는 다양한 좌표 변환에 대한 적절한 플래그 비트들의 조합이 됩니다. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | 아이덴티티 변환은 출력 좌표가 항상 입력 좌표와 동일한 변환을 말합니다. 이 변환이 아이덴티티 변환이 아닌 경우, 유형은 상수 GENERAL_TRANSFORM이 되거나 이 변환이 수행하는 다양한 좌표 변환에 대한 적절한 플래그 비트들의 조합이 됩니다. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | 이 상수는 회전 플래그 비트 중 어느 것이든 적용할 수 있는 비트 마스크입니다. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | 이 상수는 스케일 플래그 비트 중 어느 것이든 적용할 수 있는 비트 마스크입니다. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | 이 플래그 비트는 이 객체가 정의한 변환이 다른 플래그 비트가 나타내는 변환에 추가로 90도씩의 배수만큼 사분면 회전을 수행함을 나타냅니다. 회전은 벡터의 원래 방향에 관계없이 모든 벡터의 각도를 동일하게 변경하며 벡터의 길이는 변하지 않습니다. 이 플래그 비트는 TypeGeneralRotation 플래그와 상호 배타적입니다. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | 변환은 x와 y 방향으로 좌표를 일정량 이동시키며, 벡터의 길이와 각도는 변경하지 않습니다. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | 균일 스케일은 x와 y 방향 모두에서 벡터의 길이를 동일한 비율로 곱하여, 벡터 간의 각도는 변경하지 않습니다. 이 플래그 비트는 TypeGeneralScale 플래그와 상호 배타적입니다. |

## 비고

대부분의 알고리즘은 Sun의 AffineTransform.java에서 가져왔습니다. 내부에서 사용되는 행렬 요소의 Java 이름입니다. Java 이름을 .NET 이름 및 설명에 매핑한 표: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


