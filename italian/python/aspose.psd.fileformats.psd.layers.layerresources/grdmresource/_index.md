---
title: "Classe GrdmResource"
type: docs
weight: 340
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Inizializza una nuova istanza della classe [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| color_model | short | r/w | Modello di colore.<br/>            Quando 'Gradient type' = 'Noise', possiamo assegnare 'Color Model' a RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Ottiene o imposta i punti di colore. |
| dither | bool | r/w | Il gradiente è ditherato. |
| expansion_count | short | r/w | Conteggio di espansione ( = 2 per Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Modalità per questo gradiente<br/>            Determina 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Nome del gradiente: stringa Unicode, riempita. |
| interpolazione | short | r/w | Interpolazione. Determina la fluidità, quando 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Colore massimo del formato PixelDataFormat.Rgba64Bpp.<br/>            Il colore ha canali ARGB, ogni canale è a 16 bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Colore minimo del formato PixelDataFormat.Rgba64Bpp.<br/>            Il colore ha canali ARGB, ogni canale è a 16 bit. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| reverse | bool | r/w | Il gradiente è invertito. |
| rnd_number_seed | int | r/w | Il seme del numero casuale usato per generare i colori per il gradiente Rumore. |
| roughness | int | r/w | Fattore di rugosità<br/>            Quando 'Gradient type' = 'Noise', possiamo assegnare 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Flag per mostrare la trasparenza<br/>            Quando 'Gradient type' = 'Noise', possiamo impostare 'Add transparency' su true. |
| signature | int | r | Ottiene la firma. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Ottiene o imposta i punti di trasparenza. |
| use_vector_color | short | r/w | Flag per usare il colore vettoriale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva i dati della risorsa nel contenitore di stream specificato. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Inizializza una nuova istanza della classe [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| psd_version | int | La versione psd della risorsa. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva i dati della risorsa nel contenitore di stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |
| psd_version | int | La versione PSD. |

