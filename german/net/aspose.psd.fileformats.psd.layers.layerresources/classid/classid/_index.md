---
title: ClassID.ClassID
second_title: Aspose.PSD für .NET-API-Referenz
description: ClassID constructeur. Initialisiert eine neue Instanz vonClassID Klasse.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Initialisiert eine neue Instanz von[`ClassID`](../) Klasse.

```csharp
public ClassID(byte[] classID)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classID | Byte[] | Die Klassen-ID als Folge von Bytes. |

### Siehe auch

* class [ClassID](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* Montage [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Initialisiert eine neue Instanz von[`ClassID`](../) Klasse.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classID | Byte[] | Die Klassen-ID als Folge von Bytes. |
| isZeroLength | Boolean | wenn eingestellt`WAHR` [ist eine Länge von null]. Die aufgezeichnete Zeichenfolgenlänge ist null, aber die tatsächliche ist vier. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | classID ist null. |

### Siehe auch

* class [ClassID](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* Montage [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Initialisiert eine neue Instanz von[`ClassID`](../) Klasse.

```csharp
public ClassID(int classID)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classID | Int32 | Die Klassen-ID. |

### Siehe auch

* class [ClassID](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* Montage [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Initialisiert eine neue Instanz von[`ClassID`](../) Klasse.

```csharp
public ClassID(uint classID)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classID | UInt32 | Die Klassen-ID. |

### Siehe auch

* class [ClassID](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* Montage [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Initialisiert eine neue Instanz von[`ClassID`](../) Klasse.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classID | String | Die Klassen-ID in ASCII-Codierung. |
| isZeroLength | Boolean | wenn eingestellt`WAHR` [ist eine Länge von Null]. |

### Beispiele

Dieses Beispiel zeigt, dass die aus einem Bild importierte Ebene in eine intelligente Objektebene konvertiert wird und die gespeicherte PSD-Datei korrekt ist.

```csharp
[C#]

// Testet, ob die aus einem Bild importierte Ebene in eine intelligente Objektebene konvertiert wird und die gespeicherte PSD-Datei korrekt ist.

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

### Siehe auch

* class [ClassID](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* Montage [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Initialisiert eine neue Instanz von[`ClassID`](../) Klasse.

```csharp
public ClassID(string classID)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classID | String | Die Klassen-ID in ASCII-Codierung. |

### Siehe auch

* class [ClassID](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* Montage [Aspose.PSD](../../../)


