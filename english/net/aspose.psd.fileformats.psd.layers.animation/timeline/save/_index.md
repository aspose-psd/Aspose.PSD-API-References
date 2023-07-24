---
title: Timeline.Save
second_title: Aspose.PSD for .NET API Reference
description: Timeline method. Saves the PsdImages and Timeline data to the specified file location in the specified format according to save options
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Saves the PsdImage's and Timeline data to the specified file location in the specified format according to save options.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| options | ImageOptionsBase | The options. |

## Examples

The following code demonstrates the support of export Timeline to a Gif image.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### See Also

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Saves the PsdImage's and Timeline data to the specified stream in the specified format according to save options.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The output stream. |
| options | ImageOptionsBase | The options. |

## Examples

The following code demonstrates the support of export Timeline to a Gif image.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### See Also

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


