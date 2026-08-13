---
title: "Classe WorkingPathResource"
type: docs
weight: 320
url: /fr/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Initialise une nouvelle instance de la classe [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La signature de ressource d'ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La signature de ressource Photoshop standard. |
| data_size | int | r | Obtient la taille des données de la ressource en octets. |
| id | short | r/w | Obtient ou définit l'identifiant unique de la ressource. |
| is_disabled | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| is_inverted | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| is_not_linked | bool | r/w | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| minimal_version | int | r | Obtient la version PSD minimale requise. |
| name | chaîne | r/w | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Obtient ou définit les enregistrements de chemin. |
| signature | int | r | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| taille | int | r | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| version | int | r/w | Obtient ou définit la version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc de ressource dans le flux spécifié. |
| validate_values() | Valide les valeurs de la ressource. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Initialise une nouvelle instance de la classe [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_bytes | byte | Les données du chemin vectoriel. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc de ressource dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le flux dans lequel enregistrer le bloc de ressource. |

