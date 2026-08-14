---
title: "ColorComponent クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | 新しい [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) クラスのインスタンスを初期化します。<br/>            確認してください |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bit_depth | byte | r | カラー コンポーネント/チャンネルのビット深度を取得します。 |
| 説明 | string | r | カラー コンポーネントの説明を取得します。 |
| full_name | string | r | 名前とスペースで区切られた説明からなるカラー コンポーネントのフルネームを取得します。 |
| name | string | r | カラー コンポーネントの名前を取得します。 |
| permitted_full_names [static] | string | r | 許可されたフルネームを取得します。 |
| 値 | ulong | r/w | 値を取得または設定します。 <br/>            注意してください、現在のビット深度で格納可能な範囲を超える値を設定しようとすると、例外がスローされます。 |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

新しい [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) クラスのインスタンスを初期化します。<br/>            確認してください

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bit_depth | byte | ビット深度。 |
| full_name | string | フルネームです。 |

