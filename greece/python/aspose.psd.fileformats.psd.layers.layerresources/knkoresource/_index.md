---
title: "Κλάση KnkoResource"
type: docs
weight: 450
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/
---

**Summary:** Class KnkoResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.KnkoResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [KnkoResource()](#KnkoResource__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
| [KnkoResource(data)](#KnkoResource_data_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) .<br/>            Με προσαρμοσμένη ή άγνωστη τιμή |
| [KnkoResource(knockout)](#KnkoResource_knockout_3) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| απομάκρυνση | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [blend interior elements]. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει το καθορισμένο κοντέινερ ροής. |


### Constructor: KnkoResource() {#KnkoResource__1}


```
 KnkoResource() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

### Constructor: KnkoResource(data) {#KnkoResource_data_2}


```
 KnkoResource(data) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) .<br/>            Με προσαρμοσμένη ή άγνωστη τιμή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Constructor: KnkoResource(knockout) {#KnkoResource_knockout_3}


```
 KnkoResource(knockout) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| απομάκρυνση | bool | εάν οριστεί σε <c>true</c> [blend interior elements]. |

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

