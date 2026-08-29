---
title: "Timeline.Save"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Timeline. Enregistre les PsdImages et les données Timeline à l'emplacement de fichier spécifié dans le format indiqué selon les options d'enregistrement"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Enregistre les données du PsdImage et de la Timeline à l'emplacement de fichier spécifié au format spécifié selon les options d'enregistrement.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |

## Exemples

Le code suivant montre la prise en charge de l'exportation du Timeline vers une image Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Voir aussi

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Enregistre les données du PsdImage et de la Timeline dans le flux spécifié au format spécifié selon les options d'enregistrement.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux de sortie. |
| options | ImageOptionsBase | Les options. |

## Exemples

Le code suivant montre la prise en charge de l'exportation du Timeline vers une image Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Voir aussi

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


