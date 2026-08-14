---
title: "Classe Timeline"
type: docs
weight: 40
url: /it/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Timeline()](#Timeline__1) | Inizializza una nuova istanza della classe Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Ottiene l'indice del fotogramma attivo. |
| af_st | int | r/w | Ottiene o imposta il valore AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Ottiene l'elenco dei fotogrammi. |
| fs_id | int | r/w | Ottiene o imposta il valore FsID. |
| loopes_count | ushort | r/w | Ottiene o imposta il conteggio dei cicli. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Salva i dati di PsdImage e Timeline nella posizione file specificata nel formato specificato secondo le opzioni di salvataggio. |
| [save(output_stream, options)](#save_output_stream_options_2) | Salva i dati di PsdImage e Timeline nello stream specificato nel formato specificato secondo le opzioni di salvataggio. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Passa il fotogramma attivo a quello mirato. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Inizializza una nuova istanza della classe Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Salva i dati di PsdImage e Timeline nella posizione file specificata nel formato specificato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Le opzioni. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Salva i dati di PsdImage e Timeline nello stream specificato nel formato specificato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Il flusso di output. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Le opzioni. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Passa il fotogramma attivo a quello mirato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_active_frame_index | int | L'indice del frame di destinazione. |

