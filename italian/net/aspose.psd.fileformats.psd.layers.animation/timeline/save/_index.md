---
title: "Timeline.Save"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo Timeline. Salva le PsdImages e i dati della Timeline nella posizione file specificata nel formato specificato secondo le opzioni di salvataggio"
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Salva le PsdImage e i dati della Timeline nella posizione file specificata nel formato specificato secondo le opzioni di salvataggio.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | Stringa | Il percorso del file. |
| options | ImageOptionsBase | Le opzioni. |

## Esempi

Il codice seguente dimostra il supporto per l'esportazione della Timeline in un'immagine Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Vedi anche

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Salva le PsdImage e i dati della Timeline nello stream specificato nel formato specificato secondo le opzioni di salvataggio.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Flusso | Lo stream di output. |
| options | ImageOptionsBase | Le opzioni. |

## Esempi

Il codice seguente dimostra il supporto per l'esportazione della Timeline in un'immagine Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Vedi anche

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


