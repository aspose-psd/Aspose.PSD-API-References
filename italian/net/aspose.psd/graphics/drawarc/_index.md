---
title: DrawArc
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Disegna un arco che rappresenta una porzione di unellisse specificata da una coppia di coordinate una larghezza e unaltezza.
type: docs
weight: 160
url: /it/net/aspose.psd/graphics/drawarc/
---
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile dell'arco. |
| x | Single | Coordinata x dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| y | Single | La coordinata y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| width | Single | Larghezza del rettangolo che definisce l'ellisse. |
| height | Single | Altezza del rettangolo che definisce l'ellisse. |
| startAngle | Single | Angolo in gradi misurato in senso orario dall'asse x al punto iniziale dell'arco. |
| sweepAngle | Single | Angolo in gradi misurato in senso orario dal*startAngle* parametro al punto finale dell'arco. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Disegna un arco che rappresenta una porzione di un'ellisse specificata da a[`RectangleF`](../../rectanglef)struttura.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) struttura che definisce i confini dell'ellisse. |
| startAngle | Single | Angolo in gradi misurato in senso orario dall'asse x al punto iniziale dell'arco. |
| sweepAngle | Single | Angolo in gradi misurato in senso orario dal*startAngle* parametro al punto finale dell'arco. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero |

### Guarda anche

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile dell'arco. |
| x | Int32 | Coordinata x dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| y | Int32 | La coordinata y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| width | Int32 | Larghezza del rettangolo che definisce l'ellisse. |
| height | Int32 | Altezza del rettangolo che definisce l'ellisse. |
| startAngle | Int32 | Angolo in gradi misurato in senso orario dall'asse x al punto iniziale dell'arco. |
| sweepAngle | Int32 | Angolo in gradi misurato in senso orario dal*startAngle* parametro al punto finale dell'arco. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Disegna un arco che rappresenta una porzione di un'ellisse specificata da a[`Rectangle`](../../rectangle)struttura.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | Rectangle | [`RectangleF`](../../rectanglef) struttura che definisce i confini dell'ellisse. |
| startAngle | Single | Angolo in gradi misurato in senso orario dall'asse x al punto iniziale dell'arco. |
| sweepAngle | Single | Angolo in gradi misurato in senso orario dal*startAngle* parametro al punto finale dell'arco. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
