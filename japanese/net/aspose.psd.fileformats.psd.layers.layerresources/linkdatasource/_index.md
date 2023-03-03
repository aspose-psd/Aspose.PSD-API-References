---
title: Class LinkDataSource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource クラス. PSD ファイル内のリンクされたファイルまたはアセットに関する情報を含む LinkDataSource クラスを定義します
type: docs
weight: 2690
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
## LinkDataSource class

PSD ファイル内のリンクされたファイルまたはアセットに関する情報を含む LinkDataSource クラスを定義します。

```csharp
public abstract class LinkDataSource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD アセットがロックされているかどうかを示す値を取得または設定します。 Adobe® Photoshop® СС Libraries アセットのアセット ロック状態。 |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС Libraries アセットのアセット変更時刻を取得または設定します。 |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データ ソースの子ドキュメント識別子を取得または設定します。 |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | 子ドキュメントの現在選択されているコンプの ID を取得または設定します。何も選択されていない場合は -1 になります。 コンプは、デザイナーが作成できるページ レイアウトのコンポジションです。レイヤーカンプを使用すると、1 つの Adobe® Photoshop® ファイルでレイアウトの複数のバージョン を作成、管理、および表示できます。レイヤーカンプは、レイヤーパネルの状態のスナップショットです。レイヤーカンプは 3 種類のレイヤーオプションを保存しますが、 このプロパティは、スマートオブジェクトのレイヤーカンプ選択識別子を取得します. [スマートオブジェクトのレイヤーカンプ](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | PSD 形式のファイル作成者を取得または設定します LnkE / Lnk2 リソース. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Adobe® Photoshop® Lnk2 / LnkE リソースに含まれる、またはリンクされる埋め込みファイルまたは外部ファイルのタイプを取得または設定します。 |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | このリンク データ ソースに次のファイル オープン記述子があるかどうかを示す値を取得または設定します: CompId および OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | この PSD リンク データ ソースが Adobe® Photoshop® СС ライブラリ アイテムにリンクしているかどうかを示す値を取得します。 |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | リンク データ ソースの長さをバイト単位で取得します。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | 子ドキュメントで現在選択されている Comp の元の ID を取得します。何も選択されていない場合は -1 になります。 このプロパティは、スマート オブジェクトの元のレイヤー Comp 選択識別子を取得します。 [スマートオブジェクトのレイヤーカンプ](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Adobe® Photoshop® グローバル リンク リソース内のデータ ソースの元のファイル名を取得します。 |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Adobe® Photoshop® グローバル リンク データ ソース タイプを取得します。次のいずれか、またはなしのいずれかになります。 PSD に対応する埋め込みリンク ファイル liFD Lnk2Resource PSD に対応する外部リンク ファイル liFE LnkeResource リンク ファイル エイリアス liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | PSD リンク リソース内のデータ ソースのグローバル一意識別子を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | PSD LnkE / Lnk2 リソース内のデータ ソースのバージョンを取得します。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


