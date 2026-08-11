---
title: "Layer.Save"
second_title: "Aspose.PSD for .NET API Reference"
description: "Layer メソッド。オブジェクトのデータを指定されたストリームに保存します"
type: docs
weight: 390
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

オブジェクトのデータを指定されたストリームに保存します。

```csharp
public override void Save(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | オブジェクトのデータを保存するストリームです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | Image options が指定されていない状態で Save メソッドを呼び出すべきではありません |

### 関連項目

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルパス。 |
| オプション | ImageOptionsBase | オプションです。 |

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

オブジェクトのデータを指定されたファイル位置に保存します。

```csharp
public override void Save(string filePath, bool overWrite)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | オブジェクトのデータを保存するためのファイルパス。 |
| overWrite | Boolean | `true` に設定するとファイル内容を上書きし、そうでなければ追記が行われます。 |

### 関連項目

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 画像のデータを保存するストリーム。 |
| optionsBase | ImageOptionsBase | 保存オプション。 |
| boundsRectangle | Rectangle | 対象画像の境界矩形です。空の矩形を設定するとソースの境界が使用されます。 |

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルパス。 |
| オプション | ImageOptionsBase | オプションです。 |
| boundsRectangle | Rectangle | 対象画像の境界矩形です。空の矩形を設定するとソースの境界が使用されます。 |

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


