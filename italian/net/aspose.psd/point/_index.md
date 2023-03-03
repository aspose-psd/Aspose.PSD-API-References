---
title: Struct Point
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Point struct. Rappresenta una coppia ordinata di coordinate x e y intere che definisce un punto in un piano bidimensionale.
type: docs
weight: 5260
url: /it/net/aspose.psd/point/
---
## Point structure

Rappresenta una coppia ordinata di coordinate x e y intere che definisce un punto in un piano bidimensionale.

```csharp
public struct Point
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Point](point/#constructor_1)(int) | Inizializza una nuova istanza di`Point` struttura utilizzando le coordinate specificate da un valore intero. |
| [Point](point/#constructor)(Size) | Inizializza una nuova istanza di`Point` struttura dal[`Size`](../size/)struttura. |
| [Point](point/#constructor_2)(int, int) | Inizializza una nuova istanza di`Point` struttura con le coordinate specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Ottiene una nuova istanza di`Point` struttura che ha[`X`](./x/) E[`Y`](./y/) valori impostati a zero. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Ottiene un valore che indica se this`Point` è vuoto. |
| [X](../../aspose.psd/point/x/) { get; set; } | Ottiene o imposta la coordinata x di this`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Ottiene o imposta la coordinata y di this`Point` . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Aggiunge l'oggetto specificato[`Size`](../size/) allo specificato`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Converte l'oggetto specificato[`PointF`](../pointf/) ad un`Point` arrotondando i valori di[`PointF`](../pointf/) ai successivi valori interi più alti. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Converte l'oggetto specificato[`PointF`](../pointf/) ad un`Point` oggetto arrotondando l'`Point` valori al numero intero più vicino. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Restituisce il risultato della sottrazione specificata[`Size`](../size/) da quanto specificato`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Converte l'oggetto specificato[`PointF`](../pointf/) ad un`Point` troncando i valori di`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Specifica se this`Point` contiene le stesse coordinate di specificatoObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Restituisce un codice hash per questo`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Traduce questo`Point` da quanto specificato`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Traduce questo`Point`dell'importo specificato. |
| override [ToString](../../aspose.psd/point/tostring/)() | Converte questo`Point` in una stringa leggibile dall'uomo. |
| [operator +](../../aspose.psd/point/op_addition/) | Traduce a`Point` da un dato[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Confronta due`Point` oggetti. Il risultato specifica se i valori di[`X`](./x/) E[`Y`](./y/) proprietà dei due`Point` gli oggetti sono uguali. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Converte l'oggetto specificato`Point` struttura ad a[`Size`](../size/)struttura. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Converte l'oggetto specificato`Point` struttura al[`PointF`](../pointf/)struttura. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Confronta due`Point` oggetti. Il risultato specifica se i valori di[`X`](./x/) O[`Y`](./y/) proprietà dei due`Point` gli oggetti sono disuguali. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Traduce a`Point` dal negativo di un dato[`Size`](../size/) . |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


