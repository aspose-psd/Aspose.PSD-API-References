---
title: "Timeline.Save"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Timeline-Methode. Speichert die PsdImages und Timeline-Daten am angegebenen Dateipfad im angegebenen Format gemäß den Speicheroptionen."
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Speichert die Daten von PsdImage und Timeline am angegebenen Dateipfad im angegebenen Format gemäß den Speicheroptionen.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| Optionen | ImageOptionsBase | Die Optionen. |

## Beispiele

Der folgende Code demonstriert die Unterstützung des Exports der Timeline in ein Gif‑Bild.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Speichert die Daten von PsdImage und Timeline in den angegebenen Stream im angegebenen Format gemäß den Speicheroptionen.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Ausgabestream. |
| Optionen | ImageOptionsBase | Die Optionen. |

## Beispiele

Der folgende Code demonstriert die Unterstützung des Exports der Timeline in ein Gif‑Bild.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Siehe auch

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


