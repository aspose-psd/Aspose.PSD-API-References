---
title: "Image.GetFileFormat"
second_title: "Aspose.PSD for .NET API Reference"
description: "Image メソッド。ファイル形式を取得します。"
type: docs
weight: 270
url: /ja/net/aspose.psd/image/getfileformat/
---
{{< psd/tize >}}
## GetFileFormat(string) {#getfileformat_1}

ファイル形式を取得します。

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルパス。 |

### 戻り値

決定されたファイル形式です。

## 備考

決定されたファイル形式は、指定された画像がロードできることを意味しません。ファイルがロード可能かどうかを判断するには、CanLoad メソッドのオーバーロードのいずれかを使用してください。

### 関連項目

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

ファイル形式を取得します。

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ストリームです。 |

### 戻り値

決定されたファイル形式です。

## 備考

決定されたファイル形式は、指定された画像がロードできることを意味しません。ストリームがロード可能かどうかを判断するには、CanLoad メソッドのオーバーロードのいずれかを使用してください。

### 関連項目

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


