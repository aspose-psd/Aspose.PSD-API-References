---
title: "InfxResource Κλάση"
type: docs
weight: 420
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(data)](#InfxResource_data_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            Με προσαρμοσμένη ή άγνωστη τιμή |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| blend_interior_elements | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [blend interior elements]. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει το καθορισμένο κοντέινερ ροής. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| blend_interior_elements | bool | εάν οριστεί σε <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            Με προσαρμοσμένη ή άγνωστη τιμή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει το καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| psd_version | int | Η έκδοση PSD. |

