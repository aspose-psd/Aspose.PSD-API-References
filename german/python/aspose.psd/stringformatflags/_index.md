---
title: "StringFormatFlags Aufzählung"
type: docs
weight: 6300
url: /de/python-net/aspose.psd/stringformatflags/
---

Gibt die Anzeige- und Layoutinformationen für Textzeichenketten an.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Membername** | **Beschreibung** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Text wird von rechts nach links angezeigt. |
| DIRECTION_VERTICAL | Text ist vertikal ausgerichtet. |
| DISPLAY_FORMAT_CONTROL | Steuerzeichen wie das Links‑nach‑Rechts‑Markierung werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt. |
| EXACT_ALIGNMENT | Die exakte Ausrichtung, korrektes Padding GDI+ |
| FIT_BLACK_BOX | Teile von Zeichen dürfen über das Layout‑Rechteck der Zeichenkette hinausragen. Standardmäßig werden Zeichen neu positioniert, um ein Überragen zu vermeiden. |
| LINE_LIMIT | Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt, oder bis keine weiteren Zeilen mehr sichtbar sind aufgrund von Abschneiden, je nachdem, was zuerst eintritt.<br/>            Beachten Sie, dass die Standardeinstellungen zulassen, dass die letzte Zeile teilweise von einem Formatierungsrechteck verdeckt wird, das kein ganzzahliges Vielfaches der Zeilenhöhe ist. Um sicherzustellen, dass nur ganze Zeilen sichtbar sind,<br/>            geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile. |
| MEASURE_TRAILING_SPACES | Beinhaltet das nachfolgende Leerzeichen am Ende jeder Zeile. Standardmäßig schließt das von der MeasureString‑Methode zurückgegebene Begrenzungsrechteck das Leerzeichen am Ende jeder Zeile aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung einzubeziehen. |
| NO_CLIP | Überstehende Teile von Glyphen und nicht umgebrochener Text, die außerhalb des Formatierungsrechtecks liegen, dürfen angezeigt werden. Standardmäßig werden alle Text‑ und Glyphenteile, die außerhalb des Formatierungsrechtecks liegen, abgeschnitten. |
| NO_FONT_FALLBACK | Das Ausweichen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Fehlende Zeichen werden mit dem fehlenden Glyphen der Schriftart angezeigt, üblicherweise ein offenes Quadrat. |
| NO_WRAP | Der Zeilenumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. Dieses Flag wird impliziert, wenn ein Punkt anstelle eines Rechtecks übergeben wird oder wenn das angegebene Rechteck eine Zeilenlänge von null hat. |
