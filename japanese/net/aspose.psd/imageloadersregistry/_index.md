---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageLoadersRegistry クラス. イメージ ローダー レジストリを表します
type: docs
weight: 4780
url: /ja/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

イメージ ローダー レジストリを表します。

```csharp
public static class ImageLoadersRegistry
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | 登録された記述子を取得します。 |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | 登録されている画像読み込みフォーマットを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | 指定されたファイルに適した最初に見つかったローダーを作成します*stream*オプションで*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | 指定された*stream*オプションで*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | タイプ名でサポートされている最初のファイル形式を取得します。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | 型名でサポートされている最初の記述子を取得します。 |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | 指定されたイメージローダー記述子を登録します。 |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | ローダを登録します。 |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | ローダーの登録を解除します。 |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


