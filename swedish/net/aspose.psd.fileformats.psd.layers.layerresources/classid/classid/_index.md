---
title: ClassID.ClassID
second_title: Aspose.PSD för .NET API-referens
description: ClassID byggare. Initierar en ny instans avClassID class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Initierar en ny instans av[`ClassID`](../) class.

```csharp
public ClassID(byte[] classID)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | Byte[] | Klass-ID som serie av byte. |

### Se även

* class [ClassID](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* hopsättning [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Initierar en ny instans av[`ClassID`](../) class.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | Byte[] | Klass-ID som serie av byte. |
| isZeroLength | Boolean | om inställt på`Sann` [är noll längd]. Den inspelade stränglängden är noll men den faktiska är fyra. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | classID är null. |

### Se även

* class [ClassID](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* hopsättning [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Initierar en ny instans av[`ClassID`](../) class.

```csharp
public ClassID(int classID)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | Int32 | Klass-ID. |

### Se även

* class [ClassID](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* hopsättning [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Initierar en ny instans av[`ClassID`](../) class.

```csharp
public ClassID(uint classID)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | UInt32 | Klass-ID. |

### Se även

* class [ClassID](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* hopsättning [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Initierar en ny instans av[`ClassID`](../) class.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | String | Klass-ID i ASCII-kodning. |
| isZeroLength | Boolean | om inställt på`Sann` [är noll längd]. |

### Exempel

Det här exemplet visar att lagret, importerat från en bild, konverteras till smart objektlager och att den sparade PSD-filen är korrekt.

```csharp
[C#]

// Testar att lagret, importerat från en bild, konverteras till smart objektlager och att den sparade PSD-filen är korrekt.

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

### Se även

* class [ClassID](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* hopsättning [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Initierar en ny instans av[`ClassID`](../) class.

```csharp
public ClassID(string classID)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | String | Klass-ID i ASCII-kodning. |

### Se även

* class [ClassID](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* hopsättning [Aspose.PSD](../../../)


