---
title: "LiFeDataSource クラス"
type: docs
weight: 520
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | 新しい [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) クラスのインスタンスを初期化します。 |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | 新しい [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| adobe_stock_id | string | r/w | Adobe® Photoshop® CC ライブラリ用のグラフィックライブラリ AdobeStockId を取得または設定します。 |
| adobe_stock_license_state | string | r | 利用可能な場合、Adobe® Photoshop® CC ライブラリ用の Adobe Stock ライセンスの状態を取得します。 |
| asset_locked_state | bool | r/w | PSD アセットがロックされているかどうかを示す値を取得または設定します。<br/>            Adobe® Photoshop® СС ライブラリ資産用のアセットロック状態です。 |
| asset_mod_time | double | r/w | Adobe® Photoshop® СС Libraries のアセットの変更時刻を取得または設定します。 |
| child_doc_id | string | r/w | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データソースにおける子ドキュメント識別子を取得または設定します。 |
| comp_id | int | r/w | 子ドキュメントに対して現在選択されているコンプの ID を取得または設定します。選択されていない場合は -1 になります。<br/>            コンプはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe® Photoshop® ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。<br/>            レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、<br/>            このプロパティはスマートオブジェクト用のレイヤーコンプ選択識別子を取得します。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">スマートオブジェクトにおけるレイヤーコンプ</see> |
| date | datetime | r/w | PSD LnkE リソースの LiFE データソースにある外部ファイルの最終書き込み日時を取得または設定します。 |
| element_name | string | r/w | Adobe® Photoshop® CC Libraries 用のグラフィックライブラリ要素名を取得または設定します。 |
| element_ref | string | r/w | Adobe® Photoshop® CC Libraries 用のグラフィックライブラリ要素参照を取得または設定します。 |
| file_creator | string | r/w | PSD 形式の LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。 |
| file_name | string | r/w | PSD リンクリソース内の外部または埋め込みファイルの名前を取得または設定します。 |
| file_size | long | r/w | PSD LnkE リソースの LiFE データソースにある外部ファイルのサイズを取得または設定します。 |
| file_type | string | r/w | Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。 |
| full_path | string | r/w | PSD LnkE リソースの LiFE データソースにある外部ファイルのフルパスを取得または設定します。 |
| has_file_open_descriptor | bool | r/w | このリンクデータソースにファイルオープンディスクリプタ（CompId と OriginalCompId）があるかどうかを示す値を取得または設定します。 |
| is_library_link | bool | r | この PSD リンクデータソースが Adobe® Photoshop® СС Library アイテムにリンクしているかどうかを示す値を取得します。 |
| 長さを取得または設定します。 | long | r | リンク データ ソースの長さ（バイト単位）を取得します。 |
| original_comp_id | int | r | 現在選択されている子ドキュメントの Comp の元の ID を取得します。選択されていない場合は -1 になります。<br/>            このプロパティは Smart Objects の元のレイヤー Comp 選択識別子を取得します。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Smart Objects のレイヤー Comp</see> |
| original_file_name | string | r | Adobe® Photoshop® グローバルリンクリソース内のデータ ソースの元のファイル名を取得します。 |
| relative_path | string | r/w | PSD LnkE リソースの LiFE データ ソースにある外部ファイルの相対パスを取得または設定します。 |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Adobe® Photoshop® グローバルリンクデータ ソースのタイプを取得します。以下のいずれか、またはなしになる可能性があります：<br/>            PSD Lnk2Resource に対応する埋め込みリンクファイル liFD<br/>            PSD LnkeResource に対応する外部リンクファイル liFE<br/>            リンクファイルエイリアス liFA |
| unique_id | Guid | r | PSD リンクリソース内のデータ ソースのグローバル一意識別子を取得します。 |
| version | int | r | PSD LnkE / Lnk2 リソース内のデータ ソースのバージョンを取得します。 |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

新しい [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) クラスのインスタンスを初期化します。

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

新しい [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| version | int | バージョン。 |
| unique_id | Guid | 一意識別子。 |
| original_file_name | string | 元のファイル名。 |
| file_type | string | ファイルの種類。 |
| file_creator | string | ファイル作成者。 |

