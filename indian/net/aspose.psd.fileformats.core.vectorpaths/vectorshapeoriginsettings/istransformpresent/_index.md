---
title: "VectorShapeOriginSettings.IsTransformPresent"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VectorShapeOriginSettings प्रॉपर्टी। एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस ट्रांसफ़ॉर्म प्रॉपर्टी रखता है या नहीं"
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

क्या इस उदाहरण में transform property है, यह दर्शाने वाला मान प्राप्त करता है।

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` यदि यह इंस्टेंस ट्रांसफ़ॉर्म प्रॉपर्टी रखता है; अन्यथा, `false`।

## उदाहरण

निम्नलिखित कोड वेक्टर पाथ्स वाले शेप लेयर्स को रिसाइज़ करने की क्षमता दर्शाता है।

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### देखें भी

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


