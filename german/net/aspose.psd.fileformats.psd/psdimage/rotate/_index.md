---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Methode. Bild um das Zentrum drehen"
type: docs
weight: 670
url: /de/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Dreht das Bild um die Mitte.

```csharp
public override void Rotate(float angle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | Single | Der Drehwinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

## Beispiele

Der folgende Code demonstriert die Fähigkeit, das Bild um einen bestimmten Winkelwert zu drehen.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Gesamtes Bild drehen
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Ebene drehen
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Siehe auch

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Dreht das Bild um die Mitte.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | Single | Der Drehwinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | Boolean | Wenn auf `true` gesetzt, wird die Bildgröße entsprechend den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der interne Bildinhalt wird gedreht. |
| backgroundColor | Farbe | Farbe des Hintergrunds. |

### Siehe auch

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


