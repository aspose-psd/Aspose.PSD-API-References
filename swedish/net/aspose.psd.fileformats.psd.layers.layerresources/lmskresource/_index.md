---
title: "Klass LmskResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource-klass. LMsk-resursen"
type: docs
weight: 3020
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

LMsk‑resursen.

```csharp
public class LmskResource : LayerResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LmskResource](lmskresource/)() | Initierar en ny instans av klassen `LmskResource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Hämtar färgkomponent 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Hämtar färgkomponent 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Hämtar färgkomponent 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Hämtar färgkomponent 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Hämtar färgrymden. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Hämtar flaggan. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Hämtar opaciteten. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

## Anmärkningar

Denna resurs innehåller color space ID, som refererar till en specifik färgrymdstyp, och 4 färgkomponenter. Beroende på ID har färgkomponenterna olika betydelser. Om färgrymdstypen inte kräver fyra värden är de extra komponenterna odefinierade och alltid skrivna som nollor. Färgkomponenter efter färgrymdstyper: RGB – de första tre komponenterna är röd, grön och blå. HSB – de första tre komponenterna är nyans, mättnad och ljusstyrka. CMYK – de fyra komponenterna är cyan, magenta, gul och svart. Lab – de första tre komponenterna är ljusstyrka, a‑krominans och b‑krominans. Grayscale – den första komponenten är gråvärdet, från 0…10000.

## Exempel

Följande kod visar hur man ändrar visningsalternativ för lagermask på 16-bitars bilder genom att ändra LmskResource-egenskaper.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Läs in 16-bitars bild.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Hitta LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Kontrollera LmskResource-egenskaper.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Ändra LmskResource-egenskaper.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Spara bilden.
    image.Save(outputPsd);
}
```

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


