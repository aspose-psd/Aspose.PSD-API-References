---
title: "列挙型 ReadOnlyMode"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode 列挙型。PSD 画像をロードする際に利用できる読み取り専用モードを指定します。"
type: docs
weight: 5260
url: /ja/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

PSD 画像をロードする際に利用可能な読み取り専用モードを指定します。

```csharp
public enum ReadOnlyMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 読み取り専用の制限は適用されません。画像は完全に変更可能です。 |
| Default | `1` | デフォルトモード。画像は完全に読み取り専用で、変更できません。 |
| MetadataEdit | `2` | 画像コンテンツは読み取り専用のまま、画像メタデータの編集を許可します。 |

## 例

ReadOnlyMode.MetadataEdit を使用して PSD メタデータの編集と保存を示します。

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // ReadOnlyMode でメタデータを変更する
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // ReadOnlyMode で変更されたメタデータを保存する
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### 関連項目

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


