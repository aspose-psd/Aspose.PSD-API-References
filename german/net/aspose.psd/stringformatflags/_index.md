---
title: "Aufzählung StringFormatFlags"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.StringFormatFlags‑Enum. Gibt die Anzeige‑ und Layoutinformationen für Textzeichenfolgen an."
type: docs
weight: 6180
url: /de/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

Gibt die Anzeige- und Layoutinformationen für Textzeichenfolgen an.

```csharp
[Flags]
public enum StringFormatFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Text wird von rechts nach links angezeigt. |
| DirectionVertical | `2` | Text ist vertikal ausgerichtet. |
| FitBlackBox | `4` | Teile von Zeichen dürfen über das Layout‑Rechteck der Zeichenfolge hinausragen. Standardmäßig werden Zeichen neu positioniert, um ein Überragen zu vermeiden. |
| DisplayFormatControl | `20` | Steuerzeichen wie das Links‑nach‑Rechts‑Markierungssymbol werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt. |
| NoFontFallback | `400` | Das Ausweichen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Fehlende Zeichen werden mit dem fehlenden Glyphen der Schriftart angezeigt, üblicherweise ein offenes Quadrat. |
| MeasureTrailingSpaces | `800` | Beinhaltet das nachfolgende Leerzeichen am Ende jeder Zeile. Standardmäßig schließt das von der MeasureString‑Methode zurückgegebene Begrenzungsrechteck das Leerzeichen am Zeilenende aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung einzubeziehen. |
| NoWrap | `1000` | Der Zeilenumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. Dieses Flag wird impliziert, wenn ein Punkt anstelle eines Rechtecks übergeben wird oder wenn das angegebene Rechteck eine Zeilenlänge von Null hat. |
| LineLimit | `2000` | Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt oder bis keine weiteren Zeilen mehr sichtbar sind aufgrund von Clipping, je nachdem, was zuerst eintritt. Beachten Sie, dass die Standardeinstellungen zulassen, dass die letzte Zeile teilweise von einem Formatierungsrechteck verdeckt wird, das kein ganzzahliges Vielfaches der Zeilenhöhe ist. Um sicherzustellen, dass nur ganze Zeilen angezeigt werden, geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile. |
| NoClip | `4000` | Überstehende Teile von Glyphen und nicht umgebrochener Text, die außerhalb des Formatierungsrechtecks reichen, dürfen angezeigt werden. Standardmäßig werden alle Texte und Glyphen‑Teile, die außerhalb des Formatierungsrechtecks liegen, abgeschnitten. |
| ExactAlignment | `8000` | Die genaue Ausrichtung, korrekte Polsterung GDI+ |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


