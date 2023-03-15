---
title: ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat
second_title: Aspose.PSD for .NET API リファレンス
description: ImageLoadersRegistry 方法. タイプ名でサポートされている最初のファイル形式を取得します
type: docs
weight: 50
url: /ja/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

タイプ名でサポートされている最初のファイル形式を取得します。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileFormat | FileFormat | サポートされている記述子ファイル形式。 |

### 戻り値

最初に見つかったローダー記述子、またはそのような記述子が見つからない場合は null。

### 備考

最初のローダー記述子は、実際には最後に登録されます。

### 関連項目

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* 名前空間 [Aspose.PSD](../../imageloadersregistry/)
* 組み立て [Aspose.PSD](../../../)


