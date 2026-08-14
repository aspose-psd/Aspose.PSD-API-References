---
title: "Κλάση SharpenSmartFilter"
type: docs
weight: 40
url: /el/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---

**Summary:** The Sharpen smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SharpenSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [SharpenSmartFilter()](#SharpenSmartFilter__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/). |
| [SharpenSmartFilter(source_descriptor)](#SharpenSmartFilter_source_descriptor_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | Το αναγνωριστικό του τρέχοντος έξυπνου φίλτρου. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| filter_id | int | r | Λαμβάνει το αναγνωριστικό τύπου του έξυπνου φίλτρου. |
| is_enabled | bool | r/w | Λαμβάνει ή ορίζει την κατάσταση ενεργοποίησης του έξυπνου φίλτρου. |
| name | string | r | Λαμβάνει το όνομα του έξυπνου φίλτρου. |
| opacity | double | r/w | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Η δομή περιγραφέα πηγής με δεδομένα έξυπνου φίλτρου. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο εικόνας [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Εφαρμόζει το τρέχον φίλτρο στα δεδομένα μάσκας της εισόδου [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [clone()](#clone__3) | Δημιουργεί το κλώνο μελών της τρέχουσας παρουσίας του τύπου. |


### Constructor: SharpenSmartFilter() {#SharpenSmartFilter__1}


```
 SharpenSmartFilter() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/).

### Constructor: SharpenSmartFilter(source_descriptor) {#SharpenSmartFilter_source_descriptor_2}


```
 SharpenSmartFilter(source_descriptor) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | Η δομή περιγραφέα με πληροφορίες έξυπνου φίλτρου. |

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Εφαρμόζει το τρέχον φίλτρο στην είσοδο εικόνας [RasterImage](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η raster εικόνα. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Εφαρμόζει το τρέχον φίλτρο στα δεδομένα μάσκας της εισόδου [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Το στρώμα με δεδομένα μάσκας. |

### Method: clone() {#clone__3}


```
 clone() 
```

Δημιουργεί το κλώνο μελών της τρέχουσας παρουσίας του τύπου.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Επιστρέφει το κλώνο μελών της τρέχουσας παρουσίας του τύπου. |


