---
title: StreamSource.StreamSource
second_title: Aspose.PSD for .NET API リファレンス
description: StreamSource コンストラクタ. の新しいインスタンスを初期化しますStreamSourceclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

の新しいインスタンスを初期化します[`StreamSource`](../)class.

```csharp
public StreamSource(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 開くストリーム。 |

### 例

この例では、Type Color の配列にピクセル情報をロードし、配列を操作して画像に戻す方法を示します。これらの操作を実行するために、この例では、MemoryStream オブジェクトを使用して新しいイメージ ファイル (PSD 形式) を作成します。

```csharp
[C#]

//MemoryStream のインスタンスを作成する
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions のインスタンスを作成し、Source プロパティを含むさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image のインスタンスを作成する
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //領域を画像境界として指定して、画像のピクセルを取得します
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //配列をループし、代替インデックス付きピクセルの色を設定します
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //インデックス付きピクセルの色を黄色に設定
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //インデックス付きピクセルの色を青に設定
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // ピクセルの変更を画像に適用します
        image.SavePixels(image.Bounds, pixels);

        // すべての変更を保存します。
        image.Save();
    }

    //メモリストリームをファイルに書き込む
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 関連項目

* class [StreamSource](../)
* 名前空間 [Aspose.PSD.Sources](../../streamsource/)
* 組み立て [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

の新しいインスタンスを初期化します[`StreamSource`](../)class.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 開くストリーム。 |
| disposeStream | Boolean | に設定した場合`真実`ストリームは破棄されます。 |

### 例

この例では、System.IO.Stream を使用して新しいイメージ ファイルを作成する方法を示します。

```csharp
[C#]

//PsdOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// System.IO.Stream のインスタンスを作成します
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions のインスタンスのソース プロパティを定義します
// 2 番目のブール値パラメーターは、Stream がスコープ外になった後に破棄されるかどうかを決定します
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// Image のインスタンスを作成し、PsdOptions をパラメーターとして Create メソッドを呼び出して Image オブジェクトを初期化します   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 画像処理を行います
}
```

### 関連項目

* class [StreamSource](../)
* 名前空間 [Aspose.PSD.Sources](../../streamsource/)
* 組み立て [Aspose.PSD](../../../)


