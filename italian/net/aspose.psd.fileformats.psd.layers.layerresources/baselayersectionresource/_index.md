---
title: "Classe BaseLayerSectionResource"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseLayerSectionResource class. Classe base per le risorse di sezione di livello"
type: docs
weight: 2560
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/
---
{{< psd/tize >}}
## BaseLayerSectionResource class

Classe base per le risorse di sezione di livello

```csharp
public abstract class BaseLayerSectionResource : LayerResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlendModeKey](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/) { get; set; } | Ottiene o imposta la chiave della modalità di fusione. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Ottiene la versione minima di psd richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| [SectionType](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/sectiontype/) { get; set; } | Ottiene o imposta il tipo di sezione. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Ottiene la firma. |
| [Subtype](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/subtype/) { get; set; } | Ottiene o imposta il sottotipo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore di stream specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce una stringa che rappresenta questa istanza. |

## Esempi

Il codice seguente dimostra la gerarchia delle classi delle risorse di sezione di livello.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string srcFile = "123 1.psd";
string outFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[3].Resources[3] as LayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[3].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Length, 4);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).BlendModeKey, BlendMode.Absent);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Subtype, LayerSectionSubtype.NotUsed);

    psdImage.Save(outFile);
}

// controlla dopo il salvataggio
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[3].Resources[3] as LayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[3].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Length, 4);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).BlendModeKey, BlendMode.Absent);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Subtype, LayerSectionSubtype.NotUsed);
}

File.Delete(outFile);
```

### Vedi anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


