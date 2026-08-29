---
title: "クラス LinkDataSource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource クラス。リンクされたファイルまたは PSD ファイル内のアセットに関する情報を含む LinkDataSource クラスを定義します。"
type: docs
weight: 2990
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

PSD ファイル内のリンクファイルまたはアセットに関する情報を含む LinkDataSource クラスを定義します。

```csharp
public abstract class LinkDataSource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD アセットがロックされているかどうかを示す値を取得または設定します。Adobe® Photoshop® СС ライブラリ資産のロック状態です。 |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС ライブラリ資産の変更日時を取得または設定します。 |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データソース内の子ドキュメント識別子を取得または設定します。 |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | 取得または設定します 現在選択されている子ドキュメントのコンプの ID を取得または設定します。選択されていない場合は -1 になります。コンプはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe® Photoshop® ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、このプロパティはスマートオブジェクト用のレイヤーコンプ選択識別子を取得します。 [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | 取得または設定します PSD フォーマットの LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。 |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | 取得または設定します Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。 |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | 取得または設定します このリンクデータソースがファイルオープン記述子（CompId と OriginalCompId）を持つかどうかを示す値を取得または設定します。 |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | 取得します この PSD リンクデータソースが Adobe® Photoshop® СС Library アイテムにリンクしているかどうかを示す値を取得します。 |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | 取得します リンクデータソースの長さ（バイト単位）を取得します。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | 取得します 子ドキュメントの現在選択されているコンプの元の ID を取得します。選択されていない場合は -1 になります。このプロパティはスマートオブジェクト用の元のレイヤーコンプ選択識別子を取得します。 [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | 取得します Adobe® Photoshop® グローバルリンクリソース内のデータソースの元のファイル名を取得します。 |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | 取得します Adobe® Photoshop® グローバルリンクデータソースのタイプを取得します。以下のいずれか、またはなしです：PSD Lnk2Resource に対応する埋め込みリンクファイル liFD、PSD LnkeResource に対応する外部リンクファイル liFE、リンクファイルエイリアス liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | 取得します PSD リンクリソース内のデータソースのグローバル一意識別子を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | 取得します PSD LnkE / Lnk2 リソース内のデータソースのバージョンを取得します。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


