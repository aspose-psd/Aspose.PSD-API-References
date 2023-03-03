---
title: Layer.Save
second_title: Aspose.PSD for .NET API リファレンス
description: Layer 方法. オブジェクトのデータを指定されたストリームに保存します
type: docs
weight: 370
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

オブジェクトのデータを指定されたストリームに保存します。

```csharp
public override void Save(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | オブジェクトのデータを保存するストリーム。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | Image オプションなしで Save メソッドを呼び出すべきではありません |

### 関連項目

* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |
| options | ImageOptionsBase | オプション。 |

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

オブジェクトのデータを指定されたファイルの場所に保存します。

```csharp
public override void Save(string filePath, bool overWrite)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | オブジェクトのデータを保存するファイル パス。 |
| overWrite | Boolean | に設定した場合`真実`ファイルの内容を上書きします。そうしないと、追加が発生します。 |

### 関連項目

* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 画像のデータを保存するストリーム。 |
| optionsBase | ImageOptionsBase | 保存オプション。 |
| boundsRectangle | Rectangle | 宛先画像の境界矩形。ソース境界を使用するための空の四角形を設定します。 |

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |
| options | ImageOptionsBase | オプション。 |
| boundsRectangle | Rectangle | 宛先画像の境界矩形。ソース境界を使用するための空の四角形を設定します。 |

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)


