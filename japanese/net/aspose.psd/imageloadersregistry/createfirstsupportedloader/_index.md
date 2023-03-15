---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD for .NET API リファレンス
description: ImageLoadersRegistry 方法. 指定されたファイルに適した最初に見つかったローダーを作成しますstreamオプションでloadOptions .
type: docs
weight: 30
url: /ja/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

指定されたファイルに適した最初に見つかったローダーを作成します*stream*オプションで*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |
| loadOptions | LoadOptions | 読み込みオプション。 |

### 戻り値

指定された*stream*と*loadOptions*そのようなローダーが見つからない場合は null.

### 備考

最初のローダーは実際には最後に登録されたものになります.

### 関連項目

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* 名前空間 [Aspose.PSD](../../imageloadersregistry/)
* 組み立て [Aspose.PSD](../../../)


