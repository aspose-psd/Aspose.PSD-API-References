---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API リファレンス
description: ImageLoadersRegistry 方法. 指定されたstreamオプションでloadOptions .
type: docs
weight: 40
url: /ja/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

指定された*stream*オプションで*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |
| loadOptions | LoadOptions | 読み込みオプション。 |

### 戻り値

指定された*stream*と*loadOptions*そのような記述子が見つからない場合は null.

### 備考

最初のローダー記述子は、実際には最後に登録されます.

### 関連項目

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* 名前空間 [Aspose.PSD](../../imageloadersregistry/)
* 組み立て [Aspose.PSD](../../../)


