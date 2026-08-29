---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage metod. Rotera bilden kring centrum"
type: docs
weight: 670
url: /sv/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Rotera bilden kring centrum.

```csharp
public override void Rotate(float angle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | Single | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

## Exempel

Följande kod demonstrerar möjligheten att rotera bilden med ett specifikt vinkelvärde.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotering av hela bilden
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

// Rotering av lager
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
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Rotera bilden kring centrum.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | Single | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | Boolean | Om den är satt till `true` kommer bildens storlek att ändras enligt de roterade rektangelns (hörnpunkternas) projektioner; annars lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | Färg | Bakgrundens färg. |

### Se även

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


