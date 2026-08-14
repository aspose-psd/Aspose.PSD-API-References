---
title: "Classe VstkResource"
type: docs
weight: 40
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Inizializza una nuova istanza della classe VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| fill_enabled | bool | r/w | Ottiene o imposta un valore che indica se il riempimento Stroke è abilitato. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Ottiene o imposta le impostazioni di riempimento del tratto. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| stroke_enabled | bool | r/w | Ottiene o imposta un valore che indica se l'effetto stroke è abilitato. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Ottiene o imposta la modalità Blend di Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Ottiene o imposta l'entità Stroke. La proprietà determina le impostazioni di riempimento del tratto. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Ottiene o imposta l'allineamento della linea dello stile del tratto. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Ottiene o imposta il tipo di estremità di linea dello stile stroke. |
| stroke_style_line_cap_width | double | r/w | Ottiene o imposta la larghezza dell'estremità di linea Stroke. |
| stroke_style_line_dash_offset | int | r/w | Ottiene o imposta l'offset del dash della linea dello stile stroke. |
| stroke_style_line_dash_set | double | r/w | Ottiene o imposta l'array di tratti tratteggiati. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Ottiene o imposta il tipo di unione di linea dello stile Stroke. |
| stroke_style_line_width | double | r/w | Ottiene o imposta la larghezza della linea Stroke. |
| stroke_style_miter_limit | double | r/w | Ottiene o imposta il limite di spigolo dello stile stroke. |
| stroke_style_opacity | int | r/w | Ottiene o imposta l'opacità dello stile Stroke (0-100%). |
| stroke_style_resolution | double | r/w | Ottiene o imposta la risoluzione dello stile Stroke. |
| stroke_style_scale_lock | bool | r/w | Ottiene o imposta Stroke style scale lock. |
| stroke_style_stroke_adjust | bool | r/w | Ottiene o imposta Stroke adjust. |
| stroke_style_version | int | r/w | Ottiene o imposta la stroke style version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Inizializza una nuova istanza della classe VstkResource

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

