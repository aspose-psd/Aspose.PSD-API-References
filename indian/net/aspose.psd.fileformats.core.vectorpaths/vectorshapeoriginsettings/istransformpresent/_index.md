---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VectorShapeOriginSettings संपत्त. यह इंगत करने वल मन प्रप्त करत है क क्य इस उदहरण में रूपंतरण गुण है
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में रूपांतरण गुण है।

```csharp
public bool IsTransformPresent { get; }
```

### संपत्ति मूल्य

`सत्य` यदि इस उदाहरण में परिवर्तन संपत्ति है; अन्यथा,`असत्य` .

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


