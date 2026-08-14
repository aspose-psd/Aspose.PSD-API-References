---
title: "PsdLoadOptions クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | 新しい PsdLoadOptions クラスのインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | ワープ変換の有無にかかわらず、レンダリングされた画像と共に保存するかどうかを取得または設定します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | [Image](/psd/python-net/aspose.psd/image/) の背景 [Color](/psd/python-net/aspose.psd/color/) を取得または設定します。 |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | データ復旧モードを取得または設定します。 |
| ignore_alpha_channel | bool | r/w | Gets or sets a value indicating whether [ignore alpha channel]。 |
| ignore_text_layer_width_on_update | bool | r/w | Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution。 |
| load_effects_resource | bool | r/w | Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded)。 When set this option only supported effects will be rendered to final merged image。 |
| read_only_mode | bool | r/w | Gets or sets a value indicating whether [use read only mode]。 This is read-only mode, supported for identical compatibility with Adobe Photoshop.<br/>            When this option is set, all changes applied for layers will not be saved to final image. All data is used from ImageData section, so it is identical to Photoshop. <br/>            By default all loaded images are not identical to Adobe Photoshop compatible。 |
| use_disk_for_load_effects_resource | bool | r/w | Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false)。 |
| use_icc_profile_conversion | bool | r/w | ICC プロファイル変換を適用すべきかどうかを示す値を取得または設定します。 |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

新しい PsdLoadOptions クラスのインスタンスを初期化します

