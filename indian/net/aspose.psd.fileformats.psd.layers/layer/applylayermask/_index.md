---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Layer method. लेयर पर लेयर मास्क लागू करता है और फिर मास्क को हटाता है"
type: docs
weight: 350
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

लेयर पर लेयर मास्क लागू करता है, फिर मास्क को हटाता है।

```csharp
public void ApplyLayerMask()
```

## उदाहरण

निम्नलिखित कोड लेयर पर मास्क लागू करने की सुविधा को दर्शाता है।

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### देखें भी

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


