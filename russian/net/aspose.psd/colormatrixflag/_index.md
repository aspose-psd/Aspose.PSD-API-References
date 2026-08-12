---
title: "Перечисление ColorMatrixFlag"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.ColorMatrixFlag. Указывает типы изображений и цветов, которые будут затронуты настройками коррекции цвета и градации серого объекта ImageAttributes."
type: docs
weight: 360
url: /ru/net/aspose.psd/colormatrixflag/
---
{{< psd/tize >}}
## ColorMatrixFlag enumeration

Указывает типы изображений и цветов, которые будут затронуты настройками коррекции цвета и градаций серого объекта [`ImageAttributes`](../imageattributes/).

```csharp
public enum ColorMatrixFlag
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | `0` | Все значения цветов, включая оттенки серого, корректируются одной и той же матрицей коррекции цвета. |
| SkipGrays | `1` | Все цвета корректируются, но оттенки серого не корректируются. Оттенок серого — это любой цвет, у которого одинаковые значения компонентов красного, зеленого и синего. |
| AltGrays | `2` | Корректируются только оттенки серого. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


