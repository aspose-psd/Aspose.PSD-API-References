---
title: License.SetLicense
second_title: Aspose.PSD for .NET API リファレンス
description: License 方法. コンポーネントのライセンスを取得します
type: docs
weight: 20
url: /ja/net/aspose.psd/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

コンポーネントのライセンスを取得します。

```csharp
public void SetLicense(string licenseName)
```

### 備考

次の場所でライセンスを見つけようとします。

1. 明示的なパス。

2. Aspose コンポーネント アセンブリを含むフォルダー。

3. クライアントの呼び出しアセンブリを含むフォルダー。

4. エントリ (スタートアップ) アセンブリを含むフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**ノート：**.NET Compact Framework では、次の場所でのみライセンスを見つけようとします。

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

### 例

この例では、 コンポーネントを含むフォルダー、呼び出しアセンブリを含むフォルダー、エントリ アセンブリのフォルダー内の 、そして次に呼び出し元アセンブリの埋め込みリソース. 完全なファイル名または短いファイル名、または埋め込みリソースの名前を指定できます。 評価モードに切り替えるには、空の文字列を使用します。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### 関連項目

* class [License](../)
* 名前空間 [Aspose.PSD](../../license/)
* 組み立て [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントのライセンスを取得します。

```csharp
public void SetLicense(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ライセンスを含むストリーム。 |

### 備考

このメソッドを使用して、ストリームからライセンスをロードします。

### 例

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
* 名前空間 [Aspose.PSD](../../license/)
* 組み立て [Aspose.PSD](../../../)


