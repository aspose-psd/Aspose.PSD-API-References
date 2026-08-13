---
title: "PsdLoadOptions 类"
type: docs
weight: 30
url: /zh/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | 初始化一个新的 PsdLoadOptions 类实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | 读/写 | 获取或设置是否在保存时使用渲染图像，带或不带扭曲变换。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置 [Image](/psd/python-net/aspose.psd/image/) 背景 [Color](/psd/python-net/aspose.psd/color/)。 |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | 获取或设置数据恢复模式。 |
| ignore_alpha_channel | bool | 读/写 | 获取或设置一个值，指示是否 [ignore alpha channel]。 |
| ignore_text_layer_width_on_update | bool | 读/写 | 获取或设置一个值，指示在 UpdateText 操作执行时是否会忽略 PSD 文本图层的固定宽度。 |
| load_effects_resource | bool | 读/写 | 获取或设置一个值，指示是否 [load effects resource]（默认情况下资源未加载）。设置此选项后，仅支持的效果将渲染到最终合并的图像中。 |
| read_only_mode | bool | 读/写 | 获取或设置一个值，指示是否 [use read only mode]。这是只读模式，支持与 Adobe Photoshop 完全兼容。<br/>            设置此选项后，对图层所做的所有更改将不会保存到最终图像。所有数据均来自 ImageData 部分，因此与 Photoshop 完全相同。 <br/>            默认情况下，所有加载的图像都不与 Adobe Photoshop 完全兼容。 |
| use_disk_for_load_effects_resource | bool | 读/写 | 获取或设置一个值，指示是否 [use disk for load effects resource]（默认使用磁盘加载效果资源，但通过将此值设为 false 可以使用内存，如果内存足够）。 |
| use_icc_profile_conversion | bool | 读/写 | 获取或设置一个值，指示是否应应用 ICC 配置文件转换。 |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

初始化一个新的 PsdLoadOptions 类实例

