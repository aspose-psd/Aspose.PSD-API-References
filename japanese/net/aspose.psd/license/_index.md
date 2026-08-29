---
title: "クラス License"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.License クラス。コンポーネントのライセンス付与メソッドを提供します。"
type: docs
weight: 5540
url: /ja/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

コンポーネントのライセンスを付与するメソッドを提供します。

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
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | コンポーネントにライセンスを付与します。 |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | コンポーネントにライセンスを付与します。 |

## 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


