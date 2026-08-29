---
title: "AiImage.ActivePageIndex"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà AiImage. Ottiene o imposta l'indice della pagina attiva"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Ottiene o imposta l'indice della pagina attiva.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Questa proprietà è valida solo per le immagini AI in formato PDF. Se l'immagine non è in formato PDF o non ci sono pagine, la proprietà sarà -1. Questa proprietà indica quale pagina dell'immagine AI sarà la base per il rendering.

## Esempi

Il codice seguente dimostra il supporto della possibilità di cambiare la pagina attiva nelle immagini Ai.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Carica l'immagine AI.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Per impostazione predefinita, ActivePageIndex è 0.
    // Quindi, se salvi l'immagine AI senza modificare questa proprietà, verrà renderizzata e salvata la prima pagina.
    image.Save(firstPageOutputPng, new PngOptions());

    // Modifica l'indice della pagina attiva alla seconda pagina.
    image.ActivePageIndex = 1;

    // Salva la seconda pagina dell'immagine AI come immagine PNG.
    image.Save(secondPageOutputPng, new PngOptions());

    // Modifica l'indice della pagina attiva alla terza pagina.
    image.ActivePageIndex = 2;

    // Salva la terza pagina dell'immagine AI come immagine PNG.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Vedi anche

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


