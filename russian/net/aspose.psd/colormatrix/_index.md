---
title: "Класс ColorMatrix"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ColorMatrix. Определяет матрицу 5 × 5, содержащую координаты для пространства RGBA. Несколько методов класса ImageAttributes корректируют цвета изображения, используя цветовую матрицу. Этот класс не может быть наследован"
type: docs
weight: 350
url: /ru/net/aspose.psd/colormatrix/
---
{{< psd/tize >}}
## ColorMatrix class

Определяет матрицу 5 × 5, содержащую координаты для пространства RGBA. Несколько методов класса [`ImageAttributes`](../imageattributes/) корректируют цвета изображения, используя цветовую матрицу. Этот класс не может быть наследован.

```csharp
public sealed class ColorMatrix
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ColorMatrix](colormatrix/#constructor)() | Инициализирует новый экземпляр класса `ColorMatrix`. |
| [ColorMatrix](colormatrix/#constructor_1)(float[][]) | Инициализирует новый экземпляр класса `ColorMatrix`, используя элементы указанной матрицы *newColorMatrix*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.psd/colormatrix/item/) { get; set; } | Получает или задает элемент в указанной строке и столбце матрицы `ColorMatrix`. |
| [Matrix00](../../aspose.psd/colormatrix/matrix00/) { get; set; } | Получает или задает элемент в 0‑й (нулевой) строке и 0‑м столбце этой `ColorMatrix`. |
| [Matrix01](../../aspose.psd/colormatrix/matrix01/) { get; set; } | Получает или задает элемент в 0‑й (нулевой) строке и первом столбце этой `ColorMatrix`. |
| [Matrix02](../../aspose.psd/colormatrix/matrix02/) { get; set; } | Получает или задает элемент в 0‑й (нулевой) строке и втором столбце этой `ColorMatrix`. |
| [Matrix03](../../aspose.psd/colormatrix/matrix03/) { get; set; } | Получает или задает элемент в 0‑й (нулевой) строке и третьем столбце этой `ColorMatrix`. |
| [Matrix04](../../aspose.psd/colormatrix/matrix04/) { get; set; } | Получает или задает элемент в 0‑й (нулевой) строке и четвертом столбце этой `ColorMatrix`. |
| [Matrix10](../../aspose.psd/colormatrix/matrix10/) { get; set; } | Получает или задает элемент в первой строке и 0‑м (нулевом) столбце этой `ColorMatrix`. |
| [Matrix11](../../aspose.psd/colormatrix/matrix11/) { get; set; } | Получает или задает элемент в первой строке и первом столбце этой `ColorMatrix`. |
| [Matrix12](../../aspose.psd/colormatrix/matrix12/) { get; set; } | Получает или задает элемент в первой строке и втором столбце этой `ColorMatrix`. |
| [Matrix13](../../aspose.psd/colormatrix/matrix13/) { get; set; } | Получает или задает элемент в первой строке и третьем столбце этой `ColorMatrix`. |
| [Matrix14](../../aspose.psd/colormatrix/matrix14/) { get; set; } | Получает или задает элемент в первой строке и четвертом столбце этой `ColorMatrix`. |
| [Matrix20](../../aspose.psd/colormatrix/matrix20/) { get; set; } | Получает или задает элемент во второй строке и 0‑м (нулевом) столбце этой `ColorMatrix`. |
| [Matrix21](../../aspose.psd/colormatrix/matrix21/) { get; set; } | Получает или задает элемент во второй строке и первом столбце этой `ColorMatrix`. |
| [Matrix22](../../aspose.psd/colormatrix/matrix22/) { get; set; } | Получает или задает элемент во второй строке и втором столбце этой `ColorMatrix`. |
| [Matrix23](../../aspose.psd/colormatrix/matrix23/) { get; set; } | Получает или задает элемент во второй строке и третьем столбце этой `ColorMatrix`. |
| [Matrix24](../../aspose.psd/colormatrix/matrix24/) { get; set; } | Получает или задает элемент во второй строке и четвертом столбце этой `ColorMatrix`. |
| [Matrix30](../../aspose.psd/colormatrix/matrix30/) { get; set; } | Получает или задает элемент в третьей строке и 0 (ноль) столбце этой `ColorMatrix`. |
| [Matrix31](../../aspose.psd/colormatrix/matrix31/) { get; set; } | Получает или задает элемент в третьей строке и первом столбце этой `ColorMatrix`. |
| [Matrix32](../../aspose.psd/colormatrix/matrix32/) { get; set; } | Получает или задает элемент в третьей строке и втором столбце этой `ColorMatrix`. |
| [Matrix33](../../aspose.psd/colormatrix/matrix33/) { get; set; } | Получает или задает элемент в третьей строке и третьем столбце этой `ColorMatrix`. |
| [Matrix34](../../aspose.psd/colormatrix/matrix34/) { get; set; } | Получает или задает элемент в третьей строке и четвертом столбце этой `ColorMatrix`. |
| [Matrix40](../../aspose.psd/colormatrix/matrix40/) { get; set; } | Получает или задает элемент в четвертой строке и 0 (ноль) столбце этой `ColorMatrix`. |
| [Matrix41](../../aspose.psd/colormatrix/matrix41/) { get; set; } | Получает или задает элемент в четвертой строке и первом столбце этой `ColorMatrix`. |
| [Matrix42](../../aspose.psd/colormatrix/matrix42/) { get; set; } | Получает или задает элемент в четвертой строке и втором столбце этой `ColorMatrix`. |
| [Matrix43](../../aspose.psd/colormatrix/matrix43/) { get; set; } | Получает или задает элемент в четвертой строке и третьем столбце этой `ColorMatrix`. |
| [Matrix44](../../aspose.psd/colormatrix/matrix44/) { get; set; } | Получает или задает элемент в четвертой строке и четвертом столбце этой `ColorMatrix`. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetMatrix](../../aspose.psd/colormatrix/getmatrix/)() | Получает значения матрицы. |

## Поля

| Имя | Описание |
| --- | --- |
| const [MatrixDimensionElementsCount](../../aspose.psd/colormatrix/matrixdimensionelementscount/) | Количество элементов в измерении матрицы. |
| const [MatrixDimensionsCount](../../aspose.psd/colormatrix/matrixdimensionscount/) | Количество измерений матрицы. |
| const [MatrixTotalElementsCount](../../aspose.psd/colormatrix/matrixtotalelementscount/) | Общее количество элементов в матрице. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


