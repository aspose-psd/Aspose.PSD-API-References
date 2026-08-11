---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageLoadersRegistry メソッド。指定された *stream* に適合し、オプションで *loadOptions* を使用できる最初に見つかったローダーを作成します"
type: docs
weight: 30
url: /ja/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

指定された *stream* に適合し、必要に応じて *loadOptions* も考慮した最初に見つかったローダーを作成します。

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ストリームです。 |
| loadOptions | LoadOptions | ロードオプション。 |

### 戻り値

指定された *stream* と *loadOptions* をサポートするローダー、またはそのようなローダーが見つからない場合は null を返します。

## 備考

最初のローダーは実際には最後に登録されたものになります。

### 関連項目

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


