---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD for .NET API Reference"
description: "StreamSource コンストラクタ。StreamSource クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

[`StreamSource`](../) クラスの新しいインスタンスを初期化します。

```csharp
public StreamSource(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 開くストリーム。 |

## 例

この例では、Color 型の配列にピクセル情報をロードし、配列を操作して画像に戻す方法を示します。これらの操作を実行するために、MemoryStream オブジェクトを使用して新しい Image ファイル（PSD 形式）を作成します。

```csharp
[C#]

//MemoryStream のインスタンスを作成します。
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions のインスタンスを作成し、Source プロパティを含むさまざまなプロパティを設定します。
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image のインスタンスを作成します。
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //画像の境界を領域として指定して、画像のピクセルを取得します
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //配列をループし、代替インデックスピクセルの色を設定します
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //インデックスピクセルの色を黄色に設定します
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //インデックスピクセルの色を青に設定します
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //画像にピクセルの変更を適用します
        image.SavePixels(image.Bounds, pixels);

        // すべての変更を保存します。
        image.Save();
    }

    //MemoryStream をファイルに書き込みます
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 関連項目

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

[`StreamSource`](../) クラスの新しいインスタンスを初期化します。

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 開くストリーム。 |
| disposeStream | Boolean | `true` に設定すると、ストリームが破棄されます。 |

## 例

この例は System.IO.Stream を使用して新しい画像ファイルを作成する方法を示しています。

```csharp
[C#]

//PsdOptions のインスタンスを作成し、さまざまなプロパティを設定します。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream のインスタンスを作成します。
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions インスタンスの source プロパティを定義します。
//2 番目のブールパラメータは、スコープを抜けたときに Stream が破棄されるかどうかを決定します。
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image のインスタンスを作成し、PsdOptions をパラメータとして Create メソッドを呼び出して Image オブジェクトを初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //画像処理を行います。
}
```

### 関連項目

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


