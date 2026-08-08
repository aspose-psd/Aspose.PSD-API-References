---
title: "IImageLoaderDescriptor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ローダーのプロパティを指定する画像ローダーディスクリプタです。"
type: docs
weight: 124
url: /ja/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

ローダーのプロパティを指定する画像ローダーデスクリプタです。ローダーデスクリプタは、各画像ローダーインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | 画像ローダーが指定されたストリームから新しい画像を読み取れるか、オプションで loadOptions を使用して判定します。 |
| [createInstance()](#createInstance--) | 新しいローダーインスタンスを作成します。 |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


画像ローダーが指定されたストリームから新しい画像を読み取れるか、オプションで loadOptions を使用して判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | loadOptions によって指定されたファイル形式の詳細です。loadOptions は null の可能性があります。 |

**Returns:**
boolean - このデスクリプタで作成された画像ローダーがストリームから画像を読み取れる場合は true、そうでない場合は false。
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


新しいローダーインスタンスを作成します。

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
