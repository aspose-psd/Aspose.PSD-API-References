---
title: "Image.RotateFlip"
second_title: "Aspose.PSD for .NET API Reference"
description: "Image メソッド。画像を回転・反転、または回転と反転を行います。"
type: docs
weight: 230
url: /ja/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

画像を回転、フリップ、または回転とフリップを行います。

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | rotate flip の型。 |

## 例

この例は、画像に対する Rotate 操作の使用方法を示しています。例では、ディスク上の既存の画像ファイルをロードし、Enum Aspose.PSD.RotateFlipType の値に従って画像に Rotate 操作を実行します。

```csharp
[C#]

//Image クラスのインスタンスを作成し、ファイルパスを通じて既存の画像ファイルで初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //画像を X 軸周りに 180 度回転させます。
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // すべての変更を保存します。
    image.Save();
}
```

### 関連項目

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


