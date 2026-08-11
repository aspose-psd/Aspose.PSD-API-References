---
title: "ImageLoadersRegistry クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageLoadersRegistry クラス。画像ローダーのレジストリを表します。"
type: docs
weight: 5270
url: /ja/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

画像ローダー レジストリを表します。

```csharp
public static class ImageLoadersRegistry
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | 登録された記述子を取得します。 |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | 登録されている画像読み込み形式を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | 指定された *stream* に適合し、必要に応じて *loadOptions* も考慮した最初に見つかったローダーを作成します。 |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | 指定された *stream* に適合し、必要に応じて *loadOptions* も考慮した最初に見つかったサポートされている記述子を取得します。 |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | 型名で最初にサポートされているファイル形式を取得します。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | タイプ名で最初にサポートされている記述子を取得します。 |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | 指定された画像ローダー記述子を登録します。 |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | ローダーを登録します。 |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | ローダーの登録を解除します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


