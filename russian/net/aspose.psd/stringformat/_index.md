---
title: "Класс StringFormat"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.StringFormat. Инкапсулирует информацию о размещении текста, такую как ориентация выравнивания и табуляция, а также манипуляции отображением, такие как вставка многоточия, замена национальных цифр и функции OpenType. Этот класс не может быть наследован."
type: docs
weight: 6170
url: /ru/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Инкапсулирует информацию о расположении текста (например, выравнивание, ориентацию и табуляцию), манипуляции отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть наследован.

```csharp
public sealed class StringFormat : DisposableObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Инициализирует новый объект `StringFormat`. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Инициализирует новый объект `StringFormat` из указанного существующего объекта `StringFormat`. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Инициализирует новый объект `StringFormat` с указанным перечислением [`StringFormatFlags`](../stringformatflags/) и языком. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Получает объект `StringFormat` по умолчанию общего назначения. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Получает объект `StringFormat` общего типографического назначения. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Получает или задает информацию о выравнивании текста по вертикали. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Получает или задает пользовательский идентификатор символа. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Получает или задает язык, используемый при замене локальных цифр на западные. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Получает или задает метод, используемый для замены цифр. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Получает количество пробелов между началом строки текста и первой табуляцией. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Получает или задает перечисление [`StringFormatFlags`](../stringformatflags/), содержащее информацию о форматировании. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Получает или задает объект [`HotkeyPrefix`](../hotkeyprefix/) для этого объекта `StringFormat`. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Получает или задает выравнивание строк по горизонтали. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Получает массив расстояний между табуляциями в единицах, указанных свойством [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Получает или задает перечисление [`StringTrimming`](../stringtrimming/) для этого объекта `StringFormat`. |

## Методы

| Имя | Описание |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Создаёт глубокую копию этого объекта `StringFormat`. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Проверьте, равны ли объекты. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Получите хеш‑код текущего объекта. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Задаёт табуляцию для этого объекта `StringFormat`. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Преобразует этот объект `StringFormat` в читаемую строку. |

### См. также

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


