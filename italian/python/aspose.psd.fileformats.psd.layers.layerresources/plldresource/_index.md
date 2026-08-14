---
title: "Classe PlLdResource"
type: docs
weight: 820
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| anti_alias_policy | int | r/w | Ottiene o imposta la politica di anti-alias del livello posizionato nell'immagine PSD. |
| bottom | double | r/w | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Ottiene o imposta l'unità di misura dei punti della maglia orizzontale. |
| horizontal_mesh_points | double | r/w | Ottiene o imposta i punti della maglia orizzontale del livello inserito nel file PSD. |
| is_custom | bool | r/w | Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato.<br/>            Se vero contiene punti della maglia. Se impostato a false elimina i punti della maglia. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Ottiene o imposta gli elementi di deformazione. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| sinistra | double | r/w | Ottiene o imposta la posizione sinistra del livello inserito nel file PSD. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa PlLd in byte. |
| page_number | int | r/w | Ottiene o imposta il numero di pagina del livello inserito nel file PSD. |
| perspective | double | r/w | Ottiene o imposta il valore di prospettiva del livello inserito nel file PSD. |
| perspective_other | double | r/w | Ottiene o imposta l'altro valore di prospettiva del livello inserito nel file PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Ottiene o imposta il tipo del livello inserito nel file PSD. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| destra | double | r/w | Ottiene o imposta la posizione destra del livello inserito nel file PSD. |
| signature | int | r | Ottiene la firma. |
| superiore | double | r/w | Ottiene o imposta la posizione superiore del livello inserito nell'immagine PSD. |
| total_pages | int | r/w | Ottiene o imposta il numero totale di pagine del livello inserito nel file PSD. |
| transform_matrix | double | r/w | Ottiene o imposta la matrice di trasformazione del livello inserito nel file PSD. |
| u_order | int | r/w | Ottiene o imposta il valore dell'ordine U del livello inserito nel file PSD. |
| unique_id | Guid | r/w | Ottiene o imposta l'identificatore unico globale del livello inserito nell'immagine PSD. |
| v_order | int | r/w | Ottiene o imposta il valore dell'ordine V del livello inserito nel file PSD. |
| value | double | r/w | Ottiene o imposta il valore di deformazione del livello inserito nell'immagine PSD. |
| version | int | r | Ottiene la versione del livello inserito nel file PSD, solitamente 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Ottiene o imposta l'unità di misura dei punti della maglia verticale. |
| vertical_mesh_points | double | r/w | Ottiene o imposta i punti della maglia orizzontale del livello inserito nel file PSD. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa PlLD nel contenitore di flusso specificato. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva la risorsa PlLD nel contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psd_version | int | La versione PSD. |

