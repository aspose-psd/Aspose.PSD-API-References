---
title: "Image.Create"
second_title: "Aspose.PSD for .NET API Reference"
description: "Image メソッド。指定された作成オプションを使用して新しい画像を作成します"
type: docs
weight: 10
url: /ja/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

指定された作成オプションを使用して新しい画像を作成します。

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 画像オプション。 |
| width | Int32 | 幅です。 |
| height | Int32 | 高さです。 |

### 戻り値

新しく作成された画像。

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


