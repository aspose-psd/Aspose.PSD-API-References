---
title: "ClassID.ClassID"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur ClassID. Initialise une nouvelle instance de la classe ClassID"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

Initialise une nouvelle instance de la classe [`ClassID`](../).

```csharp
public ClassID(byte[] classID)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classID | Byte[] | L'ID de classe sous forme de série d'octets. |

### Voir aussi

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Initialise une nouvelle instance de la classe [`ClassID`](../).

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classID | Byte[] | L'ID de classe sous forme de série d'octets. |
| isZeroLength | Booléen | si défini sur `true` [est de longueur zéro]. La longueur de chaîne enregistrée est zéro mais la réelle est de quatre. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | classID est nul. |

### Voir aussi

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Initialise une nouvelle instance de la classe [`ClassID`](../).

```csharp
public ClassID(int classID)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classID | Int32 | L'ID de classe. |

### Voir aussi

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Initialise une nouvelle instance de la classe [`ClassID`](../).

```csharp
public ClassID(uint classID)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classID | UInt32 | L'ID de classe. |

### Voir aussi

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Initialise une nouvelle instance de la classe [`ClassID`](../).

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classID | String | L'ID de classe en encodage ASCII. |
| isZeroLength | Booléen | si défini sur `true` [est de longueur zéro]. |

## Exemples

Cet exemple montre que la couche, importée depuis une image, est convertie en couche d'objet dynamique et que le fichier PSD enregistré est correct.

```csharp
[C#]

// Teste que la couche, importée depuis une image, est convertie en couche d'objet dynamique et que le fichier PSD enregistré est correct.

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

### Voir aussi

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Initialise une nouvelle instance de la classe [`ClassID`](../).

```csharp
public ClassID(string classID)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classID | String | L'ID de classe en encodage ASCII. |

### Voir aussi

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


