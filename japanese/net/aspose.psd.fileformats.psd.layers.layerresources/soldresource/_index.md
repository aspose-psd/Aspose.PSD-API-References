---
title: Class SoLdResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource クラス. PSD ファイル内のスマート オブジェクト レイヤーに関する情報を含む SoLdResource クラスを定義します Adobe Photoshop 画像内のスマート オブジェクト レイヤーをサポートするために使用されます
type: docs
weight: 3020
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

PSD ファイル内のスマート オブジェクト レイヤーに関する情報を含む SoLdResource クラスを定義します。 Adobe® Photoshop® 画像内のスマート オブジェクト レイヤーをサポートするために使用されます。

```csharp
public class SoLdResource : SmartObjectResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | の新しいインスタンスを初期化します`SoLdResource`class. このデフォルト コンストラクタは、SoLdResourceLoader . 使用[`SmartResourceCreator`](../smartresourcecreator/)SoLdResource クラスの作成用. |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | の新しいインスタンスを初期化します`SoLdResource` class. 準備が整ったインスタンスを取得するには、Items プロパティを設定するか、InitializeItems() を呼び出す必要があります。 このコンストラクターは、[`SmartResourceCreator`](../smartresourcecreator/) および単体テストで. 使用[`SmartResourceCreator`](../smartresourcecreator/)SoLdResource クラスの作成用. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | PSD 画像のスマート オブジェクト レイヤー データのアンチ エイリアス ポリシーを取得または設定します。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | PSD 画像に配置されたレイヤーの下部の位置を取得または設定します。 |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | PSD ファイルに配置されたレイヤーの境界を取得または設定します。 |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データの comp 値を取得または設定します。 [スマートオブジェクトのレイヤーカンプ](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | 子ドキュメントの現在選択されているコンプの ID を取得または設定します。何も選択されていない場合は -1 になります。 コンプは、デザイナーが作成できるページ レイアウトのコンポジションです。レイヤーカンプを使用すると、1 つの Adobe® Photoshop® ファイルでレイアウトの複数のバージョン を作成、管理、および表示できます。レイヤーカンプは、レイヤーパネルの状態のスナップショットです。レイヤー構成は 3 種類のレイヤー オプションを保存しますが、 このプロパティは、PSD ファイル内のスマート オブジェクト レイヤーのレイヤー構成選択識別子を取得します. [スマートオブジェクトのレイヤーカンプ](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | PSD 画像のスマート オブジェクト レイヤー データのクロップを取得または設定します。 |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | 継続時間の分母を取得または設定します。 |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | 期間の分子を取得または設定します。 |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データのフレーム カウントを取得または設定します。 |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | フレーム ステップの分母を取得または設定します。 |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | フレーム ステップ分子を取得または設定します。 |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | 高さを取得または設定します。 |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | PSD ファイルに配置されたレイヤーの水平メッシュ ポイントを取得または設定します。 |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | 水平メッシュ ポイントの計測単位を取得または設定します。 |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | このインスタンス ワープ スタイルがカスタムかどうかを示す値を取得または設定します。 true の場合、メッシュ ポイントが含まれます。 false に設定すると、メッシュ ポイントが消去されます。 |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データの記述子項目を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key/) { get; } | SoLd スマート オブジェクト レイヤー リソース キーを取得します。 |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | PSD ファイルに配置されたレイヤーの左の位置を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | スマート オブジェクト リソースの長さをバイト単位で取得します。 |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データの非アフィン変換行列を取得または設定します。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | 子ドキュメントの現在選択されている Comp の元の ID を取得します。何も選択されていない場合は -1 になります。 このプロパティは、PSD ファイル内のスマート オブジェクト レイヤーの元のレイヤー Comp 選択識別子を取得します。 [スマートオブジェクトのレイヤーカンプ](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データのページ番号を取得または設定します。 |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | PSD ファイルに配置されたレイヤーの遠近値を取得または設定します。 |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | PSD ファイルに配置されたレイヤーのパースペクティブその他の値を取得または設定します。 |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | PSD 画像内のこのスマート オブジェクト レイヤー データの一意の識別子を取得または設定します。 |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データのタイプを取得または設定します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion/) { get; } | スマート オブジェクト リソースに必要な最小限の psd バージョンを取得します。 0 は制限なしを示します。 |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | PSD ファイルのスマート オブジェクト レイヤー データの解像度を取得または設定します。 |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データの解像度測定単位を取得または設定します。 |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | PSD ファイルに配置されたレイヤーの正しい位置を取得または設定します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature/) { get; } | スマート オブジェクト リソースの署名を取得します。 |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | PSD 画像に配置されたレイヤーの最上部の位置を取得または設定します。 |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データの総ページ数を取得または設定します。 |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | PSD ファイル内のスマート オブジェクト レイヤー データの変換行列を取得または設定します。 |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | スマート オブジェクト レイヤー データのグローバル一意識別子を取得または設定します[`SmartObjectResource`](../smartobjectresource/)PSD 画像で. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | PSD ファイルに配置されたレイヤーの U オーダー値を取得または設定します。 |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | PSD 画像に配置されたレイヤーのワープ値を取得または設定します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | PSD ファイルに配置されたレイヤーのバージョンを取得します。通常は 3. です。 |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | PSD ファイルに配置されたレイヤーの水平メッシュ ポイントを取得または設定します。 |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | 垂直メッシュ ポイントの測定単位を取得または設定します。 |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | PSD ファイルに配置されたレイヤーの V オーダー値を取得または設定します。 |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | 幅を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | スマート オブジェクト リソースを指定されたストリーム コンテナーに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | タイプ ツール情報キー: 'SoLd'. |

### 例

次のコードは、SoLdResource リソースのサポートを示しています。

```csharp
[C#]

// この例では、PSD ファイルのスマート オブジェクト レイヤー データ プロパティを取得または設定する方法を示します。

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
var outputFilePath = "LayeredSmartObjects8bit2_output.psd";
var expectedValues = new object[]
{
    new object[]
    {
        true,
        "76f05a3b-7523-5e42-a1bb-27f4735bffa0",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        310d,
        149d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "d3388655-19e4-9742-82f2-f553bb01046a",
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 0.0d, 0.0d, 0.0d,
            49.666666666666664d, 49.666666666666664d, 49.666666666666664d, 49.666666666666664d,
            99.333333333333329d, 99.333333333333329d, 99.333333333333329d, 99.333333333333329d,
            149, 149, 149, 149,
        },
    },
    new object[]
    {
        true,
        "cf0477a8-8f92-ac4f-9462-f78e26234851",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        1280d,
        721d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "625cc4b9-2c5f-344f-8636-03caf2bd3489",
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 0.0, 0.0, 0.0,
            240.33333333333331, 240.33333333333331, 240.33333333333331, 240.33333333333331,
            480.66666666666663, 480.66666666666663, 480.66666666666663, 480.66666666666663,
            721, 721, 721, 721,
        },
        0,
        0
    }
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as SoLdResource;
            if (resource != null)
            {
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[0], resource.IsCustom);
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                AssertAreEqual(expectedValue[2], resource.PageNumber);
                AssertAreEqual(expectedValue[3], resource.TotalPages);
                AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
                AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
                AssertAreEqual(8, resource.TransformMatrix.Length);
                AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
                AssertAreEqual(expectedValue[7], resource.Value);
                AssertAreEqual(expectedValue[8], resource.Perspective);
                AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
                AssertAreEqual(expectedValue[10], resource.Top);
                AssertAreEqual(expectedValue[11], resource.Left);
                AssertAreEqual(expectedValue[12], resource.Bottom);
                AssertAreEqual(expectedValue[13], resource.Right);
                AssertAreEqual(expectedValue[14], resource.UOrder);
                AssertAreEqual(expectedValue[15], resource.VOrder);

                AssertAreEqual(expectedValue[16], resource.Crop);
                AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
                AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
                AssertAreEqual(expectedValue[19], resource.DurationNumerator);
                AssertAreEqual(expectedValue[20], resource.DurationDenominator);
                AssertAreEqual(expectedValue[21], resource.FrameCount);
                AssertAreEqual(expectedValue[22], resource.Width);
                AssertAreEqual(expectedValue[23], resource.Height);
                AssertAreEqual(expectedValue[24], resource.Resolution);
                AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
                AssertAreEqual(expectedValue[26], resource.Comp);
                AssertAreEqual(expectedValue[27], resource.CompId);
                AssertAreEqual(expectedValue[28], resource.OriginalCompId);
                AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
                AssertAreEqual((IEnumerable)expectedValue[30], resource.NonAffineTransformMatrix);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }

                // この値は、PlLdResource でも (UniqueId を指定して) 変更する必要があります
                // そして、それらのいくつかは、LinkDataSource の下にあるスマート オブジェクトと一致している必要があります
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 0;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;
                resource.Crop = 4;
                resource.FrameStepNumerator = 1;
                resource.FrameStepDenominator = 601;
                resource.DurationNumerator = 2;
                resource.DurationDenominator = 602;
                resource.FrameCount = 11;
                resource.Width = 541;
                resource.Height = 249;
                resource.Resolution = 144;
                resource.Comp = 21;
                resource.CompId = 22;
                resource.TransformMatrix = new double[8]
                {
                    12.937922786050663,
                    19.419959734187131,
                    2.85445817782261,
                    1.0540625423957124,
                    7.20861031651307,
                    14.634102808208553,
                    17.292074924741144,
                    4
                };
                resource.NonAffineTransformMatrix = new double[8]
                {
                    129.937922786050663,
                    195.419959734187131,
                    26.85445817782261,
                    12.0540625423957124,
                    72.20861031651307,
                    147.634102808208553,
                    175.292074924741144,
                    42
                };

                // この一意の ID は、参照があれば変更する必要があります
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // 一部のパラメータには注意してください: 画像は Adobe® Photoshop® で読み取れなくなる可能性があります
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // これを変更しないでください。そうしないと、自由な変換を使用できなくなります
                // または、下線付きのスマート オブジェクトをベクター型に変更します
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // この一意の ID を持つ有効な PlLdResource が存在する必要があります
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### 関連項目

* class [SmartObjectResource](../smartobjectresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


