---
title: "XmpDynamicMediaPackage Κλάση"
type: docs
weight: 70
url: /el/python-net/aspose.psd.xmp.schemas.xmpdm/xmpdynamicmediapackage/
---

**Summary:** Represents XMP Dynamic Media namespace.

**Module:** [aspose.psd.xmp.schemas.xmpdm](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/)

**Full Name:** aspose.psd.xmp.schemas.xmpdm.XmpDynamicMediaPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [XmpDynamicMediaPackage()](#XmpDynamicMediaPackage__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης XmpDynamicMediaPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Λαμβάνει το URI του ονόματος χώρου. |
| πρόθεμα | string | r | Λαμβάνει το πρόθεμα. |
| xml_namespace | string | r | Λαμβάνει το χώρο ονομάτων XML. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Προσθέτει ιδιότητα συμβολοσειράς. |
| clear() | Καθαρίζει αυτήν την παρουσία. |
| [contains_key(key)](#contains_key_key_2) | Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί. |
| [get_xml_value()](#get_xml_value__3) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [remove(key)](#remove_key_4) | Αφαιρεί την τιμή με το καθορισμένο κλειδί. |
| [set_abs_peak_audio_file_path(uri)](#set_abs_peak_audio_file_path_uri_5) | Ορίζει τη διαδρομή του απόλυτου κορυφαίου αρχείου ήχου. |
| [set_alblum(album)](#set_alblum_album_6) | Ορίζει το άλμπουμ. |
| [set_alt_tape_name(alt_tape_name)](#set_alt_tape_name_alt_tape_name_7) | Ορίζει το εναλλακτικό όνομα ταινίας. |
| [set_alt_time_code(timecode)](#set_alt_time_code_timecode_8) | Ορίζει τον εναλλακτικό κώδικα χρόνου. |
| [set_artist(artist)](#set_artist_artist_9) | Ορίζει τον καλλιτέχνη. |
| [set_audio_channel_type(audio_channel_type)](#set_audio_channel_type_audio_channel_type_10) | Ορίζει τον τύπο καναλιού ήχου. |
| [set_audio_sample_rate(rate)](#set_audio_sample_rate_rate_11) | Ορίζει το ρυθμό δειγματοληψίας ήχου. |
| [set_audio_sample_type(audio_sample_type)](#set_audio_sample_type_audio_sample_type_12) | Ορίζει τον τύπο δείγματος ήχου. |
| [set_camera_angle(camera_angle)](#set_camera_angle_camera_angle_13) | Ορίζει τη γωνία της κάμερας. |
| [set_camera_label(camera_label)](#set_camera_label_camera_label_14) | Ορίζει την ετικέτα της κάμερας. |
| [set_camera_move(camera_move)](#set_camera_move_camera_move_15) | Ορίζει την κίνηση της κάμερας. |
| [set_client(client)](#set_client_client_16) | Ορίζει τον πελάτη. |
| [set_comment(comment)](#set_comment_comment_17) | Ορίζει το σχόλιο. |
| [set_composer(composer)](#set_composer_composer_18) | Ορίζει τον συνθέτη. |
| [set_director(director)](#set_director_director_19) | Ορίζει τον σκηνοθέτη. |
| [set_director_photography(director_photography)](#set_director_photography_director_photography_20) | Ορίζει τον διευθυντή φωτογραφίας. |
| [set_duration(duration)](#set_duration_duration_21) | Ορίζει τη διάρκεια. |
| [set_engineer(engineer)](#set_engineer_engineer_22) | Ορίζει τον μηχανικό. |
| [set_file_data_rate(rate)](#set_file_data_rate_rate_23) | Ορίζει το ρυθμό δεδομένων του αρχείου. |
| [set_genre(genre)](#set_genre_genre_24) | Ορίζει το είδος. |
| [set_good(good)](#set_good_good_25) | Ορίζει το καλό. |
| [set_instrument(instrument)](#set_instrument_instrument_26) | Ορίζει το όργανο. |
| [set_intro_time(intro_time)](#set_intro_time_intro_time_27) | Ορίζει το χρόνο εισαγωγής. |
| [set_key(key)](#set_key_key_28) | Ορίζει το μουσικό κλειδί του ήχου. |
| [set_log_comment(comment)](#set_log_comment_comment_29) | Ορίζει το σχόλιο καταγραφής του χρήστη. |
| [set_value(key, value)](#set_value_key_value_30) | Ορίζει την τιμή. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_31) | Ορίζει την τιμή τύπου XMP. |


### Constructor: XmpDynamicMediaPackage() {#XmpDynamicMediaPackage__1}


```
 XmpDynamicMediaPackage() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης XmpDynamicMediaPackage

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Προσθέτει ιδιότητα συμβολοσειράς.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | string | Η τιμή συμβολοσειράς. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Το κλειδί που θα ελεγχθεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Επιστρέφει true εάν το καθορισμένο κλειδί περιέχει το κλειδί. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Μετατρέπει την τιμή XMP στην αναπαράσταση XML.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει την τιμή XMP μετατρεπόμενη στην αναπαράσταση XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Αφαιρεί την τιμή με το καθορισμένο κλειδί.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την αφαιρεθείσα τιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Επιστρέφει true εάν η τιμή με το καθορισμένο κλειδί αφαιρέθηκε. |


### Method: set_abs_peak_audio_file_path(uri) {#set_abs_peak_audio_file_path_uri_5}


```
 set_abs_peak_audio_file_path(uri) 
```

Ορίζει τη διαδρομή του απόλυτου κορυφαίου αρχείου ήχου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| uri | string | Η απόλυτη διαδρομή προς το αρχείο κορυφαίου ήχου του αρχείου. |

### Method: set_alblum(album) {#set_alblum_album_6}


```
 set_alblum(album) 
```

Ορίζει το άλμπουμ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| album | string | Το άλμπουμ. |

### Method: set_alt_tape_name(alt_tape_name) {#set_alt_tape_name_alt_tape_name_7}


```
 set_alt_tape_name(alt_tape_name) 
```

Ορίζει το εναλλακτικό όνομα ταινίας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| alt_tape_name | string | Εναλλακτικό όνομα ταινίας. |

### Method: set_alt_time_code(timecode) {#set_alt_time_code_timecode_8}


```
 set_alt_time_code(timecode) 
```

Ορίζει τον εναλλακτικό κώδικα χρόνου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| timecode | [Timecode](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/timecode) | Κώδικας χρόνου. |

### Method: set_artist(artist) {#set_artist_artist_9}


```
 set_artist(artist) 
```

Ορίζει τον καλλιτέχνη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| καλλιτέχνης | string | Ο καλλιτέχνης. |

### Method: set_audio_channel_type(audio_channel_type) {#set_audio_channel_type_audio_channel_type_10}


```
 set_audio_channel_type(audio_channel_type) 
```

Ορίζει τον τύπο καναλιού ήχου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| audio_channel_type | [AudioChannelType](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/audiochanneltype) | Τύπος καναλιού ήχου. |

### Method: set_audio_sample_rate(rate) {#set_audio_sample_rate_rate_11}


```
 set_audio_sample_rate(rate) 
```

Ορίζει το ρυθμό δειγματοληψίας ήχου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rate | int | Ο ρυθμός δειγματοληψίας ήχου. |

### Method: set_audio_sample_type(audio_sample_type) {#set_audio_sample_type_audio_sample_type_12}


```
 set_audio_sample_type(audio_sample_type) 
```

Ορίζει τον τύπο δείγματος ήχου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| audio_sample_type | [AudioSampleType](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/audiosampletype) | Ο τύπος δείγματος ήχου. |

### Method: set_camera_angle(camera_angle) {#set_camera_angle_camera_angle_13}


```
 set_camera_angle(camera_angle) 
```

Ορίζει τη γωνία της κάμερας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| camera_angle | string | Η γωνία της κάμερας. |

### Method: set_camera_label(camera_label) {#set_camera_label_camera_label_14}


```
 set_camera_label(camera_label) 
```

Ορίζει την ετικέτα της κάμερας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| camera_label | string | Η ετικέτα της κάμερας. |

### Method: set_camera_move(camera_move) {#set_camera_move_camera_move_15}


```
 set_camera_move(camera_move) 
```

Ορίζει την κίνηση της κάμερας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| camera_move | string | Η κίνηση της κάμερας. |

### Method: set_client(client) {#set_client_client_16}


```
 set_client(client) 
```

Ορίζει τον πελάτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| client | string | Ο πελάτης. |

### Method: set_comment(comment) {#set_comment_comment_17}


```
 set_comment(comment) 
```

Ορίζει το σχόλιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| σχόλιο | string | Το σχόλιο. |

### Method: set_composer(composer) {#set_composer_composer_18}


```
 set_composer(composer) 
```

Ορίζει τον συνθέτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| composer | string | Ο συνθέτης. |

### Method: set_director(director) {#set_director_director_19}


```
 set_director(director) 
```

Ορίζει τον σκηνοθέτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| director | string | Ο σκηνοθέτης. |

### Method: set_director_photography(director_photography) {#set_director_photography_director_photography_20}


```
 set_director_photography(director_photography) 
```

Ορίζει τον διευθυντή φωτογραφίας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| director_photography | string | Ο διευθυντής φωτογραφίας. |

### Method: set_duration(duration) {#set_duration_duration_21}


```
 set_duration(duration) 
```

Ορίζει τη διάρκεια.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| duration | [Time](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/time) | Η διάρκεια. |

### Method: set_engineer(engineer) {#set_engineer_engineer_22}


```
 set_engineer(engineer) 
```

Ορίζει τον μηχανικό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| engineer | string | Ο μηχανικός. |

### Method: set_file_data_rate(rate) {#set_file_data_rate_rate_23}


```
 set_file_data_rate(rate) 
```

Ορίζει το ρυθμό δεδομένων του αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rate | [Rational](/psd/python-net/aspose.psd.xmp.types.derived/rational/) | Ο ρυθμός δεδομένων του αρχείου σε megabytes ανά δευτερόλεπτο. |

### Method: set_genre(genre) {#set_genre_genre_24}


```
 set_genre(genre) 
```

Ορίζει το είδος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| genre | string | Το είδος. |

### Method: set_good(good) {#set_good_good_25}


```
 set_good(good) 
```

Ορίζει το καλό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| good | bool | αν οριστεί σε <c>true</c> μια λήψη είναι αξιόλογη. |

### Method: set_instrument(instrument) {#set_instrument_instrument_26}


```
 set_instrument(instrument) 
```

Ορίζει το όργανο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όργανο | string | Το όργανο. |

### Method: set_intro_time(intro_time) {#set_intro_time_intro_time_27}


```
 set_intro_time(intro_time) 
```

Ορίζει το χρόνο εισαγωγής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| intro_time | [Time](/psd/python-net/aspose.psd.xmp.schemas.xmpdm/time) | Ο χρόνος εισαγωγής. |

### Method: set_key(key) {#set_key_key_28}


```
 set_key(key) 
```

Ορίζει το μουσικό κλειδί του ήχου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Το μουσικό κλειδί του ήχου. Ένα από: C, C#, D, D#, E, F, F#, G, G#, A, A#, και B. |

### Method: set_log_comment(comment) {#set_log_comment_comment_29}


```
 set_log_comment(comment) 
```

Ορίζει το σχόλιο καταγραφής του χρήστη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| σχόλιο | string | Το σχόλιο. |

### Method: set_value(key, value) {#set_value_key_value_30}


```
 set_value(key, value) 
```

Ορίζει την τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Η τιμή για προσθήκη σε. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_31}


```
 set_xmp_type_value(key, value) 
```

Ορίζει την τιμή τύπου XMP.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την ορισμένη τιμή. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Η τιμή για ορισμό σε. |

