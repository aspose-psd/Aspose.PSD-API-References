---
title: Class Cache
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Cache クラス. キャッシュ設定が含まれています
type: docs
weight: 240
url: /ja/net/aspose.psd/cache/
---
## Cache class

キャッシュ設定が含まれています。

```csharp
public static class Cache
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | 割り当てられたディスクのバイト数を取得します。 |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | 割り当てられたメモリ内バイト数を取得します。 |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | キャッシュ フォルダーを取得または設定します。 |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | 使用されるキャッシュ スキームを取得または設定します。 |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | 再割り当てが正確かどうかを示す値を取得または設定します。再割り当てが正確でない場合、パフォーマンスはより高くなるはずです. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | キャッシュに使用できる最大ディスク容量を取得または設定します。指定された値は、メガバイト count. です。 |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | メモリ内のキャッシュに使用できる最大メモリを取得または設定します。指定された値は、メガバイト count. です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | を設定します`Cache`設定をデフォルトに。 |

### 例

この例では、Aspose.PSD.Cache の使用方法を示します。

```csharp
[C#]

// デフォルトでは、キャッシュ フォルダはユーザーのローカル一時ディレクトリに設定されます。
// 次のように、デフォルト以外のキャッシュ フォルダーを指定することもできます。
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// 自動モードは柔軟で効率的です
Cache.CacheType = CacheType.Auto;

// デフォルト値は 0 で、上限がないことを意味します
Cache.MaxDiskSpaceForCache = 1073741824; // 1ギガバイト
Cache.MaxMemoryForCache = 1073741824; // 1ギガバイト

// 以下のプロパティを変更すると、パフォーマンスに大きな影響を与える可能性があるため、推奨されません
Cache.ExactReallocateOnly = false;

// いつでも、メモリまたはディスクに現在割り当てられているバイト数を確認できます 
// 次のプロパティを調べてキャッシュします
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// 以下のように画像処理を行います
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

// 割り当てプロパティを使用して、すべての Aspose.PSD オブジェクトが適切に破棄されたかどうかを確認できます。
// 一部のオブジェクトで dispose を呼び出すのを忘れた場合、キャッシュ値は 0 以外になります。            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


