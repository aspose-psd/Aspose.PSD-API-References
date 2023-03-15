---
title: Matrix.Matrix
second_title: .NET API 참조용 Aspose.PSD
description: Matrix 건설자. Matrix 클래스의 새 인스턴스를 항등 행렬로 초기화합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd/matrix/matrix/
---
## Matrix() {#constructor}

Matrix 클래스의 새 인스턴스를 항등 행렬로 초기화합니다.

```csharp
public Matrix()
```

### 또한보십시오

* class [Matrix](../)
* 네임스페이스 [Aspose.PSD](../../matrix/)
* 집회 [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`Matrix`](../) 클래스.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| m11 | Single | m00 M11 스케일 X |
| m12 | Single | m10 M12 전단 Y |
| m21 | Single | m01 M21 쉬어 X |
| m22 | Single | m11 M22 스케일 Y |
| m31 | Single | m02 M31 번역 X |
| m32 | Single | m12 M32 Y 이동 |

### 또한보십시오

* class [Matrix](../)
* 네임스페이스 [Aspose.PSD](../../matrix/)
* 집회 [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`Matrix`](../) 지정된 사각형과 포인트 배열로 정의된 기하학적 변환 클래스.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rect | RectangleF | ㅏ[`RectangleF`](../../rectanglef/) 변환할 사각형을 나타내는 구조체입니다. |
| plgpts | PointF[] | 세 개의 배열[`PointF`](../../pointf/)사각형의 왼쪽 위, 오른쪽 위 및 왼쪽 아래 모서리가 변환될 평행사변형의 점을 나타내는 구조체입니다. 평행사변형의 오른쪽 아래 모서리는 처음 세 모서리에 의해 암시됩니다. |

### 또한보십시오

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* 네임스페이스 [Aspose.PSD](../../matrix/)
* 집회 [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`Matrix`](../) 지정된 사각형과 포인트 배열로 정의된 기하학적 변환 클래스.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | ㅏ[`Rectangle`](../../rectangle/) 변환할 사각형을 나타내는 구조체입니다. |
| plgpts | Point[] | 세 개의 배열[`Point`](../../point/)사각형의 왼쪽 위, 오른쪽 위 및 왼쪽 아래 모서리가 변환될 평행사변형의 점을 나타내는 구조체입니다. 평행사변형의 오른쪽 아래 모서리는 처음 세 모서리에 의해 암시됩니다. |

### 또한보십시오

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* 네임스페이스 [Aspose.PSD](../../matrix/)
* 집회 [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

의 복사본을 만듭니다.[`Matrix`](../) 클래스.

```csharp
public Matrix(Matrix origin)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| origin | Matrix | 대처를 위한 기본 매트릭스 |

### 또한보십시오

* class [Matrix](../)
* 네임스페이스 [Aspose.PSD](../../matrix/)
* 집회 [Aspose.PSD](../../../)


