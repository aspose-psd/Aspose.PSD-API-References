---
title: "IImageCreatorDescriptor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "クリエイターのプロパティを指定する画像クリエイターディスクリプタです。"
type: docs
weight: 119
url: /ja/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

画像作成記述子は作成者のプロパティを指定します。作成者記述子は、各画像作成インスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | 画像作成者が imageOptions を使用して新しい画像を作成できるかどうかを判定します。 |
| [createInstance()](#createInstance--) | 新しい作成者インスタンスを作成します。 |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


画像作成者が imageOptions を使用して新しい画像を作成できるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像オプション。 |

**Returns:**
boolean - この記述子によって作成された画像作成者が、指定された imageOptions を使用して画像データを作成できる場合は true、そうでない場合は false。
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


新しい作成者インスタンスを作成します。

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
