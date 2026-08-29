---
title: "LrXxResource klass"
type: docs
weight: 630
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/
---

**Summary:** The lrXX resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LrXxResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | r/w | Hämtar eller anger lagren. |
| längd | int | r | Hämtar resurslängden för PSD-huvudversionen av bilden. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar lagerposten. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar lagerposten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| psd_version | int | Den psd-versionen. |

