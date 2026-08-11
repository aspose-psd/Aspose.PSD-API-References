---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageLoadersRegistry メソッド。指定されたストリームに適した最初に見つかったサポートされる記述子を取得し、オプションで loadOptions を使用します"
type: docs
weight: 40
url: /ja/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

指定された *stream* に適合し、必要に応じて *loadOptions* も考慮した最初に見つかったサポートされている記述子を取得します。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ストリームです。 |
| loadOptions | LoadOptions | ロードオプション。 |

### 戻り値

指定された *stream* と *loadOptions* をサポートするローダー記述子、またはそのような記述子が見つからない場合は null です。

## 備考

最初のローダー記述子は実際には最後に登録されたものになります。

### 関連項目

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


