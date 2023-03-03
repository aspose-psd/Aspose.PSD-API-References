---
title: Class License
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.License クラス. コンポーネントのライセンスを取得する方法を提供します
type: docs
weight: 5050
url: /ja/net/aspose.psd/license/
---
## License class

コンポーネントのライセンスを取得する方法を提供します。

```csharp
public class License
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [License](license/)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | コンポーネントのライセンスを取得します。 |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | コンポーネントのライセンスを取得します。 |

### 例

この例では、 コンポーネントを含むフォルダー、呼び出しアセンブリを含むフォルダー、エントリ アセンブリのフォルダー内の 、そして次に呼び出し元アセンブリの埋め込みリソース.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


