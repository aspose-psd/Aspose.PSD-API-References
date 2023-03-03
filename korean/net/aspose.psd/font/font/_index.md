---
title: Font.Font
second_title: .NET API 참조용 Aspose.PSD
description: Font 건설자. 새 항목을 초기화합니다.Font 지정된 기존Font 그리고FontStyle 열거형.
type: docs
weight: 10
url: /ko/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

새 항목을 초기화합니다.[`Font`](../) 지정된 기존[`Font`](../) 그리고[`FontStyle`](../../fontstyle/) 열거형.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| prototype | Font | 기존[`Font`](../) 새로운 것을 만드는 것으로부터[`Font`](../). |
| newStyle | FontStyle | 그만큼[`FontStyle`](../../fontstyle/) 신규에 적용하기 위해[`Font`](../) . 여러 값[`FontStyle`](../../fontstyle/) 열거형은 OR 연산자와 결합할 수 있습니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *prototype* null입니다. |

### 또한보십시오

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* 네임스페이스 [Aspose.PSD](../../font/)
* 집회 [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

새 항목을 초기화합니다.[`Font`](../) 지정된 크기를 사용합니다. 문자 집합은 다음과 같이 설정됩니다.Default , 그래픽 단위Point , 글꼴 스타일Regular .

```csharp
public Font(string fontName, float emSize)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 문자열 표현[`Font`](../) 이름. |
| emSize | Single | 새 글꼴의 전각 크기(포인트)입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0보다 작거나 같거나 무한대로 평가되거나 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName* null입니다. |

### 또한보십시오

* class [Font](../)
* 네임스페이스 [Aspose.PSD](../../font/)
* 집회 [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

새 항목을 초기화합니다.[`Font`](../) 지정된 크기와 스타일을 사용합니다. 문자 집합은 다음과 같이 설정됩니다.Default , 그래픽 단위Point .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 문자열 표현[`Font`](../) 이름. |
| emSize | Single | 새 글꼴의 전각 크기(포인트)입니다. |
| style | FontStyle | 그만큼[`FontStyle`](../../fontstyle/) 새 글꼴의. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0보다 작거나 같거나 무한대로 평가되거나 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName* null입니다. |

### 또한보십시오

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* 네임스페이스 [Aspose.PSD](../../font/)
* 집회 [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

새 항목을 초기화합니다.[`Font`](../) 지정된 크기와 단위를 사용합니다. 문자 집합은 다음과 같이 설정됩니다.Default 스타일은 다음으로 설정됩니다.Regular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 문자열 표현[`Font`](../) 이름. |
| emSize | Single | 에서 지정한 단위로 새 글꼴의 전각 크기*unit* 매개변수. |
| unit | GraphicsUnit | 그만큼[`GraphicsUnit`](../../graphicsunit/) 새 글꼴의. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0보다 작거나 같거나 무한대로 평가되거나 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName* null입니다. |

### 또한보십시오

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* 네임스페이스 [Aspose.PSD](../../font/)
* 집회 [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

새 항목을 초기화합니다.[`Font`](../) 지정된 크기, 스타일, 단위 및 문자 집합을 사용합니다.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 문자열 표현[`Font`](../) 이름. |
| emSize | Single | 에서 지정한 단위로 새 글꼴의 전각 크기*unit* 매개변수. |
| style | FontStyle | 그만큼[`FontStyle`](../../fontstyle/) 새 글꼴의. |
| unit | GraphicsUnit | 그만큼[`GraphicsUnit`](../../graphicsunit/) 새 글꼴의. |
| characterSet | CharacterSet | 이 글꼴에 사용할 문자 집합입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0보다 작거나 같거나 무한대로 평가되거나 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName* null입니다. |

### 또한보십시오

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* 네임스페이스 [Aspose.PSD](../../font/)
* 집회 [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

새 항목을 초기화합니다.[`Font`](../) 지정된 크기, 스타일 및 단위를 사용합니다.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 문자열 표현[`Font`](../) 이름. |
| emSize | Single | 에서 지정한 단위로 새 글꼴의 전각 크기*unit* 매개변수. |
| style | FontStyle | 그만큼[`FontStyle`](../../fontstyle/) 새 글꼴의. |
| unit | GraphicsUnit | 그만큼[`GraphicsUnit`](../../graphicsunit/) 새 글꼴의. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0보다 작거나 같거나 무한대로 평가되거나 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName* null입니다. |

### 또한보십시오

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* 네임스페이스 [Aspose.PSD](../../font/)
* 집회 [Aspose.PSD](../../../)


