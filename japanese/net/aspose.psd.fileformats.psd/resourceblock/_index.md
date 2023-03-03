---
title: Class ResourceBlock
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.ResourceBlock クラス. リソースブロック.
type: docs
weight: 3610
url: /ja/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

リソースブロック.

```csharp
public abstract class ResourceBlock
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | 必要最小限の PSD バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。サイズを均等にするためにパディングされた Pascal 文字列 (null 名は 2 バイトの 0 で構成されます). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソース署名を取得します。常に '8BIM'. である必要があります |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソース ブロック サイズをバイト単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 指定したストリームにリソース ブロックを保存します。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | リソース値を検証します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady. のリソース署名 |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | 通常の Photoshop リソース署名。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | リソースブロックの状態を表します。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 組み立て [Aspose.PSD](../../)


