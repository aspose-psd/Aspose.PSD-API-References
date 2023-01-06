---
title: DrawCurve
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Disegna una spline cardinale attraverso una matrice specificata diPointFaspose.psd/pointf strutture. Questo metodo utilizza una tensione predefinita di 05.
type: docs
weight: 200
url: /it/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../../pointf) strutture. Questo metodo utilizza una tensione predefinita di 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | PointF[] | Matrice di[`PointF`](../../pointf) strutture che definiscono la spline. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../../pointf) strutture che utilizzano una tensione specificata.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | PointF[] | Matrice di[`PointF`](../../pointf) strutture che rappresentano i punti che definiscono la curva. |
| tension | Single | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../../pointf) strutture. Il disegno inizia sfalsato dall'inizio dell'array. Questo metodo utilizza una tensione predefinita di 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | PointF[] | Matrice di[`PointF`](../../pointf) strutture che definiscono la spline. |
| offset | Int32 | Offset dal primo elemento nell'array di*points* parametro al punto iniziale nella curva. |
| numberOfSegments | Int32 | Numero di segmenti dopo il punto iniziale da includere nella curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../../pointf) strutture che utilizzano una tensione specificata. Il disegno inizia sfalsato dall'inizio dell'array.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | PointF[] | Matrice di[`PointF`](../../pointf) strutture che definiscono la spline. |
| offset | Int32 | Offset dal primo elemento nell'array di*points* parametro al punto iniziale nella curva. |
| numberOfSegments | Int32 | Numero di segmenti dopo il punto iniziale da includere nella curva. |
| tension | Single | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Disegna una spline cardinale attraverso una matrice specificata di[`Point`](../../point) strutture.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | Point[] | Matrice di[`Point`](../../point) strutture che definiscono la spline. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Disegna una spline cardinale attraverso una matrice specificata di[`Point`](../../point) strutture che utilizzano una tensione specificata.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | Point[] | Matrice di[`Point`](../../point) strutture che definiscono la spline. |
| tension | Single | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Disegna una spline cardinale attraverso una matrice specificata di[`Point`](../../point) strutture che utilizzano una tensione specificata.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e l'altezza della curva. |
| points | Point[] | Matrice di[`Point`](../../point) strutture che definiscono la spline. |
| offset | Int32 | Offset dal primo elemento nell'array di*points* parametro al punto iniziale nella curva. |
| numberOfSegments | Int32 | Numero di segmenti dopo il punto iniziale da includere nella curva. |
| tension | Single | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è nullo. -o- *points* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
