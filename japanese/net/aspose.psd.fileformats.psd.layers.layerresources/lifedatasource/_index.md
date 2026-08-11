---
title: "クラス LiFeDataSource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFeDataSource クラス。外部リンクファイルに関する情報を含む LnkeDataSource クラスを定義します。これは Adobe Photoshop ファイルの変更を支援する PSD ファイルフォーマット操作 API の一部です。"
type: docs
weight: 2980
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---
{{< psd/tize >}}
## LiFeDataSource class

外部リンクファイルに関する情報を含む LnkeDataSource クラスを定義します。これは、Adobe® Photoshop® ファイルの変更を支援する PSD ファイル形式操作 API の一部です。

```csharp
public class LiFeDataSource : LinkDataSource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LiFeDataSource](lifedatasource/#constructor)() | `LiFeDataSource` クラスの新しいインスタンスを初期化します。 |
| [LiFeDataSource](lifedatasource/#constructor_1)(int, Guid, string, string, string) | `LiFeDataSource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdobeStockId](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/adobestockid/) { get; set; } | Adobe® Photoshop® CC ライブラリ用のグラフィックライブラリ AdobeStockId を取得または設定します。 |
| [AdobeStockLicenseState](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/adobestocklicensestate/) { get; } | 利用可能な場合、Adobe® Photoshop® CC ライブラリ用の Adobe Stock ライセンスの状態を取得します。 |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD アセットがロックされているかどうかを示す値を取得または設定します。Adobe® Photoshop® СС ライブラリ資産のロック状態です。 |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС ライブラリ資産の変更日時を取得または設定します。 |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データソース内の子ドキュメント識別子を取得または設定します。 |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | 取得または設定します 現在選択されている子ドキュメントのコンプの ID を取得または設定します。選択されていない場合は -1 になります。コンプはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe® Photoshop® ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、このプロパティはスマートオブジェクト用のレイヤーコンプ選択識別子を取得します。 [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Date](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/date/) { get; set; } | 取得または設定します PSD LnkE リソースの LiFE データソースにある外部ファイルの最終書き込み日時を取得または設定します。 |
| [ElementName](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/elementname/) { get; set; } | 取得または設定します Adobe® Photoshop® CC Libraries 用のグラフィックライブラリ要素名を取得または設定します。 |
| [ElementRef](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/elementref/) { get; set; } | 取得または設定します Adobe® Photoshop® CC Libraries 用のグラフィックライブラリ要素参照を取得または設定します。 |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | 取得または設定します PSD フォーマットの LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。 |
| [FileName](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/filename/) { get; set; } | 取得または設定します PSD リンクリソース内の外部または埋め込みファイルの名前を取得または設定します。 |
| [FileSize](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/filesize/) { get; set; } | 取得または設定します PSD LnkE リソースの LiFE データソースにある外部ファイルのサイズを取得または設定します。 |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | 取得または設定します Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。 |
| [FullPath](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) { get; set; } | 取得または設定します PSD LnkE リソースの LiFE データソースにある外部ファイルのフルパスを取得または設定します。 |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | 取得または設定します このリンクデータソースがファイルオープン記述子（CompId と OriginalCompId）を持つかどうかを示す値を取得または設定します。 |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | 取得します この PSD リンクデータソースが Adobe® Photoshop® СС Library アイテムにリンクしているかどうかを示す値を取得します。 |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | 取得します リンクデータソースの長さ（バイト単位）を取得します。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | 取得します 子ドキュメントの現在選択されているコンプの元の ID を取得します。選択されていない場合は -1 になります。このプロパティはスマートオブジェクト用の元のレイヤーコンプ選択識別子を取得します。 [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | 取得します Adobe® Photoshop® グローバルリンクリソース内のデータソースの元のファイル名を取得します。 |
| [RelativePath](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) { get; set; } | 取得または設定します PSD LnkE リソースの LiFE データソースにある外部ファイルの相対パスを取得または設定します。 |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | 取得します Adobe® Photoshop® グローバルリンクデータソースのタイプを取得します。以下のいずれか、またはなしです：PSD Lnk2Resource に対応する埋め込みリンクファイル liFD、PSD LnkeResource に対応する外部リンクファイル liFE、リンクファイルエイリアス liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | 取得します PSD リンクリソース内のデータソースのグローバル一意識別子を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | 取得します PSD LnkE / Lnk2 リソース内のデータソースのバージョンを取得します。 |

## 例

この例は Psd LnkE リソースのプロパティを取得および設定する方法を示します。

```csharp
[C#]

string message = "The example works incorrectly.";
void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(message);
    }
}

// この例は外部リンクファイルに関する情報を含む Psd LnkE リソースのプロパティを取得および設定する方法を示します。
void ExampleOfLnkEResourceSupport(
    string fileName,
    int length,
    int length2,
    int length3,
    int length4,
    string fullPath,
    string date,
    double assetModTime,
    string childDocId,
    bool locked,
    string uid,
    string name,
    string originalFileName,
    string fileType,
    long size,
    int version)
{
    string outputPath = fileName;
    using (PsdImage image = (PsdImage)Image.Load(fileName))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                LiFeDataSource lifeSource = lnkeResource[0];
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lifeSource.UniqueId, new Guid(uid));
                AssertAreEqual(lifeSource.FullPath, fullPath);
                AssertAreEqual(lifeSource.Date.ToString(CultureInfo.InvariantCulture), date);
                AssertAreEqual(lifeSource.AssetModTime, assetModTime);
                AssertAreEqual(lifeSource.FileName, name);
                AssertAreEqual(lifeSource.FileSize, size);
                AssertAreEqual(lifeSource.ChildDocId, childDocId);
                AssertAreEqual(lifeSource.Version, version);
                AssertAreEqual(lifeSource.FileType.TrimEnd(' '), fileType);
                AssertAreEqual(lifeSource.FileCreator.TrimEnd(' '), string.Empty);
                AssertAreEqual(lifeSource.OriginalFileName, originalFileName);
                AssertAreEqual(false, lnkeResource.IsEmpty);
                AssertAreEqual(true, lifeSource.Type == LinkDataSourceType.liFE);
                if (version == 7)
                {
                    AssertAreEqual(lifeSource.AssetLockedState, locked);
                }

                if (lifeSource.HasFileOpenDescriptor)
                {
                    AssertAreEqual(lifeSource.CompId, -1);
                    AssertAreEqual(lifeSource.OriginalCompId, -1);
                }

                lifeSource.FullPath =
                    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                AssertAreEqual(lnkeResource.Length, length2);
                lifeSource.FileName = "rgb8_2x23.png";
                AssertAreEqual(lnkeResource.Length, length3);
                lifeSource.ChildDocId = Guid.NewGuid().ToString();
                AssertAreEqual(lnkeResource.Length, length4);
                lifeSource.Date = DateTime.Now;
                lifeSource.AssetModTime = double.MaxValue;
                lifeSource.FileSize = long.MaxValue;
                lifeSource.FileType = "test";
                lifeSource.FileCreator = "file";
                lifeSource.CompId = int.MaxValue;
                break;
            }
        }

        AssertAreEqual(true, lnkeResource != null);

        image.Save(outputPath, new PsdOptions(image));
    }
}

// この例は外部リンク JPEG ファイルに関する情報を含む Psd LnkeResource のプロパティを取得および設定する方法を示します。
ExampleOfLnkEResourceSupport(
    @"photooverlay_5_new.psd",
    0x21c,
    0x26c,
    0x274,
    0x27c,
    @"file:///C:/Users/cvallejo/Desktop/photo.jpg",
    "05/09/2017 22:24:51",
    0,
    "F062B9DB73E8D124167A4186E54664B0",
    false,
    "02df245c-36a2-11e7-a9d8-fdb2b61f07a7",
    "photo.jpg",
    "photo.jpg",
    "JPEG",
    0x1520d,
    7);

// この例は外部リンク PNG ファイルに関する情報を含む PSD LnkeResource のプロパティを取得および設定する方法を示します。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked.psd",
    0x284,
    0x290,
    0x294,
    0x2dc,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Issues/PSDNET-491/rgb8_2x2.png",
    "04/14/2020 14:23:44",
    0,
    string.Empty,
    false,
    "5867318f-3174-9f41-abca-22f56a75247e",
    "rgb8_2x2.png",
    "rgb8_2x2.png",
    "png",
    0x53,
    7);

// この例は外部リンク PNG と PSD の 2 つのファイルに関する情報を含む PSD LnkeResource のプロパティを取得および設定する方法を示します。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked2.psd",
    0x590,
    0x580,
    0x554,
    0x528,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/AddColorBalanceAdjustmentLayer.psd",
    "01/15/2020 13:02:00",
    0,
    "adobe:docid:photoshop:9312f484-3403-a644-8973-e725abc95fb7",
    false,
    "78a5b588-364f-0940-a2e5-a450a031aa48",
    "AddColorBalanceAdjustmentLayer.psd",
    "AddColorBalanceAdjustmentLayer.psd",
    "8BPS",
    0x4aea,
    7);

// この例は外部リンク CC Libraries アセットに関する情報を含む Photoshop Psd LnkeResource のプロパティを取得および設定する方法を示します。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_asset_linked.psd",
    0x398,
    0x38c,
    0x388,
    0x3d0,
    @"CC Libraries Asset “rgb8_2x2_linked/rgb8_2x2” (Feature is available in Photoshop CC 2015)",
    "01/01/0001 00:00:00",
    1588890915488.0d,
    string.Empty,
    false,
    "ec15f0a8-7f13-a640-b928-7d29c6e9859c",
    "rgb8_2x2_linked",
    "rgb8_2x2.png",
    "png",
    0,
    7);
```

以下のコードは LnkeResource リソースのサポートを示しています。

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

object[] ComplexLnkEResourceSupportCases = new object[]
{
    new object[]
    {
        "10fc87d0-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/or hdr btns” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633541.0d,
        "uuid:8485ca8d-9496-7f4d-9ef7-4243a00d4161",
        "OneReview-InDesign-InContextTranslation",
        "or hdr btns.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
    new object[]
    {
        "10fc87cc-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs Id icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633512.0d,
        "uuid:c18be832-adf7-4b43-8223-a9740807a66c",
        "OneReview-InDesign-InContextTranslation",
        "cs Id icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fef79c-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/pointer cursor” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633570.0d,
        "uuid:9d7ccaac-f094-214b-8721-1a07ae8700a9",
        "OneReview-InDesign-InContextTranslation",
        "pointer cursor.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x03c0
    },
    new object[]
    {
        "10fef79a-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/x” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633555.0d,
        "uuid:b28aa699-21d6-2d4d-a4c7-790234c1b6ba",
        "OneReview-InDesign-InContextTranslation",
        "x.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x38c
    },
    new object[]
    {
        "10fef79b-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/modal btns” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633562.0d,
        "uuid:1bd42767-058d-da44-bdee-eada3b9d40a5",
        "OneReview-InDesign-InContextTranslation",
        "modal btns.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fc87cd-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs ppt icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633519.0d,
        "uuid:215499ac-ac44-b44d-894b-9ff2c7008d9d",
        "OneReview-InDesign-InContextTranslation",
        "cs ppt icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
    new object[]
    {
        "10fc87cf-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs AI icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633534.0d,
        "uuid:a67964d4-8682-d649-8118-474cb1776264",
        "OneReview-InDesign-InContextTranslation",
        "cs AI icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fc87ce-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs PSD icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633527.0d,
        "uuid:8e9d5745-9f23-6f49-968e-647a45811bcb",
        "OneReview-InDesign-InContextTranslation",
        "cs PSD icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
};

void ExampleOfComplexLnkEResourceSupport(string filePath, int length, int length2, object[] dataSourceExpectedValues)
{
    filePath = "PSDNET652_1" + Path.DirectorySeparatorChar + filePath;
    string fileName = Path.GetFileName(filePath);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                AssertAreEqual(lnkeResource.DataSourceCount, 8);
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lnkeResource.IsEmpty, false);

                for (int i = 0; i < lnkeResource.DataSourceCount; i++)
                {
                    LiFeDataSource liFeSource = lnkeResource[i];
                    object[] expected = (object[])dataSourceExpectedValues[i];
                    AssertAreEqual(liFeSource.Type, LinkDataSourceType.liFE);
                    AssertAreEqual(liFeSource.UniqueId, new Guid((string)expected[0]));
                    AssertAreEqual(liFeSource.FullPath, expected[1]);
                    AssertAreEqual(liFeSource.Date.ToString(CultureInfo.InvariantCulture), expected[2]);
                    AssertAreEqual(liFeSource.AssetModTime, expected[3]);
                    AssertAreEqual(liFeSource.ChildDocId, expected[4]);
                    AssertAreEqual(liFeSource.FileName, expected[5]);
                    AssertAreEqual(liFeSource.OriginalFileName, expected[6]);
                    AssertAreEqual(liFeSource.FileSize, expected[7]);
                    AssertAreEqual(liFeSource.FileType, expected[8]);
                    AssertAreEqual(liFeSource.FileCreator.TrimEnd(' '), string.Empty);
                    AssertAreEqual(liFeSource.Version, expected[9]);
                    AssertAreEqual(liFeSource.AdobeStockLicenseState, expected[10]);
                    AssertAreEqual(liFeSource.HasFileOpenDescriptor, (bool)expected[11]);

                    if (liFeSource.HasFileOpenDescriptor)
                    {
                        AssertAreEqual(liFeSource.CompId, -1);
                        AssertAreEqual(liFeSource.OriginalCompId, -1);
                        liFeSource.CompId = int.MaxValue;
                    }

                    liFeSource.FullPath = @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                    liFeSource.FileName = "rgb8_2x23.png";
                    liFeSource.ChildDocId = Guid.NewGuid().ToString();
                    liFeSource.Date = DateTime.Now;
                    liFeSource.AssetModTime = double.MaxValue;
                    liFeSource.FileSize = long.MaxValue;
                    liFeSource.FileType = "test";
                    liFeSource.FileCreator = "file";
                    AssertAreEqual((int)liFeSource.Length, expected[12]);
                }

                AssertAreEqual(lnkeResource.Length, length2);
                break;
            }
        }

        AssertIsTrue(lnkeResource != null);
    }
}

ExampleOfComplexLnkEResourceSupport(
    "OneReview-InDesign-RefreshPreviewIxD(2).psd",
    0x21ac,
    0x1db8,
    ComplexLnkEResourceSupportCases);
```

### 関連項目

* class [LinkDataSource](../linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


