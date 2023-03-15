---
title: Class MlstResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource classe. La risorsa mlst. Questa classe tra le altre cose contiene informazioni sulla posizione del livello sulla timeline.
type: docs
weight: 2830
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

La risorsa mlst. Questa classe, tra le altre cose, contiene informazioni sulla posizione del livello sulla timeline.

```csharp
public class MlstResource : LayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MlstResource](mlstresource/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Ottiene o imposta la versione del descrittore. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Ottiene o imposta le strutture. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Ottiene la versione psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Ottiene la firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Salva il contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | Il tasto informazioni dello strumento testo. |

### Esempi

Il codice seguente illustra il supporto della risorsa MlstResource che fornisce un meccanismo di basso livello per manipolare gli stati del livello.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Disabilita il livello 1 sul fotogramma 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Guarda anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


