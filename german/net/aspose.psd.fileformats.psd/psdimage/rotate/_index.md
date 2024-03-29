---
title: PsdImage.Rotate
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdImage methode. Bild um die Mitte drehen.
type: docs
weight: 610
url: /de/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Bild um die Mitte drehen.

```csharp
public override void Rotate(float angle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | Single | Der Drehwinkel in Grad. Positive Werte rotieren im Uhrzeigersinn. |

### Beispiele

Der folgende Code demonstriert die Möglichkeit, das Bild um einen bestimmten Winkelwert zu drehen.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Ganzes Bild rotiert
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

// Layer rotiert
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
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Bild um die Mitte drehen.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | Single | Der Drehwinkel in Grad. Positive Werte rotieren im Uhrzeigersinn. |
| resizeProportionally | Boolean | wenn eingestellt`WAHR` Sie werden Ihre Bildgröße entsprechend den Projektionen des gedrehten Rechtecks (Eckpunkte) ändern lassen, in einem anderen Fall, der die Abmessungen unberührt lässt und nur interne Bildinhalte gedreht werden. |
| backgroundColor | Color | Farbe des Hintergrunds. |

### Siehe auch

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)


