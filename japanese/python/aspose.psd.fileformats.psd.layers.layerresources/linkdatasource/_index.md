---
title: "LinkDataSource クラス"
type: docs
weight: 530
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---

**Summary:** Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | PSD アセットがロックされているかどうかを示す値を取得または設定します。<br/>            Adobe® Photoshop® СС ライブラリ資産用のアセットロック状態です。 |
| asset_mod_time | double | r/w | Adobe® Photoshop® СС Libraries のアセットの変更時刻を取得または設定します。 |
| child_doc_id | string | r/w | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データソースにおける子ドキュメント識別子を取得または設定します。 |
| comp_id | int | r/w | 子ドキュメントに対して現在選択されているコンプの ID を取得または設定します。選択されていない場合は -1 になります。<br/>            コンプはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe® Photoshop® ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。<br/>            レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、<br/>            このプロパティはスマートオブジェクト用のレイヤーコンプ選択識別子を取得します。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">スマートオブジェクトにおけるレイヤーコンプ</see> |
| file_creator | string | r/w | PSD 形式の LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。 |
| file_type | string | r/w | Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。 |
| has_file_open_descriptor | bool | r/w | このリンクデータソースにファイルオープンディスクリプタ（CompId と OriginalCompId）があるかどうかを示す値を取得または設定します。 |
| is_library_link | bool | r | この PSD リンクデータソースが Adobe® Photoshop® СС Library アイテムにリンクしているかどうかを示す値を取得します。 |
| 長さを取得または設定します。 | long | r | リンク データ ソースの長さ（バイト単位）を取得します。 |
| original_comp_id | int | r | 現在選択されている子ドキュメントの Comp の元の ID を取得します。選択されていない場合は -1 になります。<br/>            このプロパティは Smart Objects の元のレイヤー Comp 選択識別子を取得します。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Smart Objects のレイヤー Comp</see> |
| original_file_name | string | r | Adobe® Photoshop® グローバルリンクリソース内のデータ ソースの元のファイル名を取得します。 |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Adobe® Photoshop® グローバルリンクデータ ソースのタイプを取得します。以下のいずれか、またはなしになる可能性があります：<br/>            PSD Lnk2Resource に対応する埋め込みリンクファイル liFD<br/>            PSD LnkeResource に対応する外部リンクファイル liFE<br/>            リンクファイルエイリアス liFA |
| unique_id | Guid | r | PSD リンクリソース内のデータ ソースのグローバル一意識別子を取得します。 |
| version | int | r | PSD LnkE / Lnk2 リソース内のデータ ソースのバージョンを取得します。 |


