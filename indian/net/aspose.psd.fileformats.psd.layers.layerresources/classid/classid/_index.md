---
title: "ClassID.ClassID"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ClassID कंस्ट्रक्टर। ClassID क्लास का नया उदाहरण प्रारंभ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

एक नया उदाहरण प्रारंभ करता है [`ClassID`](../) क्लास का।

```csharp
public ClassID(byte[] classID)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classID | Byte[] | क्लास ID बाइट्स की श्रृंखला के रूप में। |

### देखें भी

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

एक नया उदाहरण प्रारंभ करता है [`ClassID`](../) क्लास का।

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classID | Byte[] | क्लास ID बाइट्स की श्रृंखला के रूप में। |
| isZeroLength | बूलियन | यदि `true` पर सेट किया गया है [शून्य लंबाई है]। दर्ज किया गया स्ट्रिंग लंबाई शून्य है लेकिन वास्तविक चार है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | classID शून्य है। |

### देखें भी

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

एक नया उदाहरण प्रारंभ करता है [`ClassID`](../) क्लास का।

```csharp
public ClassID(int classID)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classID | Int32 | क्लास आईडी। |

### देखें भी

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

एक नया उदाहरण प्रारंभ करता है [`ClassID`](../) क्लास का।

```csharp
public ClassID(uint classID)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classID | UInt32 | क्लास आईडी। |

### देखें भी

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

एक नया उदाहरण प्रारंभ करता है [`ClassID`](../) क्लास का।

```csharp
public ClassID(string classID, bool isZeroLength)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classID | String | ASCII एन्कोडिंग में क्लास ID। |
| isZeroLength | बूलियन | यदि `true` पर सेट किया गया है [शून्य लंबाई है]। |

## उदाहरण

यह उदाहरण दर्शाता है कि छवि से आयात किया गया लेयर स्मार्ट ऑब्जेक्ट लेयर में परिवर्तित हो जाता है और सहेजी गई PSD फ़ाइल सही है।

```csharp
[C#]

// परीक्षण करता है कि छवि से आयात किया गया लेयर स्मार्ट ऑब्जेक्ट लेयर में परिवर्तित हो जाता है और सहेजी गई PSD फ़ाइल सही है।

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

### देखें भी

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

एक नया उदाहरण प्रारंभ करता है [`ClassID`](../) क्लास का।

```csharp
public ClassID(string classID)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classID | String | ASCII एन्कोडिंग में क्लास ID। |

### देखें भी

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


