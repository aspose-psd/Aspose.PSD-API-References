---
title: "クラス NameStructure"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure クラス。Name 構造キー 0x6E616D65 は、ASCII で 'name' と綴られ、レイヤーパスや調整などの要素の名前を表す Unicode または Pascal 形式の文字列を格納するために使用されるシンプルな構造です。"
type: docs
weight: 3580
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/
---
{{< psd/tize >}}
## NameStructure class

Name 構造 (キー: 0x6E616D65、ASCII で "name" と綴られます) は、レイヤー、パス、または調整などの要素の名前を表す Unicode または Pascal 形式の文字列を格納するために使用されるシンプルな構造です。

```csharp
public sealed class NameStructure : OSTypeStructure
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [NameStructure](namestructure/)(ClassID) | `NameStructure` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/key/) { get; } | キーを取得します。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | キー名を取得または設定します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/length/) { get; } | バイト単位で[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) の長さを取得します。 |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/value/) { get; set; } | Name 構造体の値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | ヘッダーの長さを取得します。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 構造体を指定されたストリーム コンテナに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/structurekey/) | Name 構造キーです。 |

## 例

以下のコードは NameStructure のサポートを示しています。

```csharp
[C#]

string inputFile = "Mixer_ipad_Hand_W_crash.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(inputFile, new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    //// ファイルが正常に読み込まれました

    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);

    // テストファイルを変更せずに保存します
    psdImage.Save(outputFile);

    //// ファイルは PS でエラーなく開くべきです
}

// ライティング効果の構造が正しく保存されていることを確認します
using (var psdImage = (PsdImage)Image.Load(
           outputFile,
           new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### 関連項目

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


