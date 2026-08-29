---
title: "Klasse RawColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor Klasse. Die Raw Color Klasse hilft, Farben mit beliebiger Kanalanzahl, beliebigem Farbmodus und beliebiger Bit-Tiefe zu speichern. Bitte beachten Sie, dass einige interne Klassen Probleme bei der Konvertierung von RawColor in ihr natives Format haben können, sodass es zuverlässiger ist, das von der API bereitgestellte CMYK-Format zu verwenden, wenn Ihnen ein CMYK-Farbwert bereitgestellt wird. Außerdem kann es Fälle geben, in denen Raw Color konvertiert werden kann."
type: docs
weight: 1650
url: /de/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class hilft, Farben mit beliebiger Kanalanzahl, beliebigem Farbmodus und beliebiger Bit‑Tiefe zu speichern. Bitte beachten Sie, dass einige interne Klassen Probleme bei der Konvertierung von RawColor in ihr natives Format haben können, sodass es zuverlässiger ist, das von der API bereitgestellte CMYK‑Format zu verwenden. Außerdem kann es Fälle geben, in denen Raw Color konvertiert werden kann

```csharp
public sealed class RawColor
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Initialisiert eine neue Instanz der `RawColor` Klasse. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Initialisiert eine neue Instanz der `RawColor` Klasse aus dem Pixeldatenformat unter Verwendung vordefinierter Farbmodi |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Modus für die nachfolgende Farbe. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Liefert die Komponenten der Farbe. Jede Komponente ist ein separater Kanal, und wenn Sie ein nicht gängiges Farbschema verwenden, ist es besser, mit jedem Kanal separat zu arbeiten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Liefert die Farbe als int, falls sie abrufbar ist. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Liefert die Farbe als long, falls sie abrufbar ist. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Liefert die Bit-Tiefe von Raw Color. Zum Beispiel hat eine ARGB-Farbe mit 8 Bit pro Kanal/Komponente eine Bit-Tiefe von 32, die vollständige ARGB-Farbe mit 16 Bit pro Kanal/Komponente hat 64. Die Bit-Tiefe ergibt sich aus der Summe der Bit-Tiefen der Kanäle. Dies ist möglich, wenn verschiedene Kanäle unterschiedliche Bit-Tiefen haben. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Liefert den Namen des Farbmodus. Der Farbmodusname wird aus den Namen der Kanäle/Komponenten zusammengesetzt. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Hashcode des aktuellen Objekts abrufen. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Setzt Daten für alle Kanäle aus dem int-Argument, falls möglich. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Setzt Daten für alle Kanäle aus dem int-Argument, falls möglich. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Implementiert den Operator ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Implementiert den Operator !=. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der RawColor-Klasse anstelle der veralteten Color-Struktur.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


