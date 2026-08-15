---
title: "UnknownResource klasse"
type: docs
weight: 1050
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/
---

**Summary:** The unknown resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.UnknownResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [UnknownResource(signature, key)](#UnknownResource_signature_key_1) | Initialiseert een nieuw exemplaar van de [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| data | byte | r/w | Haalt de gegevens op of stelt ze in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de laagresourcehandtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: UnknownResource(signature, key) {#UnknownResource_signature_key_1}


```
 UnknownResource(signature, key) 
```

Initialiseert een nieuw exemplaar van de [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature | int | De handtekening. |
| key | int | De resource sleutel. |

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

