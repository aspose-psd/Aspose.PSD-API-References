---
title: GraphicsPath.Warp
second_title: Aspose.PSD per riferimento API .NET
description: GraphicsPath metodo. Applica una trasformazione warp definita da un rettangolo e un parallelogramma a questoGraphicsPath .
type: docs
weight: 180
url: /it/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | PointF[] | Una matrice di[`PointF`](../../pointf/) strutture che definiscono un parallelogramma a cui il rettangolo definito da*srcRect*si trasforma. L'array può contenere tre o quattro elementi. Se la matrice contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef/) che rappresenta il rettangolo che viene trasformato nel parallelogramma definito da*destPoints*. |

### Guarda anche

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | PointF[] | Una matrice di[`PointF`](../../pointf/) strutture che definiscono un parallelogramma a cui il rettangolo definito da*srcRect*si trasforma. L'array può contenere tre o quattro elementi. Se la matrice contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef/) che rappresenta il rettangolo che viene trasformato nel parallelogramma definito da*destPoints*. |
| matrix | Matrix | UN[`Matrix`](../../matrix/) che specifica una trasformazione geometrica da applicare al tracciato. |

### Guarda anche

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | PointF[] | Una matrice di[`PointF`](../../pointf/) strutture che definiscono un parallelogramma a cui il rettangolo definito da*srcRect*si trasforma. L'array può contenere tre o quattro elementi. Se la matrice contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef/) che rappresenta il rettangolo che viene trasformato nel parallelogramma definito da*destPoints*. |
| matrix | Matrix | UN[`Matrix`](../../matrix/) che specifica una trasformazione geometrica da applicare al tracciato. |
| warpMode | WarpMode | UN[`WarpMode`](../../warpmode/) enumerazione che specifica se questa operazione di distorsione utilizza la modalità prospettiva o bilineare. |

### Guarda anche

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Applica una trasformazione warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | PointF[] | Una matrice di[`PointF`](../../pointf/) strutture che definiscono un parallelogramma a cui il rettangolo definito da*srcRect*si trasforma. L'array può contenere tre o quattro elementi. Se la matrice contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | RectangleF | UN[`RectangleF`](../../rectanglef/) che rappresenta il rettangolo che viene trasformato nel parallelogramma definito da*destPoints*. |
| matrix | Matrix | UN[`Matrix`](../../matrix/) che specifica una trasformazione geometrica da applicare al tracciato. |
| warpMode | WarpMode | UN[`WarpMode`](../../warpmode/) enumerazione che specifica se questa operazione di distorsione utilizza la modalità prospettiva o bilineare. |
| flatness | Single | Un valore compreso tra 0 e 1 che specifica quanto è piatto il percorso risultante. Per ulteriori informazioni, vedere il[`Flatten`](../flatten/) metodi. |

### Guarda anche

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)


