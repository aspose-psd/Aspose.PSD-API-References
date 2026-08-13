---
title: "Classe Txt2Resource"
type: docs
weight: 970
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Initialise une nouvelle instance de la classe Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| data | byte | r/w | Obtient ou définit les données. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Ajoute l'enregistrement texte à Resource et renvoie l'ID de l'enregistrement texte. |
| [get_text_data()](#get_text_data__2) | Récupère l'enregistrement texte à partir des données de la ressource. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Enregistre le conteneur de flux spécifié. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Initialise une nouvelle instance de la classe Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Ajoute l'enregistrement texte à Resource et renvoie l'ID de l'enregistrement texte.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text | chaîne | Le texte de l'enregistrement. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites. |

**Returns**

| Type | Description |
| :- | :- |
| int | Renvoie l'ID de l'enregistrement texte pour la ressource |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Récupère l'enregistrement texte à partir des données de la ressource.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Tableau d'enregistrements texte |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Enregistre le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| psd_version | int | La version PSD. |

