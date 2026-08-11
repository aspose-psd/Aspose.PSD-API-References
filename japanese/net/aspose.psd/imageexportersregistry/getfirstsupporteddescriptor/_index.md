---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageExportersRegistry メソッド。指定された保存オプションと画像に適合する最初に見つかったサポートされている記述子を取得します"
type: docs
weight: 40
url: /ja/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

指定された保存オプションと画像に適した最初に見つかったサポートされている記述子を取得します。

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | エクスポートする画像。 |
| オプション | ImageOptionsBase | オプションです。 |

### 戻り値

指定された画像と保存オプションをサポートするエクスポーター記述子、または該当する記述子が見つからない場合は null。

## 備考

最初のエクスポーター記述子は実際には最後に登録されたものになります。

### 関連項目

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


