---
title: "VsmsResource Klasse"
type: docs
weight: 1130
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---

**Summary:** Class VsmsResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VsmsResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [VsmsResource()](#VsmsResource__1) | Initialiseert een nieuw exemplaar van de [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) klasse. |
| [VsmsResource(data)](#VsmsResource_data_2) | Initialiseert een nieuw exemplaar van de [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| is_disabled | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze instantie is uitgeschakeld. |
| is_inverted | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze instantie is omgekeerd. |
| is_not_linked | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze instantie niet is gekoppeld. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Haalt of stelt de padrecords in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| version | int | r/w | Haalt de versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: VsmsResource() {#VsmsResource__1}


```
 VsmsResource() 
```

Initialiseert een nieuw exemplaar van de [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) klasse.

### Constructor: VsmsResource(data) {#VsmsResource_data_2}


```
 VsmsResource(data) 
```

Initialiseert een nieuw exemplaar van de [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De resourcegegevens. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

