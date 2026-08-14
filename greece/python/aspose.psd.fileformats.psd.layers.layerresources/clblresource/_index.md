---
title: "ClblResource Κλάση"
type: docs
weight: 160
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) . |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) . |
| [ClblResource(data)](#ClblResource_data_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .<br/>            Με προσαρμοσμένη ή άγνωστη τιμή |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| blend_clipped_elements | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [blend clipped elements]. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει το καθορισμένο κοντέινερ ροής. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| blend_clipped_elements | bool | αν οριστεί σε <c>true</c> [blend clipped elements]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .<br/>            Με προσαρμοσμένη ή άγνωστη τιμή

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

