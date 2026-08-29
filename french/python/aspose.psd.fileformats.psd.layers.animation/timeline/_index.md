---
title: "Classe Timeline"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Timeline()](#Timeline__1) | Initialise une nouvelle instance de la classe Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Obtient l'index de la trame active. |
| af_st | int | r/w | Obtient ou définit la valeur AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Obtient la liste des trames. |
| fs_id | int | r/w | Obtient ou définit la valeur FsID. |
| loopes_count | ushort | r/w | Obtient ou définit le nombre de boucles. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Enregistre les données du PsdImage et du Timeline à l'emplacement de fichier spécifié dans le format spécifié selon les options d'enregistrement. |
| [save(output_stream, options)](#save_output_stream_options_2) | Enregistre les données du PsdImage et du Timeline dans le flux spécifié dans le format spécifié selon les options d'enregistrement. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Bascule la trame active vers la cible. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Initialise une nouvelle instance de la classe Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Enregistre les données du PsdImage et du Timeline à l'emplacement de fichier spécifié dans le format spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Enregistre les données du PsdImage et du Timeline dans le flux spécifié dans le format spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Le flux de sortie. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Bascule la trame active vers la cible.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| target_active_frame_index | int | L'index de la trame cible. |

