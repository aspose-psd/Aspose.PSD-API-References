---
title: ClassID.ClassID
second_title: Aspose.PSD voor .NET API-referentie
description: ClassID constructeur. Initialiseert een nieuw exemplaar van hetClassID klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Initialiseert een nieuw exemplaar van het[`ClassID`](../) klasse.

```csharp
public ClassID(byte[] classID)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | Byte[] | De klasse-ID als reeks bytes. |

### Zie ook

* class [ClassID](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* montage [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`ClassID`](../) klasse.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | Byte[] | De klasse-ID als reeks bytes. |
| isZeroLength | Boolean | indien ingesteld op`WAAR` [is nul lengte]. De geregistreerde stringlengte is nul maar de werkelijke lengte is vier. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | classID is null. |

### Zie ook

* class [ClassID](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* montage [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`ClassID`](../) klasse.

```csharp
public ClassID(int classID)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | Int32 | De klasse-ID. |

### Zie ook

* class [ClassID](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* montage [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Initialiseert een nieuw exemplaar van het[`ClassID`](../) klasse.

```csharp
public ClassID(uint classID)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | UInt32 | De klasse-ID. |

### Zie ook

* class [ClassID](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* montage [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Initialiseert een nieuw exemplaar van het[`ClassID`](../) klasse.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | String | De klasse-ID in ASCII-codering. |
| isZeroLength | Boolean | indien ingesteld op`WAAR` [is nul lengte]. |

### Voorbeelden

Dit voorbeeld laat zien dat de laag, geïmporteerd uit een afbeelding, is geconverteerd naar een slimme objectlaag en dat het opgeslagen PSD-bestand correct is.

```csharp
[C#]

// Test of de laag, geïmporteerd uit een afbeelding, is geconverteerd naar een slimme objectlaag en of het opgeslagen PSD-bestand correct is.

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Zie ook

* class [ClassID](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* montage [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`ClassID`](../) klasse.

```csharp
public ClassID(string classID)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | String | De klasse-ID in ASCII-codering. |

### Zie ook

* class [ClassID](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* montage [Aspose.PSD](../../../)


