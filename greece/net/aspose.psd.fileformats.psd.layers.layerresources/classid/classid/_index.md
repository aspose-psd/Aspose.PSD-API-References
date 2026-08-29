---
title: "ClassID.ClassID"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής ClassID. Αρχικοποιεί μια νέα παρουσία της κλάσης ClassID"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`ClassID`](../).

```csharp
public ClassID(byte[] classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | Byte[] | Το αναγνωριστικό κλάσης ως σειρά byte. |

### Δείτε επίσης

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`ClassID`](../).

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | Byte[] | Το αναγνωριστικό κλάσης ως σειρά byte. |
| isZeroLength | Boolean | αν οριστεί σε `true` [είναι μηδενικού μήκους]. Το καταγεγραμμένο μήκος της συμβολοσειράς είναι μηδέν αλλά το πραγματικό είναι τέσσερα. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Το classID είναι null. |

### Δείτε επίσης

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`ClassID`](../).

```csharp
public ClassID(int classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | Int32 | Το ID της κλάσης. |

### Δείτε επίσης

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`ClassID`](../).

```csharp
public ClassID(uint classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | UInt32 | Το ID της κλάσης. |

### Δείτε επίσης

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`ClassID`](../).

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | String | Το αναγνωριστικό κλάσης σε κωδικοποίηση ASCII. |
| isZeroLength | Boolean | αν οριστεί σε `true` [είναι μηδενικού μήκους]. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει ότι η στρώση, εισήχθη από μια εικόνα, μετατρέπεται σε στρώση έξυπνου αντικειμένου και το αποθηκευμένο αρχείο PSD είναι σωστό.

```csharp
[C#]

// Δοκιμάζει ότι η στρώση, εισήχθη από μια εικόνα, μετατρέπεται σε στρώση έξυπνου αντικειμένου και το αποθηκευμένο αρχείο PSD είναι σωστό.

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

### Δείτε επίσης

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`ClassID`](../).

```csharp
public ClassID(string classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | String | Το αναγνωριστικό κλάσης σε κωδικοποίηση ASCII. |

### Δείτε επίσης

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


