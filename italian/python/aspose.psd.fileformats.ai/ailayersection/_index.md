---
title: "Classe AiLayerSection"
type: docs
weight: 50
url: /it/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blu | int | r/w | Ottiene o imposta il componente colore blu. |
| color_index | int | r/w | Ottiene o imposta l'indice del colore.<br/>            Questo argomento può assumere valori compresi tra –1 e 26. Ogni intero<br/>            rappresenta un colore che può essere assegnato al livello per scopi di<br/>            identificazione dell'utente. |
| color_number | int | r/w | Ottiene o imposta il numero del colore. -1 è il valore colore personalizzato dalle proprietà Rosso, Verde, Blu.<br/>            Specifica l'impostazione del colore del livello. |
| dim_value | int | r/w | Ottiene o imposta il valore di attenuazione in percentuale.<br/>            Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello alla percentuale specificata. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| verde | int | r/w | Ottiene o imposta il componente di colore verde. |
| has_multi_layer_masks | bool | r/w | Ottiene o imposta un valore che indica se questa istanza ha maschere multistrato. |
| is_images_dimmed | bool | r/w | Ottiene o imposta un valore che indica se questo livello è attenuato.<br/>            Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello. |
| is_locked | bool | r/w | Ottiene o imposta un valore che indica se questo livello è bloccato.<br/>            Impedisce modifiche all'elemento. |
| is_preview | bool | r/w | Ottiene o imposta un valore che indica se questo livello è in anteprima.<br/>            Visualizza l'opera contenuta nel livello a colori invece che come contorni. |
| is_printed | bool | r/w | Ottiene o imposta un valore che indica se questo livello è stampato.<br/>            Rende l'opera contenuta nel livello stampabile se vero. |
| is_shown | bool | r/w | Ottiene o imposta un valore che indica se questo livello è mostrato.<br/>            Visualizza tutta l'opera contenuta nel livello sulla tavola se vero. |
| is_template | bool | r/w | Ottiene o imposta un valore che indica se questo livello è un livello modello. |
| name | string | r/w | Ottiene o imposta il nome del livello.<br/>            Specifica il nome dell'elemento come appare nel pannello Livelli. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Ottiene le immagini raster. |
| rosso | int | r/w | Ottiene o imposta il componente di colore rosso. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Aggiunge l'immagine raster. |
| [get_data()](#get_data__2) | Restituisce i dati stringa. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Aggiunge l'immagine raster.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | L'immagine raster. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Restituisce i dati stringa.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | I dati stringa della sezione |


