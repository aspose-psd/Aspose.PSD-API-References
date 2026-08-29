---
title: "Klasse LmskResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource Klasse. Die LMsk-Ressource"
type: docs
weight: 3020
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

Die LMsk-Ressource.

```csharp
public class LmskResource : LayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LmskResource](lmskresource/)() | Initialisiert eine neue Instanz der `LmskResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Liest die Farbkomponente 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Liest die Farbkomponente 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Liest die Farbkomponente 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Liest die Farbkomponente 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Liest den Farbraum. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Liest das Flag. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Liest die Opazität. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

## Hinweise

Diese Ressource enthält die Farbraum-ID, die sich auf einen bestimmten Farbraumtyp bezieht, und 4 Farbkomponenten. Abhängig von der ID haben die Farbkomponenten unterschiedliche Bedeutungen. Wenn der Farbraumtyp nicht vier Werte erfordert, sind die zusätzlichen Komponenten undefiniert und werden immer als Nullen geschrieben. Farbkomponenten nach Farbraumtypen: RGB - die ersten drei Komponenten sind Rot, Grün und Blau. HSB - die ersten drei Komponenten sind Farbton, Sättigung und Helligkeit. CMYK- die vier Komponenten sind Cyan, Magenta, Gelb und Schwarz. Lab - die ersten drei Komponenten sind Helligkeit, a‑Chrominanz und b‑Chrominanz. Grayscale - die erste Komponente ist der Grauwert, von 0...10000.

## Beispiele

Der folgende Code demonstriert, wie man die Anzeigeoptionen der Ebenenmaske bei 16‑Bit‑Bildern durch Ändern der LmskResource‑Eigenschaften ändert.

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

// 16‑Bit‑Bild laden.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource finden.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource‑Eigenschaften prüfen.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource‑Eigenschaften ändern.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Das Bild speichern.
    image.Save(outputPsd);
}
```

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


