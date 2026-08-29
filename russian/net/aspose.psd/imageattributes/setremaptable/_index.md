---
title: "ImageAttributes.SetRemapTable"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageAttributes. Устанавливает таблицу colorremap для категории по умолчанию."
type: docs
weight: 190
url: /ru/net/aspose.psd/imageattributes/setremaptable/
---
{{< psd/tize >}}
## SetRemapTable(ColorMap[]) {#setremaptable}

Устанавливает таблицу перекраски цветов для категории по умолчанию.

```csharp
public void SetRemapTable(ColorMap[] map)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| map | ColorMap[] | Массив пар цветов типа [`ColorMap`](../../colormap/). Каждая пара цветов содержит существующий цвет (первое значение) и цвет, к которому он будет сопоставлен (второе значение). |

### См. также

* class [ColorMap](../../colormap/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetRemapTable(ColorMap[], ColorAdjustType) {#setremaptable_1}

Устанавливает таблицу перекраски цветов для указанной категории.

```csharp
public void SetRemapTable(ColorMap[] map, ColorAdjustType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| map | ColorMap[] | Массив пар цветов типа [`ColorMap`](../../colormap/). Каждая пара цветов содержит существующий цвет (первое значение) и цвет, к которому он будет сопоставлен (второе значение). |
| type | ColorAdjustType | Элемент [`ColorAdjustType`](../../coloradjusttype/), определяющий категорию, для которой установлена таблица color-remap. |

### См. также

* class [ColorMap](../../colormap/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


