---
title: Blend
second_title: Справочник по Aspose.PSD для .NET API
description: Определяет шаблон наложения. Этот класс не может быть унаследован.
type: docs
weight: 110
url: /ru/net/aspose.psd/blend/
---
## Blend class

Определяет шаблон наложения. Этот класс не может быть унаследован.

```csharp
public sealed class Blend
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Blend](blend#constructor)() | Инициализирует новый экземпляр[`Blend`](../blend) учебный класс. Количество элементов в массивах factor и blend будет равно 1. |
| [Blend](blend#constructor_1)(int) | Инициализирует новый экземпляр[`Blend`](../blend) класс с указанным количеством факторов и позиций. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors) { get; set; } | Получает или задает массив факторов смешивания для градиента. |
| [Positions](../../aspose.psd/blend/positions) { get; set; } | Получает или задает массив позиций перехода для градиента. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals)(object) | Проверяет, является ли указанный объект[`Blend`](../blend) класс и эквивалентен этому[`Blend`](../blend) класс. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode)() | Возвращает хэш-код для этого экземпляра. |

### Примечания

Типичное использование класса смешивания — определение шаблона смешивания для кисти. И поэтому свойства смешивания должны быть тщательно инициализированы. Нулевые массивы не допускаются. Кисть выдаст соответствующее исключение, если массив коэффициентов смешивания или массив позиций пуст или их длина не одинакова.

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->