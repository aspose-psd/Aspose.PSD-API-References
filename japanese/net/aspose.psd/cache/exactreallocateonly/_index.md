---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD for .NET API リファレンス
description: Cache 財産. 再割り当てが正確かどうかを示す値を取得または設定します再割り当てが正確でない場合パフォーマンスはより高くなるはずです.
type: docs
weight: 50
url: /ja/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

再割り当てが正確かどうかを示す値を取得または設定します。再割り当てが正確でない場合、パフォーマンスはより高くなるはずです.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### プロパティ値

`真実`再割り当てが正確である場合。さもないと、`間違い` .

### 備考

正確な再割り当てでは、指定された上限までのみ追加メモリの再割り当てが実行されます。適切な例外がスローされます。 可能であれば追加のコピーが実行されないため、このオプションをオフにするとパフォーマンスが向上しますが、 ただし、メモリまたはディスクに指定された上限を超える可能性もあります。

### 関連項目

* class [Cache](../)
* 名前空間 [Aspose.PSD](../../cache/)
* 組み立て [Aspose.PSD](../../../)


