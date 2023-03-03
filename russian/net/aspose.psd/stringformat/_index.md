---
title: Class StringFormat
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.StringFormat сорт. Инкапсулирует информацию о макете текста например выравнивание ориентацию и позиции табуляции манипуляции с отображением например вставку многоточия и замену национальных цифр и функции OpenType. Этот класс не может быть унаследован.
type: docs
weight: 5670
url: /ru/net/aspose.psd/stringformat/
---
## StringFormat class

Инкапсулирует информацию о макете текста (например, выравнивание, ориентацию и позиции табуляции), манипуляции с отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть унаследован.

```csharp
public sealed class StringFormat : DisposableObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Инициализирует новый`StringFormat` объект. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Инициализирует новый`StringFormat` объект из указанного существующего`StringFormat` объект. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Инициализирует новый`StringFormat` объект с указанным[`StringFormatFlags`](../stringformatflags/) перечисление и язык. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Получает общее значение по умолчанию`StringFormat` объект. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Получает общий типографский`StringFormat` объект. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Получает или задает информацию о выравнивании текста в вертикальной плоскости. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Получает или задает язык, используемый при замене западных цифр местными цифрами. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Получает или задает метод, который будет использоваться для замены цифр. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Получает количество пробелов между началом строки текста и первой позицией табуляции. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Получает или задает[`StringFormatFlags`](../stringformatflags/) перечисление, содержащее информацию о форматировании. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Получает или задает[`HotkeyPrefix`](../hotkeyprefix/) объект для этого`StringFormat` объект. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Получает или задает выравнивание линии в горизонтальной плоскости. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Получает массив расстояний между позициями табуляции в единицах, указанных[`PageUnit`](../graphics/pageunit/) свойство. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Получает или задает[`StringTrimming`](../stringtrimming/) перечисление для этого`StringFormat` объект. |

## Методы

| Имя | Описание |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Создает глубокий клон этого`StringFormat` объект. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Удаляет текущий экземпляр. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Устанавливает позиции табуляции для этого`StringFormat` объект. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Преобразует это`StringFormat` объект в удобочитаемую строку. |

### Смотрите также

* class [DisposableObject](../disposableobject/)
* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


