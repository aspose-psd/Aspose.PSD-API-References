---
title: "Struktur Size"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Size‑Struktur. Repräsentiert die Größe."
type: docs
weight: 6050
url: /de/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Stellt die Größe dar.

```csharp
public struct Size
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Size](size/#constructor)(Point) | Initialisiert eine neue Instanz der `Size`‑Struktur aus dem angegebenen [`Point`](../point/). |
| [Size](size/#constructor_1)(int, int) | Initialisiert eine neue Instanz der `Size`‑Struktur aus den angegebenen Abmessungen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Liefert eine neue Instanz der `Size`‑Struktur, deren [`Width`](./width/)‑ und [`Height`](./height/)‑Werte auf Null gesetzt sind. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Liefert oder setzt die vertikale Komponente dieser `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Liefert einen Wert, der angibt, ob diese `Size` Breite und Höhe von 0 hat. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Liefert oder setzt die horizontale Komponente dieser `Size`. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Addiert die Breite und Höhe einer `Size`-Struktur zur Breite und Höhe einer anderen `Size`-Struktur. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Konvertiert die angegebene [`SizeF`](../sizef/)-Struktur in eine `Size`-Struktur, indem die Werte der `Size`-Struktur auf die nächsthöheren Ganzzahlen gerundet werden. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Konvertiert die angegebene [`SizeF`](../sizef/)-Struktur in eine `Size`-Struktur, indem die Werte der [`SizeF`](../sizef/)-Struktur auf die nächsten Ganzzahlen gerundet werden. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Subtrahiert die Breite und Höhe einer `Size`-Struktur von der Breite und Höhe einer anderen `Size`-Struktur. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Konvertiert die angegebene [`SizeF`](../sizef/)-Struktur in eine `Size`-Struktur, indem die Werte der [`SizeF`](../sizef/)-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Prüft, ob das angegebene Objekt ein `Size` mit denselben Abmessungen wie dieses `Size` ist. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Gibt einen Hashcode für diese `Size`-Struktur zurück. |
| override [ToString](../../aspose.psd/size/tostring/)() | Erstellt einen menschenlesbaren String, der dieses `Size` darstellt. |
| [operator +](../../aspose.psd/size/op_addition/) | Addiert die Breite und Höhe einer `Size`-Struktur zur Breite und Höhe einer anderen `Size`-Struktur. |
| [operator ==](../../aspose.psd/size/op_equality/) | Prüft, ob zwei `Size`-Strukturen gleich sind. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Konvertiert das angegebene `Size` in ein [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Konvertiert das angegebene `Size` in ein [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Prüft, ob zwei `Size`-Strukturen unterschiedlich sind. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Subtrahiert die Breite und Höhe einer `Size`-Struktur von der Breite und Höhe einer anderen `Size`-Struktur. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


