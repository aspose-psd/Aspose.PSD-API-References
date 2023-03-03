---
title: Class Lnk3Resource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk3Resource クラス. PSD 形式の埋め込みファイルに関する情報を含むクラスを定義します32 ビット/チャネルの画像です リンク リソースには複数のLiFdDataSourceindexer. によってアクセスできるインスタンス
type: docs
weight: 2730
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---
## Lnk3Resource class

PSD 形式の埋め込みファイルに関する情報を含むクラスを定義します。32 ビット/チャネルの画像です。 リンク リソースには複数の[`LiFdDataSource`](../lifddatasource/)indexer. によってアクセスできるインスタンス

```csharp
public class Lnk3Resource : Lnk2Resource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Lnk3Resource](lnk3resource/)() | の新しいインスタンスを初期化します`Lnk3Resource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | インデクサーがアクセスできるリンク データ ソースの数を取得します。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | このリンク リソース インスタンスが空かどうかを示す値を取得します。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | を取得します[`LiFdDataSource`](../lifddatasource/)指定されたインデックスで. (2 indexers) |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD グローバル リンク リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | PSD 形式のバージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | PSD グローバル リンク リソース署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | リソースブロックデータを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/typetoolkey/) | タイプ ツール情報キー。 |

### 例

この例では、Lnk2Resource および Lnk3Resource のプロパティを取得および設定する方法を示します。

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

object[] Lnk2ResourceSupportCases = new object[]
{
new object[]
{
    "00af34a0-a90b-674d-a821-73ee508c5479",
    "rgb8_2x2.png",
    "png",
    string.Empty,
    0x53,
    0d,
    string.Empty,
    7,
    true,
    0x124L,
    0x74cL
}
};

object[] LayeredLnk2ResourceSupportCases = new object[]
{
new object[]
{
    "69ac1c0d-1b74-fd49-9c7e-34a7aa6299ef",
    "huset.jpg",
    "JPEG",
    string.Empty,
    0x9d46,
    0d,
    "xmp.did:0F94B342065B11E395B1FD506DED6B07",
    7,
    true,
    0x9E60L,
    0xc60cL
},
new object[]
{
    "5a7d1965-0eae-b24e-a82f-98c7646424c2",
    "panama-papers.jpg",
    "JPEG",
    string.Empty,
    0xF56B,
    0d,
    "xmp.did:BDE940CBF51B11E59D759CDA690663E3",
    7,
    true,
    0xF694L,
    0x10dd4L
},
};

object[] LayeredLnk3ResourceSupportCases = new object[]
{
new object[]
{
    "2fd7ba52-0221-de4c-bdc4-1210580c6caa",
    "panama-papers.jpg",
    "JPEG",
    string.Empty,
    0xF56B,
    0d,
    "xmp.did:BDE940CBF51B11E59D759CDA690663E3",
    7,
    true,
    0xF694l,
    0x10dd4L
},
new object[]
{
    "372d52eb-5825-8743-81a7-b6f32d51323d",
    "huset.jpg",
    "JPEG",
    string.Empty,
    0x9d46,
    0d,
    "xmp.did:0F94B342065B11E395B1FD506DED6B07",
    7,
    true,
    0x9E60L,
    0xc60cL
},
};

var basePath = "" + Path.DirectorySeparatorChar;
string Output = "output" + Path.DirectorySeparatorChar;

// PSD ファイル内のスマート オブジェクトのデータをファイルに保存します。
void SaveSmartObjectData(string prefix, string fileName, byte[] data)
{
    var filePath = basePath + prefix + "_" + fileName;

    using (var container = FileStreamContainer.CreateFileStream(filePath, false))
    {
        container.Write(data);
    }
}

// スマート オブジェクトの新しいデータを PSD ファイルにロードします。
byte[] LoadNewData(string fileName)
{
    using (var container = FileStreamContainer.OpenFileStream(basePath + fileName))
    {
        return container.ToBytes();
    }
}

