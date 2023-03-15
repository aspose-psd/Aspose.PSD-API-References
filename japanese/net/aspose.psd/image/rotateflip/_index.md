---
title: Image.RotateFlip
second_title: Aspose.PSD for .NET API リファレンス
description: Image 方法. 画像を回転反転または回転して反転します
type: docs
weight: 220
url: /ja/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

画像を回転、反転、または回転して反転します。

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 回転フリップのタイプ. |

### 例

この例では、画像に対する回転操作の使用方法を示しています。この例では、既存のイメージ ファイルをディスクの場所からロードし、Enum Aspose.PSD.RotateFlipType の値に従って、イメージに対して Rotate 操作を実行します。

```csharp
[C#]

//画像クラスのインスタンスを作成し、ファイル パスを介して既存の画像ファイルで初期化します
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // X 軸を中心に画像を 180 度回転
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // すべての変更を保存します。
    image.Save();
}
```

### 関連項目

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)


