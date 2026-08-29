---
title: "Classe QuickMaskInformationResource"
type: docs
weight: 220
url: /fr/python-net/aspose.psd.fileformats.psd.resources/quickmaskinformationresource/
---

**Summary:** Quick mask information resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.QuickMaskInformationResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [QuickMaskInformationResource()](#QuickMaskInformationResource__1) | Initialise une nouvelle instance de la classe QuickMaskInformationResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La signature de ressource d'ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La signature de ressource Photoshop standard. |
| channel_id | short | r/w | Obtient ou définit l'identifiant du canal. |
| data_size | int | r | Obtient la taille des données de la ressource en octets. |
| id | short | r/w | Obtient ou définit l'identifiant unique de la ressource. |
| is_mask_empty | bool | r/w | Obtient ou définit une valeur indiquant si cette instance a un masque vide. |
| minimal_version | int | r | Obtient la version PSD minimale requise. |
| name | chaîne | r/w | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| signature | int | r | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| taille | int | r | Obtient la taille du bloc de ressource en octets, y compris ses données. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc de ressource dans le flux spécifié. |
| validate_values() | Valide les valeurs de la ressource. |


### Constructor: QuickMaskInformationResource() {#QuickMaskInformationResource__1}


```
 QuickMaskInformationResource() 
```

Initialise une nouvelle instance de la classe QuickMaskInformationResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc de ressource dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le flux dans lequel enregistrer le bloc de ressource. |

