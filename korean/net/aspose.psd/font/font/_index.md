---
title: "Font.Font"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Font 생성자. 지정된 기존 Font와 FontStyle 열거형을 사용하는 새 Font를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

지정된 기존 [`Font`](../)와 [`FontStyle`](../../fontstyle/) 열거형을 사용하는 새 [`Font`](../)를 초기화합니다.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prototype | Font | 새 [`Font`](../)을 생성할 기존 [`Font`](../)입니다. |
| newStyle | FontStyle | 새 [`Font`](../)에 적용할 [`FontStyle`](../../fontstyle/). [`FontStyle`](../../fontstyle/) 열거형의 여러 값을 OR 연산자로 결합할 수 있습니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *prototype*이 null입니다. |

### 또 보기

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

지정된 크기를 사용하여 새 [`Font`](../)를 초기화합니다. 문자 집합은 Default로, 그래픽 단위는 Point로, 글꼴 스타일은 Regular로 설정됩니다.

```csharp
public Font(string fontName, float emSize)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | String | `[`Font`](../) 이름의 문자열 표현입니다. |
| emSize | 단일 | 새 글꼴의 em-size, 포인트 단위. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*이 0 이하이거나, 무한대로 평가되거나, 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName*이 null입니다. |

### 또 보기

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

지정된 크기와 스타일을 사용하여 새 [`Font`](../)를 초기화합니다. 문자 집합은 Default로, 그래픽 단위는 Point로 설정됩니다.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | String | `[`Font`](../) 이름의 문자열 표현입니다. |
| emSize | 단일 | 새 글꼴의 em-size, 포인트 단위. |
| style | FontStyle | 새 글꼴의 [`FontStyle`](../../fontstyle/)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*이 0 이하이거나, 무한대로 평가되거나, 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName*이 null입니다. |

### 또 보기

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

지정된 크기와 단위를 사용하여 새 [`Font`](../)를 초기화합니다. 문자 집합은 Default로, 스타일은 Regular로 설정됩니다.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | String | `[`Font`](../) 이름의 문자열 표현입니다. |
| emSize | 단일 | *unit* 매개변수로 지정된 단위로 새 글꼴의 em-size입니다. |
| unit | GraphicsUnit | 새 글꼴의 [`GraphicsUnit`](../../graphicsunit/)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*이 0 이하이거나, 무한대로 평가되거나, 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName*이 null입니다. |

### 또 보기

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새 [`Font`](../)를 초기화합니다.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | String | `[`Font`](../) 이름의 문자열 표현입니다. |
| emSize | 단일 | *unit* 매개변수로 지정된 단위로 새 글꼴의 em-size입니다. |
| style | FontStyle | 새 글꼴의 [`FontStyle`](../../fontstyle/)입니다. |
| unit | GraphicsUnit | 새 글꼴의 [`GraphicsUnit`](../../graphicsunit/)입니다. |
| characterSet | CharacterSet | 이 글꼴에 사용할 문자 집합입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*이 0 이하이거나, 무한대로 평가되거나, 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName*이 null입니다. |

### 또 보기

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

지정된 크기, 스타일 및 단위를 사용하여 새로운 [`Font`](../)을 초기화합니다.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | String | `[`Font`](../) 이름의 문자열 표현입니다. |
| emSize | 단일 | *unit* 매개변수로 지정된 단위로 새 글꼴의 em-size입니다. |
| style | FontStyle | 새 글꼴의 [`FontStyle`](../../fontstyle/)입니다. |
| unit | GraphicsUnit | 새 글꼴의 [`GraphicsUnit`](../../graphicsunit/)입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*이 0 이하이거나, 무한대로 평가되거나, 유효한 숫자가 아닙니다. |
| ArgumentNullException | *fontName*이 null입니다. |

### 또 보기

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


