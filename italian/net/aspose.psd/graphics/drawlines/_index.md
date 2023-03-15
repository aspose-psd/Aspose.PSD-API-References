---
title: Graphics.DrawLines
second_title: Aspose.PSD per riferimento API .NET
description: Graphics metodo. Disegna una serie di segmenti di linea che collegano un array diPoint strutture.
type: docs
weight: 260
url: /it/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Disegna una serie di segmenti di linea che collegano un array di[`Point`](../../point/) strutture.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | Point[] | Matrice di[`Point`](../../point/) strutture che rappresentano i punti da collegare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -oppure- *points* è zero. |
| ArgumentException | IL*points* l'array contiene meno di 2 punti. |

### Guarda anche

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Disegna una serie di segmenti di linea che collegano un array di[`PointF`](../../pointf/) strutture.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | PointF[] | Matrice di[`PointF`](../../pointf/) strutture che rappresentano i punti da collegare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -oppure- *points* è zero. |
| ArgumentException | IL*points* l'array contiene meno di 2 punti. |

### Guarda anche

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* spazio dei nomi [Aspose.PSD](../../graphics/)
* assemblea [Aspose.PSD](../../../)


