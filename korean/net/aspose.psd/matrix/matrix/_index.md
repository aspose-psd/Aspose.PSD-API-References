---
title: "Matrix.Matrix"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Matrix 생성자. Matrix 클래스를 단위 행렬로 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Matrix 클래스를 항등 행렬로 초기화합니다.

```csharp
public Matrix()
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

[`Matrix`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m11 | 단일 | m00 M11 Scale X |
| m12 | 단일 | m10 M12 Shear Y |
| m21 | 단일 | m01 M21 Shear X |
| m22 | 단일 | m11 M22 Y축 스케일 |
| m31 | 단일 | m02 M31 X축 변환 |
| m32 | 단일 | m12 M32 Y축 변환 |

### 또 보기

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 [`Matrix`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | RectangleF | 변환될 사각형을 나타내는 [`RectangleF`](../../rectanglef/) 구조체입니다. |
| plgpts | PointF[] | 세 개의 [`PointF`](../../pointf/) 구조체 배열로, 사각형의 왼쪽 위, 오른쪽 위 및 왼쪽 아래 모서리가 변환될 평행사변형의 점들을 나타냅니다. 평행사변형의 오른쪽 아래 모서리는 첫 번째 세 모서리로부터 암시됩니다. |

### 또 보기

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

지정된 사각형 및 점 배열에 의해 정의된 기하학적 변환으로 [`Matrix`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 변환될 사각형을 나타내는 [`Rectangle`](../../rectangle/) 구조체입니다. |
| plgpts | Point[] | 세 개의 [`Point`](../../point/) 구조체 배열로, 사각형의 왼쪽 위, 오른쪽 위 및 왼쪽 아래 모서리가 변환될 평행사변형의 점들을 나타냅니다. 평행사변형의 오른쪽 아래 모서리는 첫 번째 세 모서리로부터 암시됩니다. |

### 또 보기

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

[`Matrix`](../) 클래스의 복사본을 만듭니다.

```csharp
public Matrix(Matrix origin)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| origin | 행렬 | 복사를 위한 기본 행렬. |

### 또 보기

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


