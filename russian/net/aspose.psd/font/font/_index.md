---
title: "Font.Font"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор Font. Инициализирует новый Font, использующий указанный существующий Font и перечисление FontStyle."
type: docs
weight: 10
url: /ru/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Инициализирует новый [`Font`](../), использующий указанный существующий [`Font`](../) и перечисление [`FontStyle`](../../fontstyle/).

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | Font | Существующий [`Font`](../), из которого создаётся новый [`Font`](../). |
| newStyle | FontStyle | [`FontStyle`](../../fontstyle/), применяемый к новому [`Font`](../). Несколько значений перечисления [`FontStyle`](../../fontstyle/) могут быть объединены оператором OR. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *prototype* равен null. |

### См. также

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Инициализирует новый [`Font`](../) с указанным размером. Набор символов устанавливается в Default, графическая единица — в Point, стиль шрифта — в Regular.

```csharp
public Font(string fontName, float emSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени [`Font`](../). |
| emSize | Single | Размер em в пунктах нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равен 0, равен бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* равен null. |

### См. также

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Инициализирует новый [`Font`](../) с указанным размером и стилем. Набор символов устанавливается в Default, графическая единица — в Point.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени [`Font`](../). |
| emSize | Single | Размер em в пунктах нового шрифта. |
| style | FontStyle | [`FontStyle`](../../fontstyle/) нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равен 0, равен бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* равен null. |

### См. также

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Инициализирует новый [`Font`](../) с указанным размером и единицей измерения. Набор символов устанавливается в Default, стиль — в Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени [`Font`](../). |
| emSize | Single | Размер em нового шрифта в единицах, указанных параметром *unit*. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равен 0, равен бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* равен null. |

### См. также

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Инициализирует новый [`Font`](../) с указанным размером, стилем, единицей измерения и набором символов.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени [`Font`](../). |
| emSize | Single | Размер em нового шрифта в единицах, указанных параметром *unit*. |
| style | FontStyle | [`FontStyle`](../../fontstyle/) нового шрифта. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) нового шрифта. |
| characterSet | CharacterSet | Набор символов, используемый для этого шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равен 0, равен бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* равен null. |

### См. также

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Инициализирует новый [`Font`](../) с указанным размером, стилем и единицей измерения.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени [`Font`](../). |
| emSize | Single | Размер em нового шрифта в единицах, указанных параметром *unit*. |
| style | FontStyle | [`FontStyle`](../../fontstyle/) нового шрифта. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равен 0, равен бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* равен null. |

### См. также

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


