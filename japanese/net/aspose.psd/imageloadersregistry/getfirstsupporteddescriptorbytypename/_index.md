---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageLoadersRegistry メソッド。タイプ名で最初にサポートされる記述子を取得します"
type: docs
weight: 60
url: /ja/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName method

タイプ名で最初にサポートされている記述子を取得します。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| descriptorTypeName | 文字列 | 記述子の型名です。 |

### 戻り値

最初に見つかったローダー記述子、またはそのような記述子が見つからない場合は null です。

## 備考

最初のローダー記述子は実際には最後に登録されたものになります。

### 関連項目

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


