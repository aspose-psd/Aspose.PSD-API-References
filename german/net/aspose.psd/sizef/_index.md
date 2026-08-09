---
title: "Struktur SizeF"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.SizeF-Struktur. Speichert ein geordnetes Paar von Fließkommazahlen, typischerweise die Breite und Höhe eines Rechtecks"
type: docs
weight: 6060
url: /de/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Speichert ein geordnetes Paar von Gleitkommazahlen, typischerweise die Breite und Höhe eines Rechtecks.

```csharp
public struct SizeF
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Initialisiert eine neue Instanz der `SizeF`-Struktur aus dem angegebenen [`PointF`](../pointf/). |
| [SizeF](sizef/#constructor_1)(SizeF) | Initialisiert eine neue Instanz der `SizeF`-Struktur aus dem angegebenen `SizeF`. |
| [SizeF](sizef/#constructor_2)(float, float) | Initialisiert eine neue Instanz der `SizeF`-Struktur aus den angegebenen Abmessungen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Gibt eine neue Instanz der `SizeF`-Struktur zurück, deren [`Width`](./width/)- und [`Height`](./height/)-Werte auf Null gesetzt sind. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Liest oder setzt die vertikale Komponente dieses `SizeF`. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Liest einen Wert, der angibt, ob dieses `SizeF` Breite und Höhe gleich Null hat. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Liest oder setzt die horizontale Komponente dieses `SizeF`. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Addiert die Breite und Höhe einer `SizeF`-Struktur zur Breite und Höhe einer anderen `SizeF`-Struktur. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Subtrahiert die Breite und Höhe einer `SizeF`-Struktur von der Breite und Höhe einer anderen `SizeF`-Struktur. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Prüft, ob das angegebene Objekt ein `SizeF` mit denselben Abmessungen wie dieses `SizeF` ist. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Gibt einen Hashcode für diese [`Size`](../size/)-Struktur zurück. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Konvertiert ein `SizeF` in ein [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Konvertiert ein `SizeF` in eine [`Size`](../size/)-Struktur mit abgeschnittenen Größenwerten. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Erstellt einen menschenlesbaren String, der dieses `SizeF` darstellt. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Addiert die Breite und Höhe einer `SizeF`-Struktur zur Breite und Höhe einer anderen `SizeF`-Struktur. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Testet, ob zwei `SizeF`-Strukturen gleich sind. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Konvertiert das angegebene `SizeF` in ein [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Testet, ob zwei `SizeF`-Strukturen unterschiedlich sind. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Subtrahiert die Breite und Höhe einer `SizeF`-Struktur von der Breite und Höhe einer anderen `SizeF`-Struktur. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


