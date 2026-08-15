---
title: "Matrix 클래스"
type: docs
weight: 3000
url: /ko/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Matrix()](#Matrix__1) | Matrix 클래스를 단위 행렬로 새로운 인스턴스를 초기화합니다. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | 새로운 [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스 인스턴스를 초기화합니다. |
| [Matrix(origin)](#Matrix_origin_3) | [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스의 복사본을 만듭니다. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 새로운 [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스 인스턴스를 초기화합니다. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 새로운 [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | 이 플래그 비트는 이 객체에 의해 정의된 변환이<br/>            일부 축을 기준으로 거울 이미지 플립을 수행하여<br/>            일반적인 오른손 좌표계를 왼손 좌표계로 바꾸며<br/>            다른 플래그 비트가 나타내는 변환에 추가됩니다.<br/>            오른손 좌표계는 양의 X축이 반시계 방향으로 회전하여 양의 Y축 위에 겹치는 형태이며,<br/>            이는 오른손의 엄지를 바라볼 때 손가락이 말리는 방향과 유사합니다.<br/>            왼손 좌표계는 양의 X축이 시계 방향으로 회전하여 양의 Y축 위에 겹치는 형태이며,<br/>            이는 왼손의 손가락이 말리는 방향과 유사합니다.<br/>            적절한 보정 회전을 적용하면 모든 플립 각도가 동일해지기 때문에<br/>            원래의 플립 또는 미러링 변환 각도를 수학적으로 결정할 방법이 없습니다.<br/>            참고: TypeFlip은 GENERAL_TRANSFORM이 공개된 후에 추가되었으며,<br/>            플래그 비트를 편리하게 다시 번호 매기기 위해 외부 코드와의 이진 호환성을 깨뜨릴 수 없었습니다. |
| TYPE_GENERAL_ROTATION [static] | int | r | 이 플래그 비트는 이 객체에 의해 정의된 변환이<br/>            임의의 각도로 회전을 수행하며, 다른 플래그 비트가 나타내는 변환에 추가됩니다.<br/>            회전은 벡터의 원래 방향에 관계없이 동일한 양만큼 벡터의 각도를 변경하고,<br/>            벡터의 길이는 변경하지 않습니다.<br/>            이 플래그 비트는 다음과 상호 배타적입니다: |
| TYPE_GENERAL_SCALE [static] | int | r | 일반 스케일은 x 및 y 방향에서 서로 다른 양만큼 벡터의 길이를 곱하지만,<br/>            수직 벡터 사이의 각도는 변경하지 않습니다.<br/>            이 플래그 비트는 TypeUniformScale 플래그와 상호 배타적입니다. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | 이 상수는 이 객체에 의해 정의된 변환이 입력 좌표를 임의로 변환함을 나타냅니다.<br/>            이 변환이 위의 상수 중 하나로 분류될 수 있다면,<br/>            유형은 TypeIdentity 상수이거나,<br/>            이 변환이 수행하는 다양한 좌표 변환에 대한 적절한 플래그 비트들의 조합이 됩니다. |
| TYPE_IDENTITY [static] | int | r | 아이덴티티 변환은 출력 좌표가 항상 입력 좌표와 동일한 변환을 말합니다.<br/>            이 변환이 아이덴티티 변환이 아닌 경우,<br/>            유형은 상수 GENERAL_TRANSFORM이거나,<br/>            이 변환이 수행하는 다양한 좌표 변환에 대한 적절한 플래그 비트들의 조합이 됩니다. |
| TYPE_MASK_ROTATION [static] | int | r | 이 상수는 회전 플래그 비트 중 어느 것이든 적용되는 비트 마스크입니다. |
| TYPE_MASK_SCALE [static] | int | r | 이 상수는 스케일 플래그 비트 중 어느 것이든 적용되는 비트 마스크입니다. |
| TYPE_QUADRANT_ROTATION [static] | int | r | 이 플래그 비트는 이 객체에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환에 추가하여 90도 배수만큼의 사분면 회전을 수행함을 나타냅니다.<br/>            회전은 벡터의 원래 방향에 관계없이 동일한 양만큼 벡터의 각도를 변경하고, 벡터의 길이는 변경하지 않습니다.<br/>            이 플래그 비트는 TypeGeneralRotation 플래그와 상호 배타적입니다. |
| TYPE_TRANSLATION [static] | int | r | 평행 이동은 x와 y 방향으로 일정한 양만큼 좌표를 이동시키며, 벡터의 길이와 각도는 변경하지 않습니다. |
| TYPE_UNIFORM_SCALE [static] | int | r | 균일 스케일은 x와 y 방향 모두에서 동일한 양만큼 벡터의 길이를 곱하지만, 벡터 사이의 각도는 변경하지 않습니다.<br/>            이 플래그 비트는 TypeGeneralScale 플래그와 상호 배타적입니다. |
| elements | float | r | 이 [Matrix](/psd/python-net/aspose.psd/matrix/)의 요소를 나타내는 부동 소수점 값 배열을 가져옵니다. |
| m11 | float | r | 첫 번째 행 첫 번째 열에 있는 행렬 요소를 가져옵니다. X 축 방향의 스케일을 나타냅니다. |
| m12 | float | r | 첫 번째 행 두 번째 열에 있는 행렬 요소를 가져옵니다. Y 축 방향의 전단을 나타냅니다. |
| m21 | float | r | 두 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 전단을 나타냅니다. |
| m22 | float | r | 두 번째 행 두 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 스케일을 나타냅니다. |
| m31 | float | r | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 변환을 나타냅니다. |
| m32 | float | r | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 변환을 나타냅니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_elements()](#get_elements__1) | 행렬 요소의 복사본을 가져옵니다. |
| [multiply(tx)](#multiply_tx_2) | 이 Matrix에 매개변수인 matrix에 지정된 행렬을 (default) Prepend 순서를 사용하여 곱합니다. |
| [multiply(tx, order)](#multiply_tx_order_3) | 이 Matrix에 매개변수인 matrix에 지정된 행렬을 곱하고, order 매개변수에 지정된 순서대로 수행합니다. |
| reset() | 이 Matrix를 단위 행렬의 요소를 갖도록 재설정합니다. |
| [rotate(angle)](#rotate_angle_4) | 이 Matrix에 대해 기본 (Prepend) 순서로, angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용하며, 원점(좌표 x와 y가 0) 주변에서 회전합니다. |
| [rotate(angle, order)](#rotate_angle_order_5) | 이 Matrix에 대해 지정된 순서로, angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용하며, 원점(좌표 x와 y가 0) 주변에서 회전합니다. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | 지정된 점을 중심으로 이 Matrix에 시계 방향 회전을 기본 (Prepend) 순서로 적용합니다. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | 지정된 점을 중심으로 이 Matrix에 시계 방향 회전을 지정된 순서로 적용합니다. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | 지정된 스케일 벡터(scaleX 및 scaleY)를 이 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 순서를 사용하여 적용합니다. |
| [scale(sx, sy)](#scale_sx_sy_9) | 지정된 스케일 벡터(scaleX 및 scaleY)를 이 Matrix에 (default) Prepend 순서를 사용하여 적용합니다. |
| [transform_points(points)](#transform_points_points_10) | 이 [Matrix](/psd/python-net/aspose.psd/matrix/)가 나타내는 기하학적 변환을 지정된 점 배열에 적용합니다. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | 지정된 변환 벡터를 이 Matrix에 지정된 순서로 적용합니다. |
| [translate(tx, ty)](#translate_tx_ty_12) | 지정된 변환 벡터를 이 [Matrix](/psd/python-net/aspose.psd/matrix/)에 (default) Prepend 순서를 사용하여 적용합니다. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Matrix 클래스를 단위 행렬로 새로운 인스턴스를 초기화합니다.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

새로운 [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| m11 | float | m00     M11     Scale X |
| m12 | float | m10     M12     Shear Y |
| m21 | float | m01     M21     Shear X |
| m22 | float | m11     M22     Scale Y |
| m31 | float | m02     M31     Translate X |
| m32 | float | m12     M32     Y 변환 |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) 클래스의 복사본을 만듭니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | 복사를 위한 기본 행렬 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 새로운 [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 변환될 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체 |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | 상단 왼쪽, 상단 오른쪽 및 하단 왼쪽 모서리를 변환할 평행사변형의 점을 나타내는 세 개의 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열입니다. 평행사변형의 오른쪽 하단 모서리는 처음 세 모서리로부터 암시됩니다. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 새로운 [Matrix](/psd/python-net/aspose.psd/matrix/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 변환될 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체 |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | 상단 왼쪽, 상단 오른쪽 및 하단 왼쪽 모서리를 변환할 평행사변형의 점을 나타내는 세 개의 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열입니다. 평행사변형의 오른쪽 하단 모서리는 처음 세 모서리로부터 암시됩니다. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

행렬 요소의 복사본을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| float | 행렬 요소 복사본. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

이 Matrix에 매개변수인 matrix에 지정된 행렬을 (default) Prepend 순서를 사용하여 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | 곱셈에 사용할 행렬. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

이 Matrix에 매개변수인 matrix에 지정된 행렬을 곱하고, order 매개변수에 지정된 순서대로 수행합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | tx. tx. tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 순서. 순서. 순서. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

이 Matrix에 대해 기본 (Prepend) 순서로, angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용하며, 원점(좌표 x와 y가 0) 주변에서 회전합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

이 Matrix에 대해 지정된 순서로, angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용하며, 원점(좌표 x와 y가 0) 주변에서 회전합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 행렬 순서. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

지정된 점을 중심으로 이 Matrix에 시계 방향 회전을 기본 (Prepend) 순서로 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 각도. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 포인트. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

지정된 점을 중심으로 이 Matrix에 시계 방향 회전을 지정된 순서로 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 각도. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 포인트. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 순서. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

지정된 스케일 벡터(scaleX 및 scaleY)를 이 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 순서를 사용하여 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scale_x | float | 스케일 X. |
| scale_y | float | 스케일 Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 순서. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

지정된 스케일 벡터(scaleX 및 scaleY)를 이 Matrix에 (default) Prepend 순서를 사용하여 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

이 [Matrix](/psd/python-net/aspose.psd/matrix/)가 나타내는 기하학적 변환을 지정된 점 배열에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 점들. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

지정된 변환 벡터를 이 Matrix에 지정된 순서로 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| offset_x | float | 오프셋 X. |
| offset_y | float | 오프셋 Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 순서. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

지정된 변환 벡터를 이 [Matrix](/psd/python-net/aspose.psd/matrix/)에 (default) Prepend 순서를 사용하여 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

