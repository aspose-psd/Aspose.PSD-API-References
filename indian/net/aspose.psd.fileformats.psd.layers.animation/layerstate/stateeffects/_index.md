---
title: LayerState.StateEffects
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerState संपत्त. परत स्थत प्रभव प्रप्त करत है
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

परत स्थिति प्रभाव प्राप्त करता है।

```csharp
public LayerStateEffects StateEffects { get; }
```

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

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* सभा [Aspose.PSD](../../../)


