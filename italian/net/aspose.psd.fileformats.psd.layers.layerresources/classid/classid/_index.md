---
title: ClassID.ClassID
second_title: Aspose.PSD per riferimento API .NET
description: ClassID costruttore. Inizializza una nuova istanza diClassID classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Inizializza una nuova istanza di[`ClassID`](../) classe.

```csharp
public ClassID(byte[] classID)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | Byte[] | L'ID classe come serie di byte. |

### Guarda anche

* class [ClassID](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* assemblea [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Inizializza una nuova istanza di[`ClassID`](../) classe.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | Byte[] | L'ID classe come serie di byte. |
| isZeroLength | Boolean | se impostato su`VERO` [è lunghezza zero]. La lunghezza della stringa registrata è zero ma quella effettiva è quattro. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | classID è nullo. |

### Guarda anche

* class [ClassID](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* assemblea [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Inizializza una nuova istanza di[`ClassID`](../) classe.

```csharp
public ClassID(int classID)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | Int32 | L'ID della classe. |

### Guarda anche

* class [ClassID](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* assemblea [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Inizializza una nuova istanza di[`ClassID`](../) classe.

```csharp
public ClassID(uint classID)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | UInt32 | L'ID della classe. |

### Guarda anche

* class [ClassID](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* assemblea [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Inizializza una nuova istanza di[`ClassID`](../) classe.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | String | L'ID classe nella codifica ASCII. |
| isZeroLength | Boolean | se impostato su`VERO` [è di lunghezza zero]. |

### Esempi

Questo esempio dimostra che il livello, importato da un'immagine, viene convertito in livello oggetto avanzato e il file PSD salvato è corretto.

```csharp
[C#]

// Verifica che il livello, importato da un'immagine, sia convertito in livello oggetto intelligente e che il file PSD salvato sia corretto.

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

### Guarda anche

* class [ClassID](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* assemblea [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Inizializza una nuova istanza di[`ClassID`](../) classe.

```csharp
public ClassID(string classID)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classID | String | L'ID classe nella codifica ASCII. |

### Guarda anche

* class [ClassID](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* assemblea [Aspose.PSD](../../../)


