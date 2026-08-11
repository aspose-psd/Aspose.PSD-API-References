---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD for .NET API Reference"
description: "Cache プロパティ。再割り当てが正確であるかどうかを示す値を取得または設定します。再割り当てが正確でない場合、パフォーマンスが向上するはずです"
type: docs
weight: 50
url: /ja/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

再割り当てが正確であるべきかどうかを示す値を取得または設定します。再割り当てが正確でない場合、パフォーマンスが向上するはずです。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` は再割り当てが正確な場合、そうでなければ `false`。

## 備考

正確な再割り当ては、指定された上限まで追加メモリの再割り当てを行います。再割り当て中にメモリ上限を指定すると、可能な場合はキャッシュされたデータがディスクにコピーされます。ディスクメモリ上限を指定すると、適切な例外がスローされます。このオプションをオフにすると、可能な限り追加のコピーが行われないためパフォーマンスが向上するはずですが、メモリまたはディスクの上限を指定した場合に問題が発生する可能性もあります。

### 関連項目

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


