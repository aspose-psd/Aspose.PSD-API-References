---
title: "クラス Lnk3Resource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk3Resource クラス。PSD フォーマットの 32 ビット/チャンネル画像に埋め込みファイルに関する情報を含むクラスを定義します。リンクリソースはインデクサでアクセスできる複数の LiFdDataSource インスタンスを含む場合があります。"
type: docs
weight: 3040
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---
{{< psd/tize >}}
## Lnk3Resource class

PSD フォーマットの 32 ビット/チャンネル画像に埋め込みファイルに関する情報を含むクラスを定義します。リンクリソースはインデクサでアクセスできる複数の [`LiFdDataSource`](../lifddatasource/) インスタンスを含む場合があります。

```csharp
public class Lnk3Resource : Lnk2Resource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Lnk3Resource](lnk3resource/)() | `Lnk3Resource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | インデクサでアクセスできるリンクデータソースの数を取得します。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | このリンクリソースインスタンスが空かどうかを示す値を取得します。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | 指定されたインデックスの [`LiFdDataSource`](../lifddatasource/) を取得します。（インデクサ 2 つ） |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD グローバルリンクリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | リソースブロックデータを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/typetoolkey/) | タイプツール情報キーです。 |

## 例

この例は Lnk2Resource と Lnk3Resource のプロパティを取得および設定する方法を示しています。

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

// PSD ファイル内のスマートオブジェクトのデータをファイルに保存します。
void SaveSmartObjectData(string prefix, string fileName, byte[] data)
{
    var filePath = basePath + prefix + "_" + fileName;

    using (var container = FileStreamContainer.CreateFileStream(filePath, false))
    {
        container.Write(data);
    }
}

// PSD ファイル内のスマートオブジェクトの新しいデータをロードします。
byte[] LoadNewData(string fileName)
{
    using (var container = FileStreamContainer.OpenFileStream(basePath + fileName))
    {
        return container.ToBytes();
    }
}

// PSD 画像内の PSD Lnk2 / Lnk3 リソースとその liFD データソースのプロパティを取得および設定します。
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
        if (image.BitsPerChannel < 32) // 32 bit per channel saving is not supported yet
        {
            image.Save(basePath + Output + fileName, new PsdOptions(image));
        }
    }
}

// この例は 8 ビット/チャンネル用の PSD Lnk2 リソースとその liFD データソースのプロパティを取得および設定する方法を示しています。
ExampleOfLnk2ResourceSupport("rgb8_2x2_embedded_png.psd", 1, 0x12C, 0x0000079c, Lnk2ResourceSupportCases);

// この例は 32 ビット/チャンネル用の PSD Lnk3 リソースとその liFD データソースのプロパティを取得および設定する方法を示しています。
ExampleOfLnk2ResourceSupport("Layered PSD file smart objects.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk3ResourceSupportCases);

// この例は 16 ビット/チャンネル用の PSD Lnk2 リソースとその liFD データソースのプロパティを取得および設定する方法を示しています。
ExampleOfLnk2ResourceSupport("LayeredSmartObjects16bit.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk2ResourceSupportCases);
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* class [Lnk2Resource](../lnk2resource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


