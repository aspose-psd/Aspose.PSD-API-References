---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD for .NET API リファレンス
description: FileCreateSource コンストラクタ. の新しいインスタンスを初期化しますFileCreateSourceclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

の新しいインスタンスを初期化します[`FileCreateSource`](../)class.

```csharp
public FileCreateSource(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 作成するファイル パス。 |

### 例

この例では、BmpOptions インスタンスの Source プロパティで指定されたディスクの場所に新しいイメージ ファイルを作成します。 2 番目のパラメーターが FileCreateSource のコンストラクターに渡されない場合、デフォルトでは、作成されるファイルのプロパティ IsTemporal が True に設定されます。 IsTemporal を True に設定すると、実行終了時にファイルはディスクに保存されません。

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource のインスタンスを作成し、それを PsdOptions のインスタンスの Source として割り当てます
//2 番目のパラメータが渡されない場合、デフォルトでファイルの IsTemporal は True に設定されます
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Image のインスタンスを作成します 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 画像処理を行います
}
```

### 関連項目

* class [FileCreateSource](../)
* 名前空間 [Aspose.PSD.Sources](../../filecreatesource/)
* 組み立て [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

の新しいインスタンスを初期化します[`FileCreateSource`](../)class.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 作成するファイル パス。 |
| isTemporal | Boolean | に設定した場合`真実`作成されたファイルは一時的なものになります。 |

### 例

この例では、PsdOptions インスタンスの Source プロパティで指定されたディスクの場所に新しいイメージ ファイルを作成します。実際のイメージを作成する前に、PsdOptions インスタンスのいくつかのプロパティが設定されます。特に、この場合、実際のディスクの場所を参照する Source プロパティ。

```csharp
[C#]

// PsdOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource のインスタンスを作成し、それを PsdOptions のインスタンスの Source として割り当てます
//2 番目のブール値パラメーターは、作成するファイルが IsTemporal かどうかを決定します
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// Image のインスタンスを作成し、Create メソッドを呼び出して PsdOptions のインスタンスで初期化します
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 画像処理を行います

    // すべての変更を保存
    image.Save();
}
```

### 関連項目

* class [FileCreateSource](../)
* 名前空間 [Aspose.PSD.Sources](../../filecreatesource/)
* 組み立て [Aspose.PSD](../../../)


