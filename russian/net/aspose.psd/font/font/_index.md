---
title: Font
second_title: Справочник по Aspose.PSD для .NET API
description: Инициализирует новыйFontaspose.psd/fontкоторый использует указанный существующийFontaspose.psd/fontиFontStyleaspose.psd/fontstyleперечисление.
type: docs
weight: 10
url: /ru/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Инициализирует новый[`Font`](../../font)который использует указанный существующий[`Font`](../../font)и[`FontStyle`](../../fontstyle)перечисление.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | Font | Существующий[`Font`](../../font)из которого создать новыйШрифт. |
| newStyle | FontStyle | Стиль[`FontStyle`](../../fontstyle)применяется к новомуШрифт. Несколько значений перечисления[`FontStyle`](../../fontstyle)можно комбинировать с помощью оператора ИЛИ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *prototype*равно null. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* пространство имен [Aspose.PSD](../../font)
* сборка [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Инициализирует новый шрифт[`Font`](../../font)указанного размера. Набор символов установлен наDefault, графический модуль наPoint, стиль шрифта наRegular.

```csharp
public Font(string fontName, float emSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени[`Font`](../../font). |
| emSize | Single | Размер em нового шрифта в пунктах. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName*равно нулю. |

### Смотрите также

* class [Font](../../font)
* пространство имен [Aspose.PSD](../../font)
* сборка [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Инициализирует новый[`Font`](../../font)с использованием указанного размера и стиля. Набор символов установлен наDefault, графический модуль наPoint.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени[`Font`](../../font). |
| emSize | Single | Размер em нового шрифта в пунктах. |
| style | FontStyle | [`FontStyle`](../../fontstyle)нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName*равно нулю. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* пространство имен [Aspose.PSD](../../font)
* сборка [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Инициализирует новый[`Font`](../../font)с использованием указанного размера и единицы измерения. Набор символов установлен наDefault, стиль установлен наRegular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени[`Font`](../../font). |
| emSize | Single | Размер em нового шрифта в единицах, заданных параметром*unit*. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit)нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName*равно нулю. |

### Смотрите также

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* пространство имен [Aspose.PSD](../../font)
* сборка [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Инициализирует новый[`Font`](../../font)с использованием указанного размера, стиля, единицы измерения и набора символов.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени[`Font`](../../font). |
| emSize | Single | Размер em нового шрифта в единицах, заданных параметром*unit*. |
| style | FontStyle | [`FontStyle`](../../fontstyle)нового шрифта. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit)нового шрифта. |
| characterSet | CharacterSet | Набор символов, используемый для этого шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName*равно нулю. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* пространство имен [Aspose.PSD](../../font)
* сборка [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Инициализирует новый[`Font`](../../font)с использованием указанного размера, стиля и единицы измерения.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление имени[`Font`](../../font). |
| emSize | Single | Размер em нового шрифта в единицах, заданных параметром*unit*. |
| style | FontStyle | [`FontStyle`](../../fontstyle)нового шрифта. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit)нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName*равно нулю. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* пространство имен [Aspose.PSD](../../font)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
