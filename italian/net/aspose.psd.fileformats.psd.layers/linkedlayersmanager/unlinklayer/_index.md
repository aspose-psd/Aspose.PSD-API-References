---
title: LinkedLayersManager.UnlinkLayer
second_title: Aspose.PSD per riferimento API .NET
description: LinkedLayersManager metodo. Scollega il layer..
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/
---
## LinkedLayersManager.UnlinkLayer method

Scollega il layer..

```csharp
public void UnlinkLayer(Layer layer)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layer | Layer | Lo strato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il livello è nullo. |
| ArgumentException | Il contenitore del livello dovrebbe essere lo stesso dell'attuale PsdImage. |

### Esempi

L'esempio seguente dimostra come è possibile manipolare i livelli collegati in Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // collega tutti i livelli in un gruppo collegato
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // ottiene l'id per un livello
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // ottiene tutti i livelli collegati in base all'ID del gruppo di collegamenti.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // scollega ogni livello dal gruppo
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // recupera NULL per un ID gruppo di collegamento che non ha layer nel gruppo.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Guarda anche

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* assemblea [Aspose.PSD](../../../)


