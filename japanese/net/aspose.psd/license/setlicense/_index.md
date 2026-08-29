---
title: "License.SetLicense"
second_title: "Aspose.PSD for .NET API Reference"
description: "License メソッド。コンポーネントにライセンスを付与します。"
type: docs
weight: 20
url: /ja/net/aspose.psd/license/setlicense/
---
{{< psd/tize >}}
## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licenseName)
```

## 備考

以下の場所でライセンスを検索します:

1. 明示的なパス。

2. Aspose コンポーネント アセンブリを含むフォルダー。

3. クライアントの呼び出しアセンブリを含むフォルダー。

4. エントリ（スタートアップ）アセンブリを含むフォルダー。

5. クライアントの呼び出しアセンブリ内の埋め込みリソース。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリ内の埋め込みリソース。

## 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

完全または短いファイル名、または埋め込みリソースの名前にすることができます。空文字列を使用して評価モードに切り替えます。

### 関連項目

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ライセンスを含むストリーム。 |

## 備考

このメソッドを使用して、ストリームからライセンスをロードします。

## 例

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### 関連項目

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


