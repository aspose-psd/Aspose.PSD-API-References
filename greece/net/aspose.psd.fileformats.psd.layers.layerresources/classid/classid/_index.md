---
title: ClassID.ClassID
second_title: Aspose.PSD για Αναφορά API .NET
description: ClassID κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουClassID τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`ClassID`](../) τάξη.

```csharp
public ClassID(byte[] classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | Byte[] | Το αναγνωριστικό κλάσης ως σειρά byte. |

### Δείτε επίσης

* class [ClassID](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* συνέλευση [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`ClassID`](../) τάξη.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | Byte[] | Το αναγνωριστικό κλάσης ως σειρά byte. |
| isZeroLength | Boolean | εάν έχει οριστεί σε`αληθής` [είναι μηδέν μήκος]. Το καταγεγραμμένο μήκος συμβολοσειράς είναι μηδέν αλλά το πραγματικό είναι τέσσερα. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | classID είναι μηδενικό. |

### Δείτε επίσης

* class [ClassID](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* συνέλευση [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`ClassID`](../) τάξη.

```csharp
public ClassID(int classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | Int32 | Η ταυτότητα της τάξης. |

### Δείτε επίσης

* class [ClassID](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* συνέλευση [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία του[`ClassID`](../) τάξη.

```csharp
public ClassID(uint classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | UInt32 | Η ταυτότητα της τάξης. |

### Δείτε επίσης

* class [ClassID](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* συνέλευση [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία του[`ClassID`](../) τάξη.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | String | Το αναγνωριστικό κλάσης στην κωδικοποίηση ASCII. |
| isZeroLength | Boolean | εάν έχει οριστεί σε`αληθής` [είναι μηδενικό μήκος]. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει ότι το επίπεδο, που εισάγεται από μια εικόνα, μετατρέπεται σε επίπεδο έξυπνου αντικειμένου και το αποθηκευμένο αρχείο PSD είναι σωστό.

```csharp
[C#]

// Ελέγχει ότι το επίπεδο, που εισάγεται από μια εικόνα, μετατρέπεται σε επίπεδο έξυπνου αντικειμένου και ότι το αποθηκευμένο αρχείο PSD είναι σωστό.

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* συνέλευση [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`ClassID`](../) τάξη.

```csharp
public ClassID(string classID)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | String | Το αναγνωριστικό κλάσης στην κωδικοποίηση ASCII. |

### Δείτε επίσης

* class [ClassID](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* συνέλευση [Aspose.PSD](../../../)


