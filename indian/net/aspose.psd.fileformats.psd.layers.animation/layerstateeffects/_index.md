---
title: Class LayerStateEffects
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects कक्ष. परत स्थत प्रभव.
type: docs
weight: 1870
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
## LayerStateEffects class

परत स्थिति प्रभाव.

```csharp
public class LayerStateEffects
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | परत प्रभाव प्राप्त करता है। |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण दृश्यमान है या नहीं। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | रंग ओवरले प्रभाव जोड़ता है। |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | ड्रॉप शैडो प्रभाव जोड़ता है. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | ग्रेडिएंट ओवरले प्रभाव जोड़ता है. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | आंतरिक छाया प्रभाव जोड़ता है। |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | बाहरी चमक प्रभाव जोड़ता है। |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | पैटर्न ओवरले प्रभाव जोड़ता है। |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | स्ट्रोक प्रभाव जोड़ता है। |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | सभी परत शैली प्रभावों को साफ़ करता है। |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | विशिष्ट सूचकांक पर परत प्रभाव को हटाता है। |

### उदाहरण

निम्न कोड टाइमलाइन फ़्रेम में प्रभावों के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* सभा [Aspose.PSD](../../)


