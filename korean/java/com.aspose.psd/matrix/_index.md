---
title: "Matrix"
second_title: "Java용 Aspose.PSD API 참조"
description: "GDI Matrix를 대체합니다."
type: docs
weight: 69
url: /ko/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

GDI+ Matrix를 교체합니다.

대부분의 알고리즘은 Sun의 AffineTransform.java에서 가져왔습니다. 내부에서 사용되는 행렬 요소에 대한 Java 이름입니다. Java 이름을 .NET 이름 및 설명에 매핑한 표: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix 클래스의 새 인스턴스를 항등 행렬로 초기화합니다. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Matrix 클래스의 새 인스턴스를 초기화합니다. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Matrix 클래스의 복사본을 만듭니다. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 Aspose.Imaging.Matrix 클래스의 새 인스턴스를 초기화합니다. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | 지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 Aspose.Imaging.Matrix 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | 이 플래그 비트는 이 객체에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환 외에도, 일반적으로 오른손 좌표계인 것을 왼손 좌표계로 변경하는 축을 기준으로 거울 이미지 플립을 수행함을 나타냅니다. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | 이 플래그 비트는 이 객체에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환에 추가로 임의 각도만큼 회전을 수행함을 나타냅니다. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | 일반 스케일은 직교 벡터 사이의 각도를 변경하지 않으면서 x 및 y 방향에서 벡터의 길이를 서로 다른 양만큼 곱합니다. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | 이 상수는 이 객체에 의해 정의된 변환이 입력 좌표를 임의로 변환함을 나타냅니다. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | 항등 변환은 출력 좌표가 항상 입력 좌표와 동일한 변환을 말합니다. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | 이 상수는 회전 플래그 비트 중 어느 하나에 대한 비트 마스크입니다. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | 이 상수는 스케일 플래그 비트 중 어느 하나에 대한 비트 마스크입니다. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | 이 플래그 비트는 이 객체에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환에 추가로 90도씩의 배수만큼 사분면 회전을 수행함을 나타냅니다. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | 평행 이동은 벡터의 길이와 각도를 변경하지 않으면서 x와 y 방향으로 좌표를 일정한 양만큼 이동시킵니다. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | 균일 스케일은 벡터 사이의 각도를 변경하지 않으면서 x와 y 방향 모두에서 동일한 양만큼 벡터의 길이를 곱합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된  System.Object  가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | 행렬 요소의 복사본을 가져옵니다. |
| [getM11()](#getM11--) | 첫 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. |
| [getM12()](#getM12--) | 첫 번째 행 두 번째 열의 행렬 요소를 가져옵니다. |
| [getM21()](#getM21--) | 두 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. |
| [getM22()](#getM22--) | 두 번째 행 두 번째 열의 행렬 요소를 가져옵니다. |
| [getM31()](#getM31--) | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. |
| [getM32()](#getM32--) | 세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | 두 행렬이 같은지 여부를 결정합니다. |
| [isIdentity()](#isIdentity--) | `AffineTransform`이 항등 변환이면 `true`를 반환합니다. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | 이 Matrix에 매개변수 matrix에 지정된 행렬을 (기본) Prepend 순서를 사용하여 곱합니다. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | 이 Matrix에 매개변수 matrix에 지정된 행렬을 곱하고, order 매개변수에 지정된 순서대로 수행합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 이 Matrix를 항등 행렬의 요소를 갖도록 재설정합니다. |
| [rotate(float angle)](#rotate-float-) | 이 Matrix에 대해 기본 (Prepend) 순서로, 원점(좌표 x와 y가 0) 주위에서 angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용합니다. |
| [rotate(float angle, int order)](#rotate-float-int-) | 이 Matrix에 대해 지정된 순서로, 원점(좌표 x와 y가 0) 주위에서 angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용합니다. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | 지정된 점을 중심으로 이 Matrix에 기본 (Prepend) 순서로 시계 방향 회전을 적용합니다. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | 지정된 점을 중심으로 이 Matrix에 지정된 순서로 시계 방향 회전을 적용합니다. |
| [scale(float sx, float sy)](#scale-float-float-) | 지정된 스케일 벡터(scaleX 및 scaleY)를 (기본) Prepend 순서를 사용하여 이 Matrix에 적용합니다. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 지정된 스케일 벡터(scaleX 및 scaleY)를 이 Matrix에 지정된 순서대로 적용합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는  System.String  을 반환합니다. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | 이 Matrix가 나타내는 기하학적 변환을 지정된 점 배열에 적용합니다. |
| [translate(float tx, float ty)](#translate-float-float-) | 지정된 변환 벡터를 (기본) Prepend 순서를 사용하여 이 Matrix에 적용합니다. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 지정된 변환 벡터를 지정된 순서대로 이 Matrix에 적용합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix 클래스의 새 인스턴스를 항등 행렬로 초기화합니다.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Matrix 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Matrix 클래스의 복사본을 만듭니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | 복사를 위한 기본 행렬 |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 Aspose.Imaging.Matrix 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 변환될 사각형을 나타내는 Aspose.Imaging.RectangleF 구조체입니다. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | 세 개의 Aspose.Imaging.PointF 구조체 배열로, 사각형의 왼쪽 위, 오른쪽 위 및 왼쪽 아래 모서리가 변환될 평행사변형의 점들을 나타냅니다. 평행사변형의 오른쪽 아래 모서는 처음 세 모서리에 의해 암시됩니다. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 Aspose.Imaging.Matrix 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 변환될 사각형을 나타내는 Aspose.Imaging.Rectangle 구조체입니다. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | 세 개의 Aspose.Imaging.Point 구조체 배열로, 사각형의 왼쪽 위, 오른쪽 위 및 왼쪽 아래 모서리가 변환될 평행사변형의 점들을 나타냅니다. 평행사변형의 오른쪽 아래 모서는 처음 세 모서리에 의해 암시됩니다. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


이 플래그 비트는 이 객체에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환에 추가로, 일반적으로 오른손 좌표계인 시스템을 왼손 좌표계로 바꾸는 축을 중심으로 거울 이미지 플립을 수행함을 나타냅니다. 오른손 좌표계는 양의 X축이 반시계 방향으로 회전하여 양의 Y축 위에 겹치는 형태이며, 이는 오른손의 엄지손가락을 정면에서 바라볼 때 손가락이 말리는 방향과 유사합니다. 왼손 좌표계는 양의 X축이 시계 방향으로 회전하여 양의 Y축 위에 겹치는 형태이며, 이는 왼손의 손가락이 말리는 방향과 유사합니다. 적절한 보정 회전을 적용하면 모든 플립 각도가 동일해지기 때문에 원래 플립 또는 미러 변환의 각도를 수학적으로 결정할 방법은 없습니다. NOTE: TypeFlip은 GENERAL\_TRANSFORM이 공개된 후에 추가되었으며, 플래그 비트를 편리하게 재번호화하면 외부 코드와의 이진 호환성이 깨질 수 있습니다.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


이 플래그 비트는 이 객체에 의해 정의된 변환이 다른 플래그 비트가 나타내는 변환에 추가로 임의 각도만큼 회전을 수행함을 나타냅니다. 회전은 벡터의 원래 방향에 관계없이 벡터의 각도를 동일하게 변경하며 벡터의 길이는 변하지 않습니다. 이 플래그 비트는 다음과 상호 배타적입니다.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


일반 스케일은 x 및 y 방향에서 벡터의 길이를 서로 다른 양으로 곱하지만, 직교 벡터 사이의 각도는 변경하지 않습니다. 이 플래그 비트는 TypeUniformScale 플래그와 상호 배타적입니다.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


이 상수는 이 객체에 의해 정의된 변환이 입력 좌표의 임의 변환을 수행함을 나타냅니다. 이 변환이 위의 상수 중 하나로 분류될 수 있다면, 유형은 TypeIdentity 상수이거나 이 변환이 수행하는 다양한 좌표 변환에 대한 적절한 플래그 비트의 조합이 됩니다.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


항등 변환은 출력 좌표가 항상 입력 좌표와 동일한 경우를 말합니다. 이 변환이 항등 변환이 아닌 경우, 유형은 상수 GENERAL\_TRANSFORM이거나 이 변환이 수행하는 다양한 좌표 변환에 대한 적절한 플래그 비트들의 조합이 됩니다.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


이 상수는 회전 플래그 비트 중 어느 하나에 대한 비트 마스크입니다.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


이 상수는 스케일 플래그 비트 중 어느 하나에 대한 비트 마스크입니다.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


이 플래그 비트는 이 객체가 정의한 변환이 다른 플래그 비트가 나타내는 변환에 추가하여 90도씩 여러 배수만큼 사분면 회전을 수행함을 나타냅니다. 회전은 벡터의 원래 방향에 관계없이 동일한 각도로 벡터의 각도를 변경하고 벡터의 길이는 변경하지 않습니다. 이 플래그 비트는 TypeGeneralRotation 플래그와 상호 배타적입니다.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


평행 이동은 벡터의 길이와 각도를 변경하지 않으면서 x와 y 방향으로 좌표를 일정한 양만큼 이동시킵니다.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


균일 스케일은 x 및 y 방향 모두에서 벡터의 길이를 동일한 비율로 곱하며 벡터 사이의 각도는 변경하지 않습니다. 이 플래그 비트는 TypeGeneralScale 플래그와 상호 배타적입니다.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된  System.Object  가 이 인스턴스와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object. |

**Returns:**
boolean - 지정된 System.Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


행렬 요소의 복사본을 가져옵니다.

**Returns:**
float[] - 행렬 요소 복사.
### getM11() {#getM11--}
```
public float getM11()
```


첫 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 스케일을 나타냅니다.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


첫 번째 행 두 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 전단을 나타냅니다.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


두 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 전단을 나타냅니다.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


두 번째 행 두 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 스케일을 나타냅니다.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. X 축을 따라 변환을 나타냅니다.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


세 번째 행 첫 번째 열의 행렬 요소를 가져옵니다. Y 축을 따라 변환을 나타냅니다.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


두 행렬이 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | 비교할 첫 번째 행렬. |
| b | [Matrix](../../com.aspose.psd/matrix) | 비교할 두 번째 행렬. |

**Returns:**
boolean - 행렬이 동일하면 True.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


`AffineTransform`이 항등 변환이면 `true`를 반환합니다.

**Returns:**
boolean - `true`이면 이 `AffineTransform`이 항등 변환이며, 그렇지 않으면 `false`.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


이 Matrix에 매개변수 matrix에 지정된 행렬을 (기본) Prepend 순서를 사용하여 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | 곱할 행렬. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


이 Matrix에 매개변수 matrix에 지정된 행렬을 곱하고, order 매개변수에 지정된 순서대로 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | 그 tx. 그 tx. 그 tx. |
| order | int | 그 order. 그 order. 그 order. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


이 Matrix를 항등 행렬의 요소를 갖도록 재설정합니다.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


이 Matrix에 대해 기본 (Prepend) 순서로, 원점(좌표 x와 y가 0) 주위에서 angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 그 회전 각도. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


이 Matrix에 대해 지정된 순서로, 원점(좌표 x와 y가 0) 주위에서 angle 매개변수에 지정된 양만큼 시계 방향 회전을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 그 회전 각도. |
| order | int | 그 행렬 순서. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


지정된 점을 중심으로 이 Matrix에 기본 (Prepend) 순서로 시계 방향 회전을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 그 각도. |
| point | [PointF](../../com.aspose.psd/pointf) | 포인트. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


지정된 점을 중심으로 이 Matrix에 지정된 순서로 시계 방향 회전을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 그 각도. |
| point | [PointF](../../com.aspose.psd/pointf) | 포인트. |
| order | int | 그 순서. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


지정된 스케일 벡터(scaleX 및 scaleY)를 (기본) Prepend 순서를 사용하여 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | 그 sx. 그 sx. 그 sx. |
| sy | float | 그 sy. 그 sy. 그 sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


지정된 스케일 벡터(scaleX 및 scaleY)를 이 Matrix에 지정된 순서대로 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | float | X 배율입니다. |
| scaleY | float | Y 배율입니다. |
| order | int | 그 순서. |

### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는  System.String  을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 System.String.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


이 Matrix가 나타내는 기하학적 변환을 지정된 점 배열에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 그 점들. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


지정된 변환 벡터를 (기본) Prepend 순서를 사용하여 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tx | float | 그 tx. 그 tx. 그 tx. |
| ty | float | 그 ty. 그 ty. 그 ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


지정된 변환 벡터를 지정된 순서대로 이 Matrix에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| offsetX | float | 그 offset X. |
| offsetY | float | 그 offset Y. |
| order | int | 그 순서. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

