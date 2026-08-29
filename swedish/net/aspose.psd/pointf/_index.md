---
title: "Struktur PointF"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.PointF struct. Representerar ett ordnat par av flyttal‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan."
type: docs
weight: 5770
url: /sv/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

Representerar ett ordnat par av flyttals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.

```csharp
public struct PointF
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PointF](pointf/)(float, float) | Initierar en ny instans av strukturen `PointF` med de angivna koordinaterna. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Hämtar en ny instans av strukturen `PointF` som har [`X`](./x/) och [`Y`](./y/) värden satta till noll. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Hämtar ett värde som indikerar om denna `PointF` är tom. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Hämtar eller anger x‑koordinaten för denna `PointF`. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Hämtar eller anger y‑koordinaten för denna `PointF`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Översätter en given `PointF` med den angivna [`Size`](../size/). |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Översätter en given `PointF` med en specificerad [`SizeF`](../sizef/). |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Översätter en `PointF` med den negativa av en specificerad storlek. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Översätter en `PointF` med den negativa av en specificerad storlek. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Anger om denna `PointF` innehåller samma koordinater som det angivna objektet. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Returnerar en hashkod för denna `PointF`‑struktur. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Konverterar denna `PointF` till en människoläsbar sträng. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Översätter en `PointF` med en given [`Size`](../size/). (2 operatorer) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | Jämför två `PointF`‑strukturer. Resultatet anger om värdena för [`X`](./x/) och [`Y`](./y/) egenskaperna hos de två `PointF`‑strukturerna är lika. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Bestämmer om koordinaterna för de angivna punkterna inte är lika. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Översätter en `PointF` med den negativa av en given [`Size`](../size/). (2 operatorer) |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


