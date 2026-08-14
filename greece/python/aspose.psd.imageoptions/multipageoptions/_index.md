---
title: "MultiPageOptions Κλάση"
type: docs
weight: 70
url: /el/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Λαμβάνει ή ορίζει την περιοχή εξαγωγής. |
| merge_layers | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [συγχώνευση επιπέδων]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Λαμβάνει ή ορίζει τη λειτουργία. |
| output_layers_names | string | r/w | Λαμβάνει ή ορίζει τα ονόματα των εξόδων επιπέδων (Λειτουργεί εάν η μορφή εξαγωγής υποστηρίζει ονοματοδοσία επιπέδων, για παράδειγμα για Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization της σελίδας. |
| page_titles | string | r/w | Λαμβάνει ή ορίζει τους τίτλους της σελίδας. |
| pages | int | r/w | Λαμβάνει ή ορίζει τις σελίδες. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Αρχικοποιεί τις σελίδες από τον πίνακα περιοχών |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_titles | string | Οι τίτλοι της σελίδας. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_titles | string | Οι τίτλοι της σελίδας. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pages | int | Οι σελίδες. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pages | int | Ο πίνακας των σελίδων. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Το [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Αρχικοποιεί ένα νέο αντικείμενο της [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) κλάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Το [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Αρχικοποιεί τις σελίδες από τον πίνακα περιοχών

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Οι περιοχές. |

