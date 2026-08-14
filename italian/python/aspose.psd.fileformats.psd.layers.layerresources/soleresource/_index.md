---
title: "SoLeResource Classe"
type: docs
weight: 940
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/
---

**Summary:** Defines the SoLeResource class that contains information about a smart object layer in a PSD file.<br/>            Is is used to support smart object layers with external file links in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLeResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SoLeResource()](#SoLeResource__1) | Inizializza una nuova istanza della classe [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |
| [SoLeResource(unique_id, is_custom, has_comp_info)](#SoLeResource_unique_id_is_custom_has_comp_info_2) | Inizializza una nuova istanza della classe [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo: 'SoLE'. |
| anti_alias_policy | int | r/w | Ottiene o imposta la politica anti-alias dei dati del livello smart object nell'immagine PSD. |
| bottom | double | r/w | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| comp | int | r/w | Ottiene o imposta il valore comp dei dati del livello smart object nel file PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| comp_id | int | r/w | Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato.<br/>            I comp sono composizioni di un layout di pagina che i designer possono creare. Utilizzando i layer comp, è possibile creare, gestire e visualizzare più versioni<br/>            di un layout in un unico file Adobe® Photoshop® . Un layer comp è un'istantanea di uno stato del pannello Livelli. I layer comp salvano tre tipi di opzioni di livello ma<br/>            questa proprietà restituisce l'identificatore di selezione del Layer Comp per il livello smart object nel file PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| crop | int | r/w | Ottiene o imposta il ritaglio dei dati del livello smart object nell'immagine PSD. |
| duration_denominator | int | r/w | Ottiene o imposta il denominatore della durata. |
| duration_numerator | int | r/w | Ottiene o imposta il numeratore della durata. |
| frame_count | int | r/w | Ottiene o imposta il conteggio dei fotogrammi dei dati del livello oggetto intelligente nel file PSD. |
| frame_step_denominator | int | r/w | Ottiene o imposta il denominatore del passo del fotogramma. |
| frame_step_numerator | int | r/w | Ottiene o imposta il numeratore del passo del fotogramma. |
| altezza | double | r/w | Ottiene o imposta l'altezza. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Ottiene o imposta l'unità di misura dei punti della maglia orizzontale. |
| horizontal_mesh_points | double | r/w | Ottiene o imposta i punti della maglia orizzontale del livello inserito nel file PSD. |
| is_custom | bool | r/w | Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato.<br/>            Se vero contiene punti della maglia. Se impostato a false elimina i punti della maglia. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Ottiene o imposta gli elementi descrittori dei dati del livello oggetto intelligente nel file PSD. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| sinistra | double | r/w | Ottiene o imposta la posizione sinistra del livello inserito nel file PSD. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa dell'oggetto intelligente in byte. |
| non_affine_transform_matrix | double | r/w | Ottiene o imposta la matrice di trasformazione non affine dei dati del livello oggetto intelligente nel file PSD. |
| original_comp_id | int | r | Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato.<br/>            Questa proprietà ottiene l'identificatore di selezione del Comp di livello originale per il livello oggetto intelligente nel file PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| page_number | int | r/w | Ottiene o imposta il numero di pagina dei dati del livello oggetto intelligente nel file PSD. |
| perspective | double | r/w | Ottiene o imposta il valore di prospettiva del livello inserito nel file PSD. |
| perspective_other | double | r/w | Ottiene o imposta l'altro valore di prospettiva del livello inserito nel file PSD. |
| placed_id | Guid | r/w | Ottiene o imposta l'identificatore univoco di questi dati del livello oggetto intelligente nell'immagine PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Ottiene o imposta il tipo dei dati del livello oggetto intelligente nel file PSD. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| resolution | double | r/w | Ottiene o imposta la risoluzione dei dati del livello oggetto intelligente nel file PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Ottiene o imposta l'unità di misura della risoluzione dei dati del livello oggetto intelligente nel file PSD. |
| destra | double | r/w | Ottiene o imposta la posizione destra del livello inserito nel file PSD. |
| signature | int | r | Ottiene la firma. |
| superiore | double | r/w | Ottiene o imposta la posizione superiore del livello inserito nell'immagine PSD. |
| total_pages | int | r/w | Ottiene o imposta il numero totale di pagine dei dati del livello oggetto intelligente nel file PSD. |
| transform_matrix | double | r/w | Ottiene o imposta la matrice di trasformazione dei dati del livello oggetto intelligente nel file PSD. |
| u_order | int | r/w | Ottiene o imposta il valore dell'ordine U del livello inserito nel file PSD. |
| unique_id | Guid | r/w | Ottiene o imposta l'identificatore univoco globale dei dati del livello oggetto intelligente [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) nell'immagine PSD. |
| v_order | int | r/w | Ottiene o imposta il valore dell'ordine V del livello inserito nel file PSD. |
| value | double | r/w | Ottiene o imposta il valore di deformazione del livello inserito nell'immagine PSD. |
| version | int | r | Restituisce la versione del livello posizionato nel file PSD, solitamente 3-5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Ottiene o imposta l'unità di misura dei punti della maglia verticale. |
| vertical_mesh_points | double | r/w | Ottiene o imposta i punti della maglia orizzontale del livello inserito nel file PSD. |
| width | double | r/w | Ottiene o imposta la larghezza. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa dell'oggetto intelligente nel contenitore di stream specificato. |


### Constructor: SoLeResource() {#SoLeResource__1}


```
 SoLeResource() 
```

Inizializza una nuova istanza della classe [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/).

### Constructor: SoLeResource(unique_id, is_custom, has_comp_info) {#SoLeResource_unique_id_is_custom_has_comp_info_2}


```
 SoLeResource(unique_id, is_custom, has_comp_info) 
```

Inizializza una nuova istanza della classe [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| unique_id | Guid | L'identificatore univoco dei dati del livello posizionato [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |
| is_custom | bool | se impostato su <c>true</c> [is custom]. |
| has_comp_info | bool | se impostato su <c>true</c> [has comp information]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva la risorsa dell'oggetto intelligente nel contenitore di stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psd_version | int | La versione PSD. |

