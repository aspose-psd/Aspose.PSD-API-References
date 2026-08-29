---
title: "クラス ImageExportersRegistry"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageExportersRegistry クラス。画像エクスポーターのレジストリを表します。"
type: docs
weight: 5100
url: /ja/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

画像エクスポーター レジストリを表します。

```csharp
public static class ImageExportersRegistry
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | 登録されたエクスポーター記述子を取得します。 |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | 登録されたエクスポート形式を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | 指定された保存オプションと画像に適した最初に見つかったエクスポーターを作成します。 |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | 指定された保存オプションと画像に適した最初に見つかったサポートされている記述子を取得します。 |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | 指定された画像エクスポーター記述子を登録します。 |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | エクスポーターを登録します。 |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | エクスポーターの登録を解除します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


