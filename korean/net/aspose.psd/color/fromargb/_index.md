---
title: "Color.FromArgb"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Color 메서드. 32비트 ARGB 값으로 Color 구조체를 생성합니다."
type: docs
weight: 1430
url: /ko/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

이 [`Color`](../) 구조체를 32비트 ARGB 값으로 생성합니다.

```csharp
public static Color FromArgb(int argb)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb | Int32 | 32비트 ARGB 값을 지정하는 값입니다. |

### 반환 값

이 메서드가 생성하는 [`Color`](../) 구조체입니다.

### 또 보기

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

`[`Color`](../)` 구조체를 네 개의 ARGB 구성 요소(alpha, red, green, and blue) 값으로 생성합니다. 이 메서드는 각 구성 요소에 32비트 값을 전달할 수 있도록 허용하지만, 각 구성 요소의 값은 8비트로 제한됩니다.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alpha | Int32 | 알파 구성 요소. 유효한 값은 0부터 255까지입니다. |
| 빨강 | Int32 | 빨간색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 녹색 | Int32 | 녹색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 파란색 | Int32 | 파란색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |

### 반환 값

이 메서드가 생성하는 [`Color`](../)입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green*, 또는 *blue* 가 0보다 작거나 255보다 큽니다. |

### 또 보기

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

지정된 [`Color`](../) 구조에서 새로운 [`Color`](../) 구조를 생성하지만, 새로 지정된 알파 값을 사용합니다. 이 메서드는 알파 값에 대해 32비트 값을 전달할 수 있지만, 값은 8비트로 제한됩니다.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alpha | Int32 | 새 [`Color`](../)의 알파 값입니다. 유효한 값은 0부터 255까지입니다. |
| baseColor | Color | 새 [`Color`](../)을 생성할 기준이 되는 [`Color`](../)입니다. |

### 반환 값

이 메서드가 생성하는 [`Color`](../)입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 가 0보다 작거나 255보다 큽니다. |

### 또 보기

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

지정된 8비트 색상 값(빨강, 녹색, 파랑)으로부터 [`Color`](../) 구조를 생성합니다. 알파 값은 암묵적으로 255(완전 불투명)입니다. 이 메서드는 각 색상 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| red | Int32 | 새 [`Color`](../)의 빨간색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| green | Int32 | 새 [`Color`](../)의 녹색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| blue | Int32 | 새 [`Color`](../)의 파란색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |

### 반환 값

이 메서드가 생성하는 [`Color`](../)입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green*, 또는 *blue* 가 0보다 작거나 255보다 큽니다. |

### 또 보기

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


