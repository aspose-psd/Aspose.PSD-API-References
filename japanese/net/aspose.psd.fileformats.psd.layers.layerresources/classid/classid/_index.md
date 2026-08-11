---
title: "ClassID.ClassID"
second_title: "Aspose.PSD for .NET API Reference"
description: "ClassID コンストラクタ。ClassID クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

[`ClassID`](../) クラスの新しいインスタンスを初期化します。

```csharp
public ClassID(byte[] classID)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| classID | Byte[] | クラスIDはバイト列として表されます。 |

### 関連項目

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

[`ClassID`](../) クラスの新しいインスタンスを初期化します。

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| classID | Byte[] | クラスIDはバイト列として表されます。 |
| isZeroLength | Boolean | `true` に設定した場合 [は長さがゼロです]。 記録された文字列の長さはゼロですが、実際は4です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | classID は null です。 |

### 関連項目

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

[`ClassID`](../) クラスの新しいインスタンスを初期化します。

```csharp
public ClassID(int classID)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| classID | Int32 | クラス IDです。 |

### 関連項目

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

[`ClassID`](../) クラスの新しいインスタンスを初期化します。

```csharp
public ClassID(uint classID)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| classID | UInt32 | クラス IDです。 |

### 関連項目

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

[`ClassID`](../) クラスの新しいインスタンスを初期化します。

```csharp
public ClassID(string classID, bool isZeroLength)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| classID | 文字列 | ASCII エンコーディングのクラス ID。 |
| isZeroLength | Boolean | `true` に設定した場合 [は長さがゼロです]。 |

## 例

この例は、画像からインポートされたレイヤーがスマートオブジェクトレイヤーに変換され、保存された PSD ファイルが正しいことを示しています。

```csharp
[C#]

// レイヤーが画像からインポートされ、スマートオブジェクトレイヤーに変換され、保存された PSD ファイルが正しいことをテストします。

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

[`ClassID`](../) クラスの新しいインスタンスを初期化します。

```csharp
public ClassID(string classID)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| classID | 文字列 | ASCII エンコーディングのクラス ID。 |

### 関連項目

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


