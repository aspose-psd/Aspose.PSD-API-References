---
title: "Timeline.Save"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Timeline-methode. Slaat de PsdImages en Timeline-gegevens op naar de opgegeven bestandslocatie in het opgegeven formaat volgens de opslagopties"
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Slaat de PsdImage's en Timeline-gegevens op naar de opgegeven bestandslocatie in het opgegeven formaat volgens de opslagopties.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| options | ImageOptionsBase | De opties. |

## Voorbeelden

De volgende code toont de ondersteuning voor het exporteren van Timeline naar een GIF-afbeelding.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Zie ook

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Slaat de PsdImage's en Timeline-gegevens op naar de opgegeven stream in het opgegeven formaat volgens de opslagopties.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputStream | Stroom | De uitvoerstream. |
| options | ImageOptionsBase | De opties. |

## Voorbeelden

De volgende code toont de ondersteuning voor het exporteren van Timeline naar een GIF-afbeelding.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Zie ook

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