// PSD Lnk2 / Lnk3 リソースのプロパティと、PSD 画像内のその liFD データ ソースのプロパティを取得および設定します
void ExampleOfLnk2ResourceSupport(
    string fileName,
    int dataSourceCount,
    int length,
    int newLength,
    object[] dataSourceExpectedValues)
{
    using (PsdImage image = (PsdImage)Image.Load(basePath + fileName))
    {
        Lnk2Resource lnk2Resource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnk2Resource = resource as Lnk2Resource;
            if (lnk2Resource != null)
            {
                AssertAreEqual(lnk2Resource.DataSourceCount, dataSourceCount);
                AssertAreEqual(lnk2Resource.Length, length);
                AssertAreEqual(lnk2Resource.IsEmpty, false);

                for (int i = 0; i < lnk2Resource.DataSourceCount; i++)
                {
                    LiFdDataSource lifdSource = lnk2Resource[i];
                    object[] expected = (object[])dataSourceExpectedValues[i];
                    AssertAreEqual(LinkDataSourceType.liFD, lifdSource.Type);
                    AssertAreEqual(new Guid((string)expected[0]), lifdSource.UniqueId);
                    AssertAreEqual(expected[1], lifdSource.OriginalFileName);
                    AssertAreEqual(expected[2], lifdSource.FileType.TrimEnd(' '));
                    AssertAreEqual(expected[3], lifdSource.FileCreator.TrimEnd(' '));
                    AssertAreEqual(expected[4], lifdSource.Data.Length);
                    AssertAreEqual(expected[5], lifdSource.AssetModTime);
                    AssertAreEqual(expected[6], lifdSource.ChildDocId);
                    AssertAreEqual(expected[7], lifdSource.Version);
                    AssertAreEqual((bool)expected[8], lifdSource.HasFileOpenDescriptor);
                    AssertAreEqual(expected[9], lifdSource.Length);

                    if (lifdSource.HasFileOpenDescriptor)
                    {
                        AssertAreEqual(-1, lifdSource.CompId);
                        AssertAreEqual(-1, lifdSource.OriginalCompId);
                        lifdSource.CompId = int.MaxValue;
                    }

                    SaveSmartObjectData(
                        Output + fileName,
                        lifdSource.OriginalFileName,
                        lifdSource.Data);
                    lifdSource.Data = LoadNewData("new_" + lifdSource.OriginalFileName);
                    AssertAreEqual(expected[10], lifdSource.Length);

                    lifdSource.ChildDocId = Guid.NewGuid().ToString();
                    lifdSource.AssetModTime = double.MaxValue;
                    lifdSource.FileType = "test";
                    lifdSource.FileCreator = "me";
                }

                AssertAreEqual(newLength, lnk2Resource.Length);
                break;
            }
        }

        AssertAreEqual(true, lnk2Resource != null);
        if (image.BitsPerChannel < 32) // チャンネルあたり 32 ビットの保存はまだサポートされていません
        {
            image.Save(basePath + Output + fileName, new PsdOptions(image));
        }
    }
}

// この例では、チャンネルあたり 8 ビットの PSD Lnk2 リソースとその liFD データ ソースのプロパティを取得および設定する方法を示します。
ExampleOfLnk2ResourceSupport("rgb8_2x2_embedded_png.psd", 1, 0x12C, 0x0000079c, Lnk2ResourceSupportCases);

// この例では、チャンネルごとに 32 ビットの PSD Lnk3 リソースとその liFD データ ソースのプロパティを取得および設定する方法を示します。
ExampleOfLnk2ResourceSupport("Layered PSD file smart objects.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk3ResourceSupportCases);

// この例では、チャンネルごとに 16 ビットの PSD Lnk2 リソースとその liFD データ ソースのプロパティを取得および設定する方法を示します。
ExampleOfLnk2ResourceSupport("LayeredSmartObjects16bit.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk2ResourceSupportCases);
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* class [Lnk2Resource](../lnk2resource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


