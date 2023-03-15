---
title: ClassID.ClassID
second_title: Aspose.PSD for .NET API リファレンス
description: ClassID コンストラクタ. の新しいインスタンスを初期化しますClassIDclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

の新しいインスタンスを初期化します[`ClassID`](../)class.

```csharp
public ClassID(byte[] classID)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| classID | Byte[] | 一連のバイトとしてのクラス ID。 |

### 関連項目

* class [ClassID](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 組み立て [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

の新しいインスタンスを初期化します[`ClassID`](../)class.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| classID | Byte[] | 一連のバイトとしてのクラス ID。 |
| isZeroLength | Boolean | に設定した場合`真実` [長さゼロ]. 記録された文字列の長さはゼロですが、実際は 4 です. |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | クラス ID がヌルです。 |

### 関連項目

* class [ClassID](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 組み立て [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

の新しいインスタンスを初期化します[`ClassID`](../)class.

```csharp
public ClassID(int classID)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| classID | Int32 | クラス ID。 |

### 関連項目

* class [ClassID](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 組み立て [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

の新しいインスタンスを初期化します[`ClassID`](../)class.

```csharp
public ClassID(uint classID)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| classID | UInt32 | クラス ID。 |

### 関連項目

* class [ClassID](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 組み立て [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

の新しいインスタンスを初期化します[`ClassID`](../)class.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| classID | String | ASCII エンコーディングのクラス ID。 |
| isZeroLength | Boolean | に設定した場合`真実` [長さゼロです]。 |

### 例

この例は、画像からインポートされたレイヤーがスマート オブジェクト レイヤーに変換され、保存された PSD ファイルが正しいことを示しています。

```csharp
[C#]

// 画像からインポートされたレイヤーがスマート オブジェクト レイヤーに変換され、保存された PSD ファイルが正しいことをテストします。

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 関連項目

* class [ClassID](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 組み立て [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

の新しいインスタンスを初期化します[`ClassID`](../)class.

```csharp
public ClassID(string classID)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| classID | String | ASCII エンコーディングのクラス ID。 |

### 関連項目

* class [ClassID](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 組み立て [Aspose.PSD](../../../)


