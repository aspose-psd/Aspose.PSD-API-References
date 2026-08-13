---
title: "Classe UnknownResource"
type: docs
weight: 280
url: /fr/python-net/aspose.psd.fileformats.psd.resources/unknownresource/
---

**Summary:** The unknown resource. When a resource block is not recognized then this resource block is created.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.UnknownResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La signature de ressource d'ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La signature de ressource Photoshop standard. |
| data | byte | r | Obtient les données de la ressource. |
| data_size | int | r | Obtient la taille des données de la ressource en octets. |
| id | short | r/w | Obtient ou définit l'identifiant unique de la ressource. |
| minimal_version | int | r | Obtient la version PSD minimale requise. |
| name | chaîne | r/w | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| signature | int | r | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| taille | int | r | Obtient la taille du bloc de ressource en octets, y compris ses données. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc de ressource dans le flux spécifié. |
| validate_values() | Valide les valeurs de la ressource. |


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc de ressource dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le flux dans lequel enregistrer le bloc de ressource. |

