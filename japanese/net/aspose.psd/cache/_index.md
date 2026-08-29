---
title: "クラス Cache"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Cache クラス。キャッシュ設定を含みます"
type: docs
weight: 240
url: /ja/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

キャッシュ設定を含みます。

```csharp
public static class Cache
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | 割り当てられたディスクバイト数を取得します。 |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | 割り当てられたメモリ内バイト数を取得します。 |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | キャッシュフォルダーを取得または設定します。 |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | 使用されるキャッシュスキームを取得または設定します。 |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | 再割り当てが正確であるべきかどうかを示す値を取得または設定します。再割り当てが正確でない場合、パフォーマンスが向上するはずです。 |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | キャッシュ用の最大利用可能ディスク容量を取得または設定します。指定された値はメガバイト数です。 |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | キャッシュ用の最大利用可能メモリ容量を取得または設定します。指定された値はメガバイト数です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | `Cache` 設定をデフォルトに設定します。 |

## 例

この例は Aspose.PSD.Cache の使用方法を示しています。

```csharp
[C#]

// デフォルトでは、キャッシュフォルダーはユーザーのローカル一時ディレクトリに設定されます。
// 以下のように、デフォルト以外の別のキャッシュフォルダーを指定することもできます：
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// 自動モードは柔軟で効率的です。
Cache.CacheType = CacheType.Auto;

// デフォルト値は 0 で、上限がないことを意味します。
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// パフォーマンスに大きく影響する可能性があるため、以下のプロパティを変更することは推奨されません。
Cache.ExactReallocateOnly = false;

// いつでも、メモリまたはディスクに現在割り当てられているバイト数を確認できます。
// 以下のプロパティを調べることでキャッシュを確認できます。
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// 以下のように画像処理を行います。
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // 上記のコードを実行すると、メモリ内に 40000 バイトが割り当てられます。
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// 割り当てプロパティは、すべての Aspose.PSD オブジェクトが適切に破棄されたかどうかを確認するために使用できます。
// あるオブジェクトで dispose の呼び出しを忘れた場合、キャッシュ値は 0 とは異なる値になります。
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


