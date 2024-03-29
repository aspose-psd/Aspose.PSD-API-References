---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD for .NET API Reference
description: Cache property. Gets or sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher
type: docs
weight: 50
url: /net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Gets or sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` if reallocation is exact; otherwise, `false`.

## Remarks

The exact reallocation will perform reallocation of additional memory only up to the upper limit specified. When passing upper limit for in-memory during reallocation the cached data will be copied to disk if possible. When passing upper limit for disk memory during reallocation the appropriate exception is thrown. The performance should be higher if this option is turned off as no additional copying will be performed if possible, however this may also lead to pass upper limits specified for memory or disk.

### See Also

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


