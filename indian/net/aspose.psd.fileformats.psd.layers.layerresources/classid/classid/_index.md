---
title: ClassID.ClassID
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ClassID नर्मत. क एक नय उदहरण प्ररंभ करत हैClassID वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`ClassID`](../) वर्ग.

```csharp
public ClassID(byte[] classID)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | Byte[] | वर्ग आईडी बाइट्स की श्रृंखला के रूप में। |

### यह सभी देखें

* class [ClassID](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* सभा [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`ClassID`](../) वर्ग.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | Byte[] | वर्ग आईडी बाइट्स की श्रृंखला के रूप में। |
| isZeroLength | Boolean | अगर सेट है`सत्य` [शून्य लंबाई है]. रिकॉर्ड की गई स्ट्रिंग लंबाई शून्य है लेकिन वास्तविक चार है. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | क्लासआईडी शून्य है। |

### यह सभी देखें

* class [ClassID](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* सभा [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`ClassID`](../) वर्ग.

```csharp
public ClassID(int classID)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | Int32 | कक्षा आईडी। |

### यह सभी देखें

* class [ClassID](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* सभा [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`ClassID`](../) वर्ग.

```csharp
public ClassID(uint classID)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | UInt32 | कक्षा आईडी। |

### यह सभी देखें

* class [ClassID](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* सभा [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`ClassID`](../) वर्ग.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | String | ASCII एन्कोडिंग में वर्ग आईडी। |
| isZeroLength | Boolean | अगर सेट है`सत्य` [शून्य लंबाई है]। |

### उदाहरण

यह उदाहरण दर्शाता है कि एक छवि से आयात की गई परत, स्मार्ट ऑब्जेक्ट परत में परिवर्तित हो जाती है और सहेजी गई PSD फ़ाइल सही है।

```csharp
[C#]

// परीक्षण करता है कि एक छवि से आयातित परत, स्मार्ट ऑब्जेक्ट परत में परिवर्तित हो जाती है और सहेजी गई PSD फ़ाइल सही है।

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

### यह सभी देखें

* class [ClassID](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* सभा [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`ClassID`](../) वर्ग.

```csharp
public ClassID(string classID)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | String | ASCII एन्कोडिंग में वर्ग आईडी। |

### यह सभी देखें

* class [ClassID](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* सभा [Aspose.PSD](../../../)


