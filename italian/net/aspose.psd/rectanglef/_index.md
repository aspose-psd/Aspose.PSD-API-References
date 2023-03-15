---
title: Struct RectangleF
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.RectangleF struct. Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
weight: 5350
url: /it/net/aspose.psd/rectanglef/
---
## RectangleF structure

Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.

```csharp
public struct RectangleF
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Inizializza una nuova istanza di`RectangleF` struttura con la posizione e le dimensioni specificate. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Inizializza una nuova istanza di`RectangleF` struttura con la posizione e le dimensioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Ottiene una nuova istanza di`RectangleF` struttura che ha[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) E[`Height`](./height/) valori impostati a zero. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Ottiene o imposta la coordinata y che è la somma di[`Y`](./y/) E[`Height`](./height/) di questo`RectangleF`struttura. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Ottiene o imposta l'altezza di this`RectangleF`struttura. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Ottiene un valore che indica se il[`Width`](./width/) O[`Height`](./height/) proprietà di questo`RectangleF` ha un valore pari a zero. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Ottiene o imposta la coordinata x del bordo sinistro di this`RectangleF`struttura. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Ottiene o imposta le coordinate dell'angolo superiore sinistro di this`RectangleF`struttura. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Ottiene o imposta la coordinata x che è la somma di[`X`](./x/) E[`Width`](./width/) di questo`RectangleF`struttura. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Ottiene o imposta la dimensione di this`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Ottiene o imposta la coordinata y del bordo superiore di this`RectangleF`struttura. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Ottiene o imposta la larghezza di this`RectangleF`struttura. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di this`RectangleF`struttura. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di this`RectangleF`struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Crea un`RectangleF` struttura con angolo superiore sinistro e angolo inferiore destro nelle posizioni specificate. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Crea un nuovo[`Rectangle`](../rectangle/) da due punti specificati. Due vertici del creato[`Rectangle`](../rectangle/) sarà uguale al passato*point1* E*point2* . Questi sarebbero in genere i vertici opposti. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Crea e restituisce una copia gonfiata dell'oggetto specificato`RectangleF`struttura. La copia viene gonfiata della quantità specificata. Il rettangolo originale rimane invariato. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Restituisce a`RectangleF` struttura che rappresenta l'intersezione di due rettangoli. Se non c'è intersezione e vuoto`RectangleF` viene restituito. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Crea il terzo rettangolo più piccolo possibile che può contenere entrambi i due rettangoli che formano un'unione. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Determina se il punto specificato è contenuto all'interno di questo`RectangleF`struttura. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Determina se l'area rettangolare rappresentata da*rect* è interamente contenuto in questo`RectangleF`struttura. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Determina se il punto specificato è contenuto all'interno di questo`RectangleF`struttura. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Verifica se*obj* è un`RectangleF` con la stessa posizione e dimensione di questo`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Ottiene il codice hash per questo`RectangleF`struttura. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Gonfia questo`RectangleF`dell'importo specificato. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Gonfia questo`RectangleF` struttura per l'importo specificato. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Sostituisce questo`RectangleF`struttura con l'intersezione di se stesso e lo specificato`RectangleF`struttura. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Determina se questo rettangolo si interseca con*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normalizza il rettangolo rendendone la larghezza e l'altezza positive, sinistra minore di destra e superiore minore di inferiore. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Regola la posizione di questo rettangolo in base alla quantità specificata. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Regola la posizione di questo rettangolo in base alla quantità specificata. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Converte gli attributi di this`RectangleF` in una stringa leggibile dall'uomo. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implementa l'operatore /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Verifica se due`RectangleF` le strutture hanno la stessa posizione e dimensione. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Converte l'oggetto specificato[`Rectangle`](../rectangle/) struttura ad a`RectangleF`struttura. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Verifica se due`RectangleF` le strutture differiscono per posizione o dimensioni. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implementa l'operatore *. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


