---
title: "GaussWienerFilterOptions クラス"
type: docs
weight: 60
url: /ja/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | 新しい [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) クラスのインスタンスを初期化します。<br/>            デフォルト設定です。 |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | 新しい [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | double | r/w | この [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) がグレースケールかどうかを示す値を取得または設定します。<br/>            グレースケールモードまたはRGBモードを返します。 |
| grayscale | bool | r/w | is_partial_loaded |
| このインスタンスが部分的にロードされているかどうかを示す値を取得します。 | bool | r | 長さ |
| 半径 | int | r/w | 半径を取得または設定します。 |
| スムーズを取得または設定します。 | double | r/w | snr |
| SNR（信号対雑音比）を取得または設定します。<br/>            推奨範囲 0.002 - 0.009、デフォルト値 = 0.007 | double | r/w | 長さ。 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

新しい [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) クラスのインスタンスを初期化します。<br/>            デフォルト設定です。

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

新しい [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 半径 | int | 半径です。 |
| スムーズを取得または設定します。 | double | グラドゥスの角度。 |

