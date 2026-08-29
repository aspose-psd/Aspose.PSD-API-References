---
title: "Classe BaseFxResource"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource. Risorsa di effetti di base"
type: docs
weight: 2550
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

Risorsa di effetti di base

```csharp
public abstract class BaseFxResource : LayerResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Ottiene la versione del descrittore. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Ottiene la versione minima di psd richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Ottiene la firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore di stream specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce una stringa che rappresenta questa istanza. |

## Esempi

Il codice seguente dimostra il supporto della risorsa multi-effetti.

```csharp
[C#]

// L'immagine PSD contiene 2 effetti Drop Shadow 
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // Renderizza l'immagine PSD con 2 effetti Drop Shadow.
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Aggiunge un terzo effetto Drop Shadow.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // Renderizza l'immagine PSD con 3 effetti Drop Shadow.
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // La risorsa imfx è usata se il livello contiene più effetti dello stesso tipo.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Cancella tutti gli effetti.
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // Renderizza l'immagine PSD con 1 effetto Drop Shadow (gli altri sono stati eliminati).
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // La risorsa lfx2 è usata se il livello non contiene più effetti dello stesso tipo.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Vedi anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


