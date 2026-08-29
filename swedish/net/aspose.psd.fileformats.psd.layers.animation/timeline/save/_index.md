---
title: "Timeline.Save"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Timeline‑metod. Sparar PsdImages och Timeline‑data till den angivna filplatsen i det angivna formatet enligt sparalternativ."
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Sparar PsdImage‑ och Timeline‑data till den angivna filplatsen i det angivna formatet enligt sparalternativ.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| alternativ | ImageOptionsBase | Alternativen. |

## Exempel

Följande kod demonstrerar stöd för att exportera Timeline till en GIF‑bild.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Sparar PsdImage‑ och Timeline‑data till den angivna strömmen i det angivna formatet enligt sparalternativ.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Utdata‑strömmen. |
| alternativ | ImageOptionsBase | Alternativen. |

## Exempel

Följande kod demonstrerar stöd för att exportera Timeline till en GIF‑bild.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Se även

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


