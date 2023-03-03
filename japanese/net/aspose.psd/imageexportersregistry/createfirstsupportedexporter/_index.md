---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: Aspose.PSD for .NET API リファレンス
description: ImageExportersRegistry 方法. 指定された保存オプションとイメージに適した最初に見つかったエクスポーターを作成します
type: docs
weight: 30
url: /ja/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

指定された保存オプションとイメージに適した最初に見つかったエクスポーターを作成します。

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Image | エクスポートするイメージ。 |
| options | ImageOptionsBase | エクスポートに使用する保存オプション。 |

### 戻り値

指定されたイメージと保存オプションをサポートするエクスポーター、またはそのようなエクスポーターが見つからない場合は null。

### 備考

最初のエクスポーターは、実際には最後に登録されたものになります。

### 関連項目

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* 名前空間 [Aspose.PSD](../../imageexportersregistry/)
* 組み立て [Aspose.PSD](../../../)


