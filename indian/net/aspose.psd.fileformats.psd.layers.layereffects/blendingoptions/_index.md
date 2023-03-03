---
title: Class BlendingOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions कक्ष. सम्मश्रण वकल्प यह Lfx2Resource के लए एक आवरण है ज परत प्रभव के लए एपआई प्रदन करत है
type: docs
weight: 2100
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

सम्मिश्रण विकल्प। यह Lfx2Resource के लिए एक आवरण है जो परत प्रभाव के लिए एपीआई प्रदान करता है

```csharp
public class BlendingOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | प्रभाव प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | रंग ओवरले जोड़ता है. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | ड्रॉप शैडो प्रभाव जोड़ता है. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | ग्रेडिएंट ओवरले जोड़ता है। |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | आंतरिक छाया प्रभाव जोड़ता है। |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | बाहरी चमक प्रभाव जोड़ता है। |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | पैटर्न ओवरले जोड़ता है. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | स्ट्रोक प्रभाव जोड़ता है। |

### उदाहरण

निम्न कोड दर्शाता है कि इनर शैडो लेयर इफेक्ट की सेटिंग्स को कैसे बदलना है।

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* सभा [Aspose.PSD](../../)


