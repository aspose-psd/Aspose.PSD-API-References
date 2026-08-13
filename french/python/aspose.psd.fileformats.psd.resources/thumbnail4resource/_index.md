---
title: "Classe Thumbnail4Resource"
type: docs
weight: 240
url: /fr/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | Initialise une nouvelle instance de la classe Thumbnail4Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La signature de ressource d'ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La signature de ressource Photoshop standard. |
| bits_pixel | short | r/w | Obtient ou définit les bits par pixel. |
| data_size | int | r | Obtient la taille des données de la ressource en octets. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Obtient ou définit le format des données de la vignette. |
| hauteur | int | r/w | Obtient ou définit la hauteur de la vignette en pixels. |
| id | short | r/w | Obtient ou définit l'identifiant unique de la ressource. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Obtient ou définit les options JPEG. Convient lorsque la ressource de vignette est enregistrée uniquement au format de fichier JPEG. Cette option n'a aucun effet lorsque le format RAW est défini. |
| minimal_version | int | r | Obtient la version PSD minimale requise. |
| name | chaîne | r/w | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| planes_count | short | r/w | Obtient ou définit le nombre de plans. |
| signature | int | r | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| taille | int | r | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| size_after_compression | int | r | Obtient ou définit la taille après compression. Utilisé pour la vérification de cohérence. |
| thumbnail_argb_32_data | int | r/w | Obtient ou définit les données de la miniature ARGB 32 bits. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit les données de la miniature. |
| total_size | int | r | Obtient la taille totale des données. |
| width | int | r/w | Obtient ou définit la largeur de la miniature en pixels. |
| width_bytes | int | r | Obtient la largeur de la ligne en octets. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre les données du bloc de ressources. |
| validate_values() | Valide les valeurs de la ressource. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

Initialise une nouvelle instance de la classe Thumbnail4Resource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre les données du bloc de ressources.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

