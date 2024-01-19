---
title: PsdLoadOptions Class
type: docs
weight: 30
url: /python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Initializes a new instance of the PsdLoadOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Gets or sets whether to save with the rendered image, with or without a warp transform. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the [Image](/psd/python-net/aspose.psd/image/) background [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Gets or sets the data recovery mode. |
| ignore_alpha_channel | bool | r/w | Gets or sets a value indicating whether [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution. |
| load_effects_resource | bool | r/w | Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded). When set this option only supported effects will be rendered to final merged image. |
| read_only_mode | bool | r/w | Gets or sets a value indicating whether [use read only mode]. This is read-only mode, supported for identical compatibility with Adobe Photoshop.<br/>            When this option is set, all changes applied for layers will not be saved to final image. All data is used from ImageData section, so it is identical to Photoshop. <br/>            By default all loaded images are not identical to Adobe Photoshop compatible. |
| use_disk_for_load_effects_resource | bool | r/w | Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false). |
| use_icc_profile_conversion | bool | r/w | Gets or sets a value indicating whether ICC profile conversion should be applied. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Initializes a new instance of the PsdLoadOptions class

