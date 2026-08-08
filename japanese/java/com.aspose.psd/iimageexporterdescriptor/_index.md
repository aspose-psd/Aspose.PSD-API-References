---
title: "IImageExporterDescriptor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "画像エクスポーターのディスクリプタを表します。"
type: docs
weight: 122
url: /ja/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

画像エクスポーター記述子を表します。エクスポーター記述子は、各エクスポーターインスタンスをメモリに保持する必要性とマルチスレッドの問題を克服するために使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 画像エクスポーターが、保存オプションで指定された画像形式に指定された画像をエクスポートできるかどうかを判断します。 |
| [createInstance()](#createInstance--) | 新しいエクスポーターインスタンスを作成します。 |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


画像エクスポーターが、保存オプションで指定された画像形式に指定された画像をエクスポートできるかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | エクスポートする画像です。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプションの基底です。 |

**Returns:**
boolean -  true  この記述子によって作成されたエクスポーターが、指定されたファイル形式に指定された画像をエクスポートできる場合は true、そうでない場合は false。
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


新しいエクスポーターインスタンスを作成します。

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
