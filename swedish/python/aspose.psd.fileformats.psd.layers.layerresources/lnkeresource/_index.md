---
title: "LnkeResource klass"
type: docs
weight: 590
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/
---

**Summary:** Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image.<br/>            The link resource may contain several [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instances which can be accessed by indexer.<br/>            This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnkeResource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LnkeResource()](#LnkeResource__1) | Initierar en ny instans av [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klass. |
| [LnkeResource(data_sources)](#LnkeResource_data_sources_2) | Initierar en ny instans av [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| data_source_count | int | r | Hämtar antalet länkdatakällor som kan nås via indexeraren. |
| is_empty | bool | r | Hämtar ett värde som indikerar om denna länkreursursinstans är tom. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar den globala länkreursurslängden i PSD i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursblockets data. |


### Constructor: LnkeResource() {#LnkeResource__1}


```
 LnkeResource() 
```

Initierar en ny instans av [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klass.

### Constructor: LnkeResource(data_sources) {#LnkeResource_data_sources_2}


```
 LnkeResource(data_sources) 
```

Initierar en ny instans av [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_sources | [LinkDataSource[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) | Datakällorna. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursblockets data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

