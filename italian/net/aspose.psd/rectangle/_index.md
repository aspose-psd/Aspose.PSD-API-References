---
title: Struct Rectangle
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Rectangle struct. Memorizza un insieme di quattro numeri interi che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
weight: 5340
url: /it/net/aspose.psd/rectangle/
---
## Rectangle structure

Memorizza un insieme di quattro numeri interi che rappresentano la posizione e le dimensioni di un rettangolo.

```csharp
public struct Rectangle
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Inizializza una nuova istanza di`Rectangle` struttura con la posizione e le dimensioni specificate. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Inizializza una nuova istanza di`Rectangle` struttura con la posizione e le dimensioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Ottiene una nuova istanza di`Rectangle` struttura che ha[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) E[`Height`](./height/) valori impostati a zero. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Ottiene o imposta la coordinata y che è la somma di[`Y`](./y/) E[`Height`](./height/) valori di proprietà di questo`Rectangle`struttura. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Ottiene o imposta l'altezza di this`Rectangle`struttura. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Ottiene un valore che indica se tutte le proprietà numeriche di this`Rectangle` hanno valori pari a zero. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Ottiene o imposta la coordinata x del bordo sinistro di this`Rectangle`struttura. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Ottiene o imposta le coordinate dell'angolo superiore sinistro di this`Rectangle`struttura. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Ottiene o imposta la coordinata x che è la somma di[`X`](./x/) E[`Width`](./width/) valori di proprietà di questo`Rectangle`struttura. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Ottiene o imposta la dimensione di this`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Ottiene o imposta la coordinata y del bordo superiore di this`Rectangle`struttura. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Ottiene o imposta la larghezza di this`Rectangle`struttura. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro di this`Rectangle`struttura. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro di this`Rectangle`struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Converte l'oggetto specificato[`RectangleF`](../rectanglef/) struttura ad a`Rectangle` struttura arrotondando il[`RectangleF`](../rectanglef/) valori ai successivi valori interi più alti. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Crea un`Rectangle` struttura con le posizioni dei bordi specificate. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Crea un nuovo`Rectangle` da due punti specificati. Due verticali del creato`Rectangle` sarà uguale al passato*point1* E*point2* . Questi sarebbero in genere i vertici opposti. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Crea e restituisce una copia gonfiata dell'oggetto specificato`Rectangle`struttura. La copia viene gonfiata della quantità specificata. L'originale`Rectangle` la struttura rimane invariata. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Restituisce un terzo`Rectangle` struttura che rappresenta l'intersezione di altre due`Rectangle` strutture. Se non c'è intersezione, un vuoto`Rectangle` viene restituito. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Converte l'oggetto specificato[`RectangleF`](../rectanglef/) ad un`Rectangle` arrotondando il[`RectangleF`](../rectanglef/) valori ai valori interi più vicini. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Converte l'oggetto specificato[`RectangleF`](../rectanglef/) ad un`Rectangle` troncando il[`RectangleF`](../rectanglef/) valori. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Ottiene a`Rectangle` struttura che contiene l'unione di due`Rectangle` strutture. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Determina se il punto specificato è contenuto all'interno di questo`Rectangle`struttura. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Determina se l'area rettangolare rappresentata da*rect* è interamente contenuto in questo`Rectangle`struttura. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Determina se il punto specificato è contenuto all'interno di questo`Rectangle`struttura. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Verifica se*obj* è un`Rectangle`struttura con la stessa posizione e dimensione di questa`Rectangle`struttura. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Restituisce il codice hash per questo`Rectangle`struttura. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Gonfia questo`Rectangle`dell'importo specificato. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Gonfia questo`Rectangle`dell'importo specificato. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Sostituisce questo`Rectangle` con l'intersezione di se stesso e lo specificato`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Determina se questo rettangolo si interseca con*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normalizza il rettangolo rendendone la larghezza e l'altezza positive, sinistra minore di destra e superiore minore di inferiore. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Regola la posizione di questo rettangolo in base alla quantità specificata. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Regola la posizione di questo rettangolo in base alla quantità specificata. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Converte gli attributi di this`Rectangle` in una stringa leggibile dall'uomo. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Verifica se due`Rectangle` le strutture hanno la stessa posizione e dimensione. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Verifica se due`Rectangle` le strutture differiscono per posizione o dimensioni. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


