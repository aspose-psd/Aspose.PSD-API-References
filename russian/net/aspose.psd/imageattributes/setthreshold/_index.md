---
title: "ImageAttributes.SetThreshold"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageAttributes. Устанавливает диапазон прозрачности порога для категории по умолчанию"
type: docs
weight: 200
url: /ru/net/aspose.psd/imageattributes/setthreshold/
---
{{< psd/tize >}}
## SetThreshold(float) {#setthreshold}

Устанавливает порог (диапазон прозрачности) для категории по умолчанию.

```csharp
public void SetThreshold(float threshold)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | Single | Вещественное число, определяющее значение порога. |

### См. также

* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetThreshold(float, ColorAdjustType) {#setthreshold_1}

Устанавливает порог (диапазон прозрачности) для указанной категории.

```csharp
public void SetThreshold(float threshold, ColorAdjustType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | Single | Значение порога от 0,0 до 1,0, используемое в качестве точки разрыва для сортировки цветов, которые будут сопоставлены либо с максимальным, либо с минимальным значением. |
| type | ColorAdjustType | Элемент [`ColorAdjustType`](../../coloradjusttype/), определяющий категорию, для которой установлен цветовой порог. |

### См. также

* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


