---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ShapeLayer प्रॉपर्टी। Paths का सेट प्राप्त करता है जो एक Shape लेयर में मौजूद हैं"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Shape लेयर में मौजूद Paths के सेट को प्राप्त करता है।

```csharp
public IPath Path { get; }
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

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


