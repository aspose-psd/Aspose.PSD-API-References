---
title: Graphics.DrawBezier
second_title: Aspose.PSD per riferimento API .NET
description: Graphics metodo. Disegna una spline di Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.
type: docs
weight: 170
url: /it/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Disegna una spline di Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile della curva. |
| x1 | Single | La coordinata x del punto iniziale della curva. |
| y1 | Single | La coordinata y del punto iniziale della curva. |
| x2 | Single | La coordinata x del primo punto di controllo della curva. |
| y2 | Single | La coordinata y del primo punto di controllo della curva. |
| x3 | Single | La coordinata x del secondo punto di controllo della curva. |
| y3 | Single | La coordinata y del secondo punto di controllo della curva. |
| x4 | Single | La coordinata x del punto finale della curva. |
| y4 | Single | La coordinata y del punto finale della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Disegna una spline di Bézier definita da quattro[`PointF`](../../pointf/) strutture.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | PointF | [`PointF`](../../pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | PointF | [`PointF`](../../pointf/) struttura che rappresenta il primo punto di controllo per la curva. |
| pt3 | PointF | [`PointF`](../../pointf/) struttura che rappresenta il secondo punto di controllo per la curva. |
| pt4 | PointF | [`PointF`](../../pointf/) struttura che rappresenta il punto finale della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Disegna una spline di Bézier definita da quattro[`Point`](../../point/) strutture.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) struttura che determina il colore, la larghezza e lo stile della curva. |
| pt1 | Point | [`Point`](../../point/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | Point | [`Point`](../../point/) struttura che rappresenta il primo punto di controllo per la curva. |
| pt3 | Point | [`Point`](../../point/) struttura che rappresenta il secondo punto di controllo per la curva. |
| pt4 | Point | [`Point`](../../point/) struttura che rappresenta il punto finale della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)


