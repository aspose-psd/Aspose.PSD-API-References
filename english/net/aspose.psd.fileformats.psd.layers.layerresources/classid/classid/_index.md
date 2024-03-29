---
title: ClassID.ClassID
second_title: Aspose.PSD for .NET API Reference
description: ClassID constructor. Initializes a new instance of the ClassID class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

Initializes a new instance of the [`ClassID`](../) class.

```csharp
public ClassID(byte[] classID)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classID | Byte[] | The class ID as series of bytes. |

### See Also

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Initializes a new instance of the [`ClassID`](../) class.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classID | Byte[] | The class ID as series of bytes. |
| isZeroLength | Boolean | if set to `true` [is zero length]. The recorded string length is zero but actual is four. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | classID is null. |

### See Also

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Initializes a new instance of the [`ClassID`](../) class.

```csharp
public ClassID(int classID)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classID | Int32 | The class ID. |

### See Also

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Initializes a new instance of the [`ClassID`](../) class.

```csharp
public ClassID(uint classID)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classID | UInt32 | The class ID. |

### See Also

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Initializes a new instance of the [`ClassID`](../) class.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classID | String | The class ID in ASCII encoding. |
| isZeroLength | Boolean | if set to `true` [is zero length]. |

## Examples

This example demonstrates that that the layer, imported from an image, is converted to smart object layer and the saved PSD file is correct.

```csharp
[C#]

// Tests that the layer, imported from an image, is converted to smart object layer and the saved PSD file is correct.

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

### See Also

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Initializes a new instance of the [`ClassID`](../) class.

```csharp
public ClassID(string classID)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classID | String | The class ID in ASCII encoding. |

### See Also

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


