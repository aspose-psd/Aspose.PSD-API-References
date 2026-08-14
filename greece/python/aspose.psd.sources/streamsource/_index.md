---
title: "StreamSource Κλάση"
type: docs
weight: 40
url: /el/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή πρέπει να διαγραφεί κάθε φορά που το δοχείο διαγράφεται. |
| ροή | _io.BufferedRandom | r | Λαμβάνει τη ροή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Λαμβάνει το δοχείο ροής. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για άνοιγμα. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για άνοιγμα. |
| dispose_stream | bool | εάν οριστεί σε <c>true</c> η ροή θα διαγραφεί. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Λαμβάνει το δοχείο ροής.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | το δοχείο ροής. |


