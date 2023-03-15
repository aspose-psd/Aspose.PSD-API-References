---
title: VectorShapeOriginSettings.IsOriginBoxCornersPresent
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VectorShapeOriginSettings संपत्त. एक मन प्रप्त करत है ज इंगत करत है क इस उदहरण में मूल बक्स कनं क संपत्त है य नहं
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

एक मान प्राप्त करता है जो इंगित करता है कि इस उदाहरण में मूल बॉक्स कोनों की संपत्ति है या नहीं।

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### संपत्ति मूल्य

`सत्य` अगर इस उदाहरण में मूल बॉक्स कोनों की संपत्ति है; अन्यथा,`असत्य` .

### उदाहरण

निम्नलिखित कोड वेक्टर पथों वाली आकृति परतों का आकार बदलने की क्षमता प्रदर्शित करता है।

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

### यह सभी देखें

* class [VectorShapeOriginSettings](../)
* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* सभा [Aspose.PSD](../../../)


