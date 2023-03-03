---
title: ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName
second_title: Aspose.PSD for .NET API リファレンス
description: ImageLoadersRegistry 方法. 型名でサポートされている最初の記述子を取得します
type: docs
weight: 60
url: /ja/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName method

型名でサポートされている最初の記述子を取得します。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| descriptorTypeName | String | 記述子の型名。 |

### 戻り値

最初に見つかったローダー記述子、またはそのような記述子が見つからない場合は null。

### 備考

最初のローダー記述子は、実際には最後に登録されます。

### 関連項目

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [ImageLoadersRegistry](../)
* 名前空間 [Aspose.PSD](../../imageloadersregistry/)
* 組み立て [Aspose.PSD](../../../)


