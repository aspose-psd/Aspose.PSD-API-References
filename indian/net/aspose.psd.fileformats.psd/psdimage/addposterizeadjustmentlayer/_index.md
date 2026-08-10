---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage मेथड। Posterize Adjustment लेयर जोड़ता है"
type: docs
weight: 430
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

पोस्टराइज़ एडजस्टमेंट लेयर जोड़ता है।

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### रिटर्न वैल्यू

PosterizeLayer इंस्टेंस।

## उदाहरण

निम्नलिखित कोड PsdImage के माध्यम से PosterizeAdjustmentLayer जोड़ने की क्षमता दर्शाता है।

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// सहेजे गए बदलावों की जाँच करें
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### देखें भी

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


