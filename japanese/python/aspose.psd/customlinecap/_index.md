---
title: "CustomLineCap クラス"
type: docs
weight: 1010
url: /ja/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | 指定されたアウトラインと塗りつぶしで [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | 指定された既存の [LineCap](/psd/python-net/aspose.psd/linecap/) 列挙体から、指定されたアウトラインと塗りつぶしで [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | 指定された既存の[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体から、指定されたアウトライン、塗り、インセットを使用して、[CustomLineCap](/psd/python-net/aspose.psd/customlinecap/)クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | この[CustomLineCap](/psd/python-net/aspose.psd/customlinecap/)が基づく[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体を取得または設定します。 |
| base_inset | float | r/w | キャップと線の間の距離を取得または設定します。 |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | カスタムキャップの塗りを定義するオブジェクトを取得または設定します。 |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | この[CustomLineCap](/psd/python-net/aspose.psd/customlinecap/)オブジェクトを構成する線がどのように結合されるかを決定する[LineJoin](/psd/python-net/aspose.psd/linejoin/)列挙体を取得または設定します。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | カスタムキャップのアウトラインを定義するオブジェクトを取得または設定します。 |
| width_scale | float | r/w | この[CustomLineCap](/psd/python-net/aspose.psd/customlinecap/)クラスオブジェクトを、オブジェクトの幅に対して拡大縮小する量を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | このカスタムキャップを構成する線の開始と終了に使用されるキャップを取得します。 |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | このカスタムキャップを構成する線の開始と終了に使用されるキャップを設定します。 |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

指定されたアウトラインと塗りつぶしで [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | カスタムキャップの塗りを定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)オブジェクトです。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | カスタムキャップのアウトラインを定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)オブジェクトです。 |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

指定された既存の [LineCap](/psd/python-net/aspose.psd/linecap/) 列挙体から、指定されたアウトラインと塗りつぶしで [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | カスタムキャップの塗りを定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)オブジェクトです。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | カスタムキャップのアウトラインを定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)オブジェクトです。 |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | カスタムキャップを作成する元となるラインキャップです。 |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

指定された既存の[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体から、指定されたアウトライン、塗り、インセットを使用して、[CustomLineCap](/psd/python-net/aspose.psd/customlinecap/)クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | カスタムキャップの塗りを定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)オブジェクトです。 |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | カスタムキャップのアウトラインを定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)オブジェクトです。 |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | カスタムキャップを作成する元となるラインキャップです。 |
| base_inset | float | キャップと線の間の距離です。 |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

このカスタムキャップを構成する線の開始と終了に使用されるキャップを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | このキャップ内の線の開始時に使用される[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体です。 |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | このキャップ内の線の終了時に使用される[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体です。 |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

このカスタムキャップを構成する線の開始と終了に使用されるキャップを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | このキャップ内の線の開始時に使用される[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体です。 |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | このキャップ内の線の終了時に使用される[LineCap](/psd/python-net/aspose.psd/linecap/)列挙体です。 |

