---
title: "Classe TypeToolInfoResource"
type: docs
weight: 1000
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Inizializza una nuova istanza della classe TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| a_component | short | r/w | Ottiene o imposta un componente. |
| b_component | short | r/w | Ottiene o imposta il componente b. |
| character_count | int | r/w | Ottiene o imposta il conteggio dei caratteri. |
| color_space_value | short | r/w | Ottiene o imposta il valore dello spazio colore. |
| font_version | short | r/w | Ottiene o imposta la versione del carattere. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Ottiene o imposta i font. |
| fonts_count | short | r | Restituisce il conteggio dei font. |
| g_component | short | r/w | Ottiene o imposta il componente g. |
| horizontal_placement | int | r/w | Ottiene o imposta il posizionamento orizzontale. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| line_count | short | r | Ottiene il conteggio delle righe. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Ottiene o imposta le righe. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| r_component | short | r/w | Ottiene o imposta il componente r. |
| scale_factor | int | r/w | Ottiene o imposta il fattore di scala. |
| selection_end | int | r/w | Ottiene o imposta la fine della selezione. |
| selection_start | int | r/w | Ottiene o imposta l'inizio della selezione. |
| signature | int | r | Ottiene la firma. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Ottiene o imposta gli stili del carattere. |
| styles_count | short | r | Ottiene il conteggio degli stili. |
| transform_matrix | double | r/w | Ottiene o imposta la matrice di trasformazione. |
| type_value | short | r/w | Ottiene o imposta il valore del tipo. |
| version | short | r/w | Ottiene o imposta la versione. |
| vertical_placement | int | r/w | Ottiene o imposta il posizionamento verticale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva il contenitore di flusso specificato. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Inizializza una nuova istanza della classe TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva il contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |
| psd_version | int | La versione PSD. |

