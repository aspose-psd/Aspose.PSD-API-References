---
title: "FxrpResource Κλάση"
type: docs
weight: 320
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) |
| [FxrpResource(data)](#FxrpResource_data_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) κλάσης.<br/>            Με προσαρμοσμένη ή άγνωστη τιμή |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
| x | double | r/w | Λαμβάνει ή ορίζει το x του σημείου αναφοράς |
| y | double | r/w | Λαμβάνει ή ορίζει το y του σημείου αναφοράς |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει στο καθορισμένο δοχείο ροής. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/)

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) κλάσης.<br/>            Με προσαρμοσμένη ή άγνωστη τιμή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/)

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | double | Η συντεταγμένη x του σημείου αναφοράς |
| y | double | Η συντεταγμένη y του σημείου αναφοράς |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει στο καθορισμένο δοχείο ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| psd_version | int | Η έκδοση PSD. |

