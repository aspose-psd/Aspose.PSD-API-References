---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API リファレンス
description: ImageExportersRegistry 方法. 指定された保存オプションとイメージに適した最初に見つかったサポートされている記述子を取得します
type: docs
weight: 40
url: /ja/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

指定された保存オプションとイメージに適した最初に見つかったサポートされている記述子を取得します。

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Image | エクスポートするイメージ。 |
| options | ImageOptionsBase | オプション。 |

### 戻り値

指定されたイメージおよび保存オプションをサポートするエクスポーター記述子、またはそのような記述子が見つからない場合は null.

### 備考

最初のエクスポーター記述子は、実際には最後に登録されたものになります.

### 関連項目

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* 名前空間 [Aspose.PSD](../../imageexportersregistry/)
* 組み立て [Aspose.PSD](../../../)


