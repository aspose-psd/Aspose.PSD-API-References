---
title: Class ImageExportersRegistry
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageExportersRegistry クラス. イメージ エクスポータ レジストリを表します
type: docs
weight: 4630
url: /ja/net/aspose.psd/imageexportersregistry/
---
## ImageExportersRegistry class

イメージ エクスポータ レジストリを表します。

```csharp
public static class ImageExportersRegistry
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | 登録済みのエクスポーター記述子を取得します。 |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | 登録されているエクスポート形式を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | 指定された保存オプションとイメージに適した最初に見つかったエクスポーターを作成します。 |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | 指定された保存オプションとイメージに適した最初に見つかったサポートされている記述子を取得します。 |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | 指定されたイメージ エクスポーター記述子を登録します。 |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | エクスポーターを登録します。 |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | エクスポーターを登録解除します。 |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


