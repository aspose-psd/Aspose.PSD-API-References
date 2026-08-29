---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageLoadersRegistry メソッド。タイプ名で最初にサポートされるファイル形式を取得します"
type: docs
weight: 50
url: /ja/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

型名で最初にサポートされているファイル形式を取得します。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileFormat | FileFormat | サポートされている記述子ファイル形式です。 |

### 戻り値

最初に見つかったローダー記述子、またはそのような記述子が見つからない場合は null です。

## 備考

最初のローダー記述子は実際には最後に登録されたものになります。

### 関連項目

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


