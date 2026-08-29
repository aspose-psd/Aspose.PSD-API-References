---
title: "LayerState.StateEffects"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerState प्रॉपर्टी. लेयर स्टेट इफ़ेक्ट्स को प्राप्त करता है"
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
{{< psd/tize >}}
## LayerState.StateEffects property

लेयर स्टेट इफ़ेक्ट्स को प्राप्त करता है।

```csharp
public LayerStateEffects StateEffects { get; }
```

## उदाहरण

निम्नलिखित कोड टाइमलाइन फ्रेम्स में इफ़ेक्ट्स के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### देखें भी

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


