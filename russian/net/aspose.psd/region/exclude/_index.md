---
title: "Region.Exclude"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Region. Обновляет этот Region, оставляя только часть его внутреннего пространства, не пересекающуюся с указанной структурой RectangleF."
type: docs
weight: 50
url: /ru/net/aspose.psd/region/exclude/
---
{{< psd/tize >}}
## Exclude(RectangleF) {#exclude_2}

Обновляет этот [`Region`](../), оставляя только часть его внутреннего пространства, не пересекающуюся с указанной структурой [`RectangleF`](../../rectanglef/).

```csharp
public void Exclude(RectangleF rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/), которую следует исключить из этого [`Region`](../). |

### См. также

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Exclude(Rectangle) {#exclude_1}

Обновляет этот [`Region`](../), оставляя только часть его внутреннего пространства, не пересекающуюся с указанной структурой [`Rectangle`](../../rectangle/).

```csharp
public void Exclude(Rectangle rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Структура [`Rectangle`](../../rectangle/), которую следует исключить из этого [`Region`](../). |

### См. также

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Exclude(GraphicsPath) {#exclude}

Обновляет этот [`Region`](../), оставляя только часть его внутреннего пространства, не пересекающуюся с указанным [`GraphicsPath`](../../graphicspath/).

```csharp
public void Exclude(GraphicsPath path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | GraphicsPath | Объект [`GraphicsPath`](../../graphicspath/), который следует исключить из этого [`Region`](../). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *path* равен null. |

### См. также

* class [GraphicsPath](../../graphicspath/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Exclude(Region) {#exclude_3}

Обновляет этот [`Region`](../), чтобы он содержал только ту часть своего внутреннего пространства, которая не пересекается с указанным [`Region`](../).

```csharp
public void Exclude(Region region)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | Region | [`Region`](../), который следует исключить из этого [`Region`](../). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *region* равен null. |

### См. также

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


