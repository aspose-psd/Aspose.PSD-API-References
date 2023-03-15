---
title: Color.FromArgb
second_title: .NET API 참조용 Aspose.PSD
description: Color 방법. 생성Color 32비트 ARGB 값의 구조.
type: docs
weight: 1430
url: /ko/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

생성[`Color`](../) 32비트 ARGB 값의 구조.

```csharp
public static Color FromArgb(int argb)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| argb | Int32 | 32비트 ARGB 값을 지정하는 값입니다. |

### 반환 값

그만큼[`Color`](../) 이 메소드가 생성하는 구조.

### 또한보십시오

* struct [Color](../)
* 네임스페이스 [Aspose.PSD](../../color/)
* 집회 [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

생성[`Color`](../) 4개의 ARGB 구성 요소(알파, 빨강, 녹색 및 파랑) 값의 구조. 이 방법을 사용하면 각 구성 요소에 대해 32비트 값을 전달할 수 있지만 각 구성 요소의 값은 8비트로 제한됩니다.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | Int32 | 알파 구성 요소입니다. 유효한 값은 0에서 255까지입니다. |
| red | Int32 | 빨간색 구성 요소입니다. 유효한 값은 0에서 255까지입니다. |
| green | Int32 | 녹색 구성 요소입니다. 유효한 값은 0에서 255까지입니다. |
| blue | Int32 | 파란색 구성 요소입니다. 유효한 값은 0에서 255까지입니다. |

### 반환 값

그만큼[`Color`](../) 이 메서드가 만드는 것입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , 또는*blue* 0보다 작거나 255보다 큽니다. |

### 또한보십시오

* struct [Color](../)
* 네임스페이스 [Aspose.PSD](../../color/)
* 집회 [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

생성[`Color`](../) 지정된 구조[`Color`](../) 구조이지만 새로 지정된 알파 값을 사용합니다. 이 방법을 사용하면 알파 값으로 32비트 값을 전달할 수 있지만 값은 8비트로 제한됩니다.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | Int32 | 새로운 알파 값[`Color`](../). 유효한 값은 0에서 255까지입니다. |
| baseColor | Color | 그만큼[`Color`](../) 새로운 것을 만드는 것으로부터[`Color`](../). |

### 반환 값

그만큼[`Color`](../) 이 메서드가 만드는 것입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 0보다 작거나 255보다 큽니다. |

### 또한보십시오

* struct [Color](../)
* 네임스페이스 [Aspose.PSD](../../color/)
* 집회 [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

생성[`Color`](../) 지정된 8비트 색상 값(빨간색, 녹색 및 파란색)의 구조. 알파 값은 암시적으로 255(완전 불투명)입니다. 이 방법을 사용하면 각 색상 구성 요소에 대해 32비트 값을 전달할 수 있지만 각 구성 요소의 값은 8비트로 제한됩니다.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| red | Int32 | 새 항목에 대한 빨간색 구성 요소 값[`Color`](../). 유효한 값은 0에서 255까지입니다. |
| green | Int32 | 새 제품의 녹색 구성 요소 값[`Color`](../). 유효한 값은 0에서 255까지입니다. |
| blue | Int32 | 새 항목에 대한 파란색 구성 요소 값[`Color`](../). 유효한 값은 0에서 255까지입니다. |

### 반환 값

그만큼[`Color`](../) 이 메서드가 만드는 것입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , 또는*blue* 0보다 작거나 255보다 큽니다. |

### 또한보십시오

* struct [Color](../)
* 네임스페이스 [Aspose.PSD](../../color/)
* 집회 [Aspose.PSD](../../../)


