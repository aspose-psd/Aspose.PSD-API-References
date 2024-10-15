---
title: ThumbnailResource Class
type: docs
weight: 250
url: /python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | Initializes a new instance of the ThumbnailResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | The resource signature of ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | The regular Photoshop resource signature. |
| bits_pixel | short | r/w | Gets or sets the bits pixel. |
| data_size | int | r | Gets the resource data size in bytes. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Gets or sets the thumbnail data format. |
| height | int | r/w | Gets or sets the height of thumbnail in pixels. |
| id | short | r/w | Gets or sets the unique identifier for the resource. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Gets or sets the JPEG options. Suitable when thumbnail resource is saved into JPEG file format only. This option has no effect when RAW format is defined. |
| minimal_version | int | r | Gets the minimal required psd version. |
| name | string | r/w | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| planes_count | short | r/w | Gets or sets the planes count. |
| signature | int | r | Gets the resource signature. Should be always '8BIM'. |
| size | int | r | Gets the resource block size in bytes including its data. |
| size_after_compression | int | r | Gets or sets the size after compression. Used for consistency check. |
| thumbnail_argb_32_data | int | r/w | Gets or sets the 32-bit ARGB thumbnail data. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the thumbnail data. |
| total_size | int | r | Gets the total data size. |
| width | int | r/w | Gets or sets the width of thumbnail in pixels. |
| width_bytes | int | r | Gets the row width in bytes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the resource block data. |
| validate_values() | Validates the resource values. |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

Initializes a new instance of the ThumbnailResource class

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the resource block data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

