---
title: "IImageExporter"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "画像エクスポーターです。"
type: docs
weight: 121
url: /ja/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

画像エクスポーター。内部の Aspose.Imaging フォーマットから指定されたデータフォーマットへデータをエクスポートできる。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 指定された画像データを指定されたデータフォーマットにエクスポートする。 |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 指定された画像データを指定されたデータフォーマットにエクスポートする。 |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


指定された画像データを指定されたデータフォーマットにエクスポートする。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | エクスポートする画像データ。 |
| stream | java.io.OutputStream | データをエクスポートするストリーム。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像エクスポートのオプション |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


指定された画像データを指定されたデータフォーマットにエクスポートする。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | エクスポートする画像データ。 |
| stream | java.io.OutputStream | データをエクスポートするストリーム。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像エクスポートのオプション |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 境界矩形。 |

