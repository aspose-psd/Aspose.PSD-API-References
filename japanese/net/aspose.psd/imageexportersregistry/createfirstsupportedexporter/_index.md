---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageExportersRegistry メソッド。指定された保存オプションと画像に適合する最初に見つかったエクスポーターを作成します"
type: docs
weight: 30
url: /ja/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

指定された保存オプションと画像に適した最初に見つかったエクスポーターを作成します。

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | エクスポートする画像。 |
| オプション | ImageOptionsBase | エクスポートに使用する保存オプション。 |

### 戻り値

指定された画像と保存オプションをサポートするエクスポーター、または該当するエクスポーターが見つからない場合は null。

## 備考

最初のエクスポーターは実際には最後に登録されたものになります。

### 関連項目

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


