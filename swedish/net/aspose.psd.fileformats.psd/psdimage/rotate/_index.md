---
title: PsdImage.Rotate
second_title: Aspose.PSD för .NET API-referens
description: PsdImage metod. Rotera bilden runt mitten.
type: docs
weight: 610
url: /sv/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Rotera bilden runt mitten.

```csharp
public override void Rotate(float angle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | Single | Rotationsvinkeln i grader. Positiva värden kommer att rotera medurs. |

### Exempel

Följande kod visar förmågan att rotera bilden med ett specifikt vinkelvärde.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Hela bilden roterar
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

// Lager som roterar
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

### Se även

* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Rotera bilden runt mitten.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | Single | Rotationsvinkeln i grader. Positiva värden kommer att rotera medurs. |
| resizeProportionally | Boolean | om inställt på`Sann` du kommer att få din bildstorlek ändrad enligt projicering av roterade rektangel (hörnpunkter) i andra fall som lämnar dimensioner orörda och endast interna bildinnehåll roteras. |
| backgroundColor | Color | Färg på bakgrunden. |

### Se även

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)


