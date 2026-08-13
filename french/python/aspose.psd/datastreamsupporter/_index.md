---
title: "Classe DataStreamSupporter"
type: docs
weight: 1030
url: /fr/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Obtient le flux de données de l'objet. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| est_en_cache | bool | r | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et qu'aucune lecture de données n'est requise. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) sous-jacent. |
| save() | Enregistre les données de l'objet dans le [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) actuel. |
| [save(file_path)](#save_file_path_1) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_3) | Enregistre les données de l'objet dans le flux spécifié. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données de l'objet. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

