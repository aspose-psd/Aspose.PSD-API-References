---
title: Class LinkResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource classe. Definisce la classe LinkResource che contiene informazioni sui file collegati o incorporati nellimmagine in formato PSD. La risorsa collegamento può contenere diversiLinkDataSource istanze a cui possono accedere gli indicizzatori in qualsiasi classe derivata.
type: docs
weight: 2710
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Definisce la classe LinkResource che contiene informazioni sui file collegati o incorporati nell'immagine in formato PSD. La risorsa collegamento può contenere diversi[`LinkDataSource`](../linkdatasource/) istanze a cui possono accedere gli indicizzatori in qualsiasi classe derivata.

```csharp
public abstract class LinkResource : LayerResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Ottiene il numero di origini dati di collegamento a cui può accedere l'indicizzatore. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Ottiene un valore che indica se questa istanza della risorsa di collegamento è vuota. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Ottiene il[`LinkDataSource`](../linkdatasource/) all'indice specificato che è l'identificatore univoco dell'origine dati del collegamento.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Ottiene la lunghezza della risorsa di collegamento globale PSD in byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Ottiene la versione del formato PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Ottiene la firma della risorsa di collegamento globale PSD. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Salva i dati del blocco delle risorse. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

### Guarda anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


