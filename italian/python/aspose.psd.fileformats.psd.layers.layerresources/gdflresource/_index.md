---
title: "Classe GdFlResource"
type: docs
weight: 330
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Inizializza una nuova istanza della classe GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| align_with_layer | bool | r/w | Ottiene o imposta un valore che indica se [align with layer]. |
| angolo | double | r/w | Ottiene o imposta l'angolo. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene il colore dell'RGB. |
| color_model | string | r/w | Modello di colore - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Ottiene i punti colore. |
| dither | bool | r/w | Ottiene o imposta un valore che indica se questo [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) è dither. |
| gradient_interval | double | r/w | Ottiene o imposta l'intervallo del gradiente. |
| gradient_mode | string | r/w | Modalità per questo gradiente.<br/>            Determina 'Tipo di gradiente' = 'Solido/Rumore' = \"CstS\"/\"ClNs\". |
| gradient_name | string | r/w | Ottiene o imposta il nome del gradiente. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Ottiene o imposta il tipo del gradiente. |
| horizontal_offset | double | r/w | Ottiene o imposta lo spostamento orizzontale. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Colore massimo di PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Colore minimo di PixelDataFormat. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| reverse | bool | r/w | Ottiene o imposta un valore che indica se questo [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) è invertito. |
| rnd_number_seed | int | r/w | Il seme del numero casuale usato per generare i colori per il gradiente Rumore. |
| roughness | int | r/w | Fattore di rugosità. |
| scale | int | r/w | Ottiene o imposta la scala. |
| show_transparency | bool | r/w | Flag per mostrare la trasparenza. |
| signature | int | r | Ottiene la firma. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Ottiene i punti di trasparenza. |
| use_vector_color | bool | r/w | Flag per usare il colore vettoriale. |
| vertical_offset | double | r/w | Ottiene o imposta lo spostamento verticale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Inizializza una nuova istanza della classe GdFlResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva la risorsa nel contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psd_version | int | La versione PSD. |

