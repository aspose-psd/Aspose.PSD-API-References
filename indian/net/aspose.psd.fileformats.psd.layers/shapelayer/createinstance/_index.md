---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ShapeLayer मेथड। ShapeLayer क्लास का नया इंस्टेंस बनाता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

[`ShapeLayer`](../) क्लास का नया इंस्टेंस बनाता है।

```csharp
public static ShapeLayer CreateInstance()
```

### रिटर्न वैल्यू

[`ShapeLayer`](../) क्लास का नया इंस्टेंस लौटाता है।

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


