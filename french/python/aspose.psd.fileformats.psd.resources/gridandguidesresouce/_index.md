---
title: "GridAndGuidesResouce Classe"
type: docs
weight: 110
url: /fr/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Initialise une nouvelle instance de la classe GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La signature de ressource d'ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La signature de ressource Photoshop standard. |
| data_size | int | r | Obtient la taille des données de la ressource en octets. |
| grid_cycle_x | int | r/w | Obtient ou définit le cycle de grille horizontal. La valeur par défaut est 576. |
| grid_cycle_y | int | r/w | Obtient ou définit le cycle de grille vertical. La valeur par défaut est 576. |
| guide_count | int | r | Obtient le nombre de blocs de ressources de guide. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Obtient ou définit les guides. |
| header_version | int | r/w | Obtient ou définit la version de l'en-tête. Cette valeur doit toujours être 1. |
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


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Initialise une nouvelle instance de la classe GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc de ressource dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le flux dans lequel enregistrer le bloc de ressource. |

