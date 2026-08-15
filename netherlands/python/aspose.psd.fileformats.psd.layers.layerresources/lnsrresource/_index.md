---
title: "LnsrResource Klasse"
type: docs
weight: 600
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/
---

**Summary:** Class lnsrResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnsrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LnsrResource(bytes)](#LnsrResource_bytes_1) | Initialiseert een nieuw exemplaar van de [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) klasse.<br/>            Met aangepaste of onbekende waarde |
| [LnsrResource(lnsr_resource_type)](#LnsrResource_lnsr_resource_type_2) | Initialiseert een nieuw exemplaar van de [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| data | byte | r | Haalt de ruwe gegevens op. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| value | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | r | Haalt de waarde op als LnsrResourceType als de overeenkomstige enum is beschreven.<br/>            Retourneert anders Unknown |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: LnsrResource(bytes) {#LnsrResource_bytes_1}


```
 LnsrResource(bytes) 
```

Initialiseert een nieuw exemplaar van de [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) klasse.<br/>            Met aangepaste of onbekende waarde

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De bytes. |

### Constructor: LnsrResource(lnsr_resource_type) {#LnsrResource_lnsr_resource_type_2}


```
 LnsrResource(lnsr_resource_type) 
```

Initialiseert een nieuw exemplaar van de [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| lnsr_resource_type | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | Type van de LNSR. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de opgegeven streamcontainer op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| psd_version | int | De PSD‑versie. |

