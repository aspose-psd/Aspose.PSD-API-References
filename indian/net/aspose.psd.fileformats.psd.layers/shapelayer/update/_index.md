---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ShapeLayer मेथड। Shape layer प्रॉपर्टीज़ से संसाधनों को अपडेट करता है"
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

Shape लेयर गुणों से संसाधनों को अपडेट करता है।

```csharp
public void Update()
```

## उदाहरण

निम्नलिखित कोड ShapeLayer लेयर के समर्थन को दर्शाता है।

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    IPath layerPath = shapeLayer.Path;

    IPathShape[] pathShapeSource = layerPath.GetItems();
    List<IPathShape> pathShapesDest = new List<IPathShape>(pathShapeSource);

    // स्रोत फ़ाइल में 2 आकृतियाँ हैं। दूसरी को हटाएँ।
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### देखें भी

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


