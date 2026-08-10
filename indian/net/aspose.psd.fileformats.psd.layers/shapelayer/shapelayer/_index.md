---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ShapeLayer कंस्ट्रक्टर। ShapeLayer क्लास का एक नया उदाहरण प्रारंभ करता है। सभी संसाधन डिफ़ॉल्ट स्थिति में बनाए जाते हैं"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

एक नया उदाहरण प्रारंभ करता है [`ShapeLayer`](../) क्लास का। सभी संसाधन डिफ़ॉल्ट स्थिति में बनाए जाते हैं।

```csharp
public ShapeLayer()
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


