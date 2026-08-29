---
title: "IRasterImageRawDataLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ラスタ画像生データローダー。"
type: docs
weight: 137
url: /ja/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

ラスタ画像生データローダー。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | 現在の生データ設定を取得します。 |
| [isRawDataAvailable()](#isRawDataAvailable--) | 生データの読み込みがサポートされているかどうかを示す値を取得します。 |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 生データをロードします。 |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


現在の生データ設定を取得します。これらの設定を使用すると、データは変換なしでロードされることに注意してください。

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


生データの読み込みがサポートされているかどうかを示す値を取得します。

**Returns:**
boolean - 生データの読み込みがサポートされている場合は true、そうでない場合は false。
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


生データをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 生データを読み込む矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 読み込まれたデータに使用する生データ設定です。指定された形式でない場合はデータ変換が実行されますのでご注意ください。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 生データローダー。 |

