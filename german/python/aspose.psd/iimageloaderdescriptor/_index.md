---
title: "IImageLoaderDescriptor Klasse"
type: docs
weight: 1820
url: /de/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ermittelt das unterstützte Format. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann, optional unter Verwendung von <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Erstellt eine neue Loader-Instanz. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann, optional unter Verwendung von <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Dateiformatdetails, die durch <paramref name="loadOptions" /> angegeben werden. <paramref name="loadOptions" /> kann null sein. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn der durch diesen Deskriptor erstellte Bildlader das Bild aus dem Stream lesen kann; andernfalls <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Erstellt eine neue Loader-Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Eine neue Loader-Instanz. |


