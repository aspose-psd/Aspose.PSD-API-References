---
title: "FilterEffectMaskData Κλάση"
type: docs
weight: 310
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Αρχικοποιεί μια νέα παρουσία της [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) κλάσης. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Λαμβάνει τα κανάλια. |
| guid | string | r | Λαμβάνει το GUID. |
| μήκος | int | r | Λαμβάνει το μήκος δεδομένων μάσκας φίλτρου σε byte. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Λαμβάνει το ορθογώνιο της μάσκας φύλλου. |
| max_channels | int | r | Λαμβάνει το μέγιστο αριθμό καναλιών. |
| pixels_depth | int | r | Λαμβάνει το βάθος εικονοστοιχείων. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Λαμβάνει το ορθογώνιο των καναλιών. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Λαμβάνει τη μάσκα φύλλου. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Λαμβάνει τη μάσκα χρήστη. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Αρχικοποιεί μια νέα παρουσία της [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| guid | string | Το guid του πόρου. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο των καναλιών. |
| pixels_depth | int | Το βάθος εικονοστοιχείων. |
| max_channels | int | Η τιμή μέγιστων καναλιών. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Τα κανάλια. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Η μάσκα χρήστη. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο μάσκα φύλλου. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Η μάσκα φύλλου. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |

