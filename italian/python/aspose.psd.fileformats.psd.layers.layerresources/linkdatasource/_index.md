---
title: "Classe LinkDataSource"
type: docs
weight: 530
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---

**Summary:** Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Ottiene o imposta un valore che indica se l'asset PSD è bloccato.<br/>            Lo stato di blocco dell'asset, per gli asset delle librerie Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Ottiene o imposta la data di modifica dell'asset, per gli asset delle librerie Adobe® Photoshop® СС. |
| child_doc_id | string | r/w | Ottiene o imposta l'identificatore del documento figlio nella fonte dati liFE o liFD della risorsa Lnk2 / LnkE di Adobe® Photoshop®. |
| comp_id | int | r/w | Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato.<br/>            I comp sono composizioni di un layout di pagina che i designer possono creare. Utilizzando i layer comp, è possibile creare, gestire e visualizzare più versioni<br/>            di un layout in un unico file Adobe® Photoshop®. Un layer comp è un'istantanea di uno stato del pannello Livelli. I layer comp salvano tre tipi di opzioni di livello ma<br/>            questa proprietà restituisce l'identificatore di selezione del Layer Comp per gli Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| file_creator | string | r/w | Ottiene o imposta il creatore del file nella risorsa PSD formato LnkE / Lnk2. |
| file_type | string | r/w | Ottiene o imposta il tipo del file incorporato o esterno che la risorsa Adobe® Photoshop® Lnk2 / LnkE contiene o collega. |
| has_file_open_descriptor | bool | r/w | Ottiene o imposta un valore che indica se questa fonte dati di collegamento ha il descrittore di file aperto: CompId e OriginalCompId. |
| is_library_link | bool | r | Restituisce un valore che indica se questa fonte dati di collegamento PSD è collegata all'elemento della libreria Adobe® Photoshop® СС. |
| lunghezza | long | r | Restituisce la lunghezza della sorgente dati del collegamento in byte. |
| original_comp_id | int | r | Restituisce l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato.<br/>            Questa proprietà restituisce l'identificatore di selezione del Comp di livello originale per gli Smart Object.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Restituisce il nome file originale della sorgente dati nella risorsa di collegamento globale di Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Restituisce il tipo di sorgente dati del collegamento globale di Adobe® Photoshop®, che può essere uno dei seguenti o nessuno:<br/>            Il file collegato incorporato liFD che corrisponde al PSD Lnk2Resource<br/>            Il file collegato esterno liFE che corrisponde al PSD LnkeResource<br/>            L'alias del file collegato liFA |
| unique_id | Guid | r | Restituisce l'identificatore unico globale della sorgente dati nella risorsa di collegamento PSD. |
| version | int | r | Restituisce la versione della sorgente dati nella risorsa PSD LnkE / Lnk2. |


