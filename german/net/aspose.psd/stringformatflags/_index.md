---
title: Enum StringFormatFlags
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.StringFormatFlags opsomming. Gibt die Anzeige und Layoutinformationen für Textzeichenfolgen an.
type: docs
weight: 5680
url: /de/net/aspose.psd/stringformatflags/
---
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
| FitBlackBox | `4` | Teile von Zeichen dürfen über das Layoutrechteck der Zeichenfolge hinausragen. Standardmäßig werden Zeichen neu positioniert, um Überhänge zu vermeiden. |
| DisplayFormatControl | `20` | Steuerzeichen wie die Links-nach-rechts-Markierung werden in der Ausgabe mit einer repräsentativen Glyphe angezeigt. |
| NoFontFallback | `400` | Fallback auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Alle fehlenden Zeichen werden mit der fehlenden Glyphe der Schriftart angezeigt, normalerweise ein offenes Quadrat. |
| MeasureTrailingSpaces | `800` | Enthält das nachstehende Leerzeichen am Ende jeder Zeile. Standardmäßig schließt das von der MeasureString-Methode zurückgegebene Begrenzungsrechteck den Leerraum am Ende jeder Zeile aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung einzubeziehen. |
| NoWrap | `1000` | Textumbruch zwischen Zeilen, wenn die Formatierung innerhalb eines Rechtecks deaktiviert ist. Dieses Flag wird impliziert, wenn anstelle eines Rechtecks ein Punkt übergeben wird oder wenn das angegebene Rechteck eine Linienlänge von null hat. |
| LineLimit | `2000` | Im Formatierungsrechteck werden nur ganze Zeilen angelegt. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt oder bis keine Zeilen mehr sichtbar sind, je nachdem, was zuerst eintritt. Beachten Sie, dass die Standardeinstellungen zulassen, dass die letzte Zeile teilweise durch ein Formatierungsrechteck verdeckt wird, das kein ist ganze Vielfache der Zeilenhöhe. Um sicherzustellen, dass nur ganze Zeilen angezeigt werden, geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile. |
| NoClip | `4000` | Überhängende Teile von Glyphen und nicht umbrochener Text, der über das Formatierungsrechteck hinausreicht, dürfen angezeigt werden. Standardmäßig werden alle Text- und Glyphenteile, die außerhalb des Formatierungsrechtecks liegen, abgeschnitten. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


