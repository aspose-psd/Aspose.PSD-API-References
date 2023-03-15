---
title: Image.Create
second_title: Aspose.PSD for .NET API リファレンス
description: Image 方法. 指定された作成オプションを使用して新しいイメージを作成します
type: docs
weight: 10
url: /ja/net/aspose.psd/image/create/
---
## Image.Create method

指定された作成オプションを使用して新しいイメージを作成します。

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 画像オプション. |
| width | Int32 | 幅. |
| height | Int32 | 高さ. |

### 戻り値

新しく作成されたイメージ。

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)


