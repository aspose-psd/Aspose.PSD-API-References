---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD for .NET API Reference"
description: "FileCreateSource コンストラクタ。FileCreateSource クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

[`FileCreateSource`](../) クラスの新しいインスタンスを初期化します

```csharp
public FileCreateSource(string filePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | 作成するファイルのパスです。 |

## 例

この例は、BmpOptions インスタンスの Source プロパティで指定されたディスク上の場所に新しい Image ファイルを作成します。FileCreateSource のコンストラクタに第2パラメータが渡されない場合、既定で作成されるファイルの IsTemporal プロパティは True に設定されます。IsTemporal が True に設定されている場合、実行終了時にディスクにファイルは保存されません。

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions のインスタンスを作成し、さまざまなプロパティを設定します。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource のインスタンスを作成し、PsdOptions インスタンスの Source として割り当てます。
//第2パラメータが渡されない場合、既定でファイルの IsTemporal は True に設定されます
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Image のインスタンスを作成します
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //画像処理を行います。
}
```

### 関連項目

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

[`FileCreateSource`](../) クラスの新しいインスタンスを初期化します

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | 作成するファイルのパスです。 |
| isTemporal | Boolean | `true` に設定すると、作成されたファイルは一時的になります。 |

## 例

この例では、PsdOptions インスタンスの Source プロパティで指定されたディスク上の場所に新しい Image ファイルを作成します。PsdOptions インスタンスの複数のプロパティが実際の画像を作成する前に設定されます。特に、この場合は実際のディスク位置を指す Source プロパティです。

```csharp
[C#]

//PsdOptions のインスタンスを作成し、さまざまなプロパティを設定します。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource のインスタンスを作成し、PsdOptions インスタンスの Source として割り当てます。
//2 番目の Boolean パラメーターは、作成するファイルが一時的かどうかを決定します。
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image のインスタンスを作成し、Create メソッドを呼び出して PsdOptions のインスタンスで初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //画像処理を行います。

    // すべての変更を保存します。
    image.Save();
}
```

### 関連項目

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


