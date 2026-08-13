---
title: "Classe VersionInfoResource"
type: docs
weight: 300
url: /fr/python-net/aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Summary:** Version Info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.VersionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VersionInfoResource()](#VersionInfoResource__1) | Initialise une nouvelle instance de la classe VersionInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La signature de ressource d'ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La signature de ressource Photoshop standard. |
| data_size | int | r | Obtient la taille des données de la ressource en octets. |
| file_version | uint | r/w | Obtient ou définit la version du fichier. |
| has_real_merged_data | bool | r/w | Obtient ou définit une valeur indiquant si cette instance possède des données fusionnées réelles. |
| id | short | r/w | Obtient ou définit l'identifiant unique de la ressource. |
| minimal_version | int | r | Obtient la version PSD minimale requise. |
| name | chaîne | r/w | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| reader_name | chaîne | r/w | Obtient ou définit le nom du lecteur. |
| signature | int | r | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| taille | int | r | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| version | uint | r/w | Obtient ou définit la version. |
| writer_name | chaîne | r/w | Obtient ou définit le nom de l'écrivain. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc de ressource dans le flux spécifié. |
| validate_values() | Valide les valeurs de la ressource. |


### Constructor: VersionInfoResource() {#VersionInfoResource__1}


```
 VersionInfoResource() 
```

Initialise une nouvelle instance de la classe VersionInfoResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc de ressource dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le flux dans lequel enregistrer le bloc de ressource. |

