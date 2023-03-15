---
title: PsdImage.Rotate
second_title: Aspose.PSD voor .NET API-referentie
description: PsdImage methode. Afbeelding roteren rond het midden.
type: docs
weight: 610
url: /nl/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Afbeelding roteren rond het midden.

```csharp
public override void Rotate(float angle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | Single | De draaihoek in graden. Positieve waarden draaien met de klok mee. |

### Voorbeelden

De volgende code demonstreert de mogelijkheid om de afbeelding te roteren met een specifieke hoekwaarde.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Gehele afbeelding roterend
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

// Lagen roteren
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

### Zie ook

* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Afbeelding roteren rond het midden.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | Single | De draaihoek in graden. Positieve waarden draaien met de klok mee. |
| resizeProportionally | Boolean | indien ingesteld op`WAAR` u zult uw afbeeldingsgrootte laten wijzigen volgens projecties van geroteerde rechthoeken (hoekpunten), in andere gevallen blijven de afmetingen onaangeroerd en wordt alleen de interne afbeeldingsinhoud geroteerd. |
| backgroundColor | Color | Kleur van de achtergrond. |

### Zie ook

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)


