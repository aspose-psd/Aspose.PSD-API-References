---
title: "インターフェイス IImageLoaderDescriptor"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.IImageLoaderDescriptor インターフェイス。ローダーのプロパティを指定するイメージローダーデスクリプタです。ローダーデスクリプタは、各イメージローダーインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。"
type: docs
weight: 4930
url: /ja/net/aspose.psd/iimageloaderdescriptor/
---
{{< psd/tize >}}
## IImageLoaderDescriptor interface

画像ローダーディスクリプタはローダーのプロパティを指定します。ローダーディスクリプタは、各画像ローダーインスタンスをメモリに保持する必要性やマルチスレッドの問題を回避するために使用されます。

```csharp
public interface IImageLoaderDescriptor : IImageDescriptor
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CanLoad](../../aspose.psd/iimageloaderdescriptor/canload/)(StreamContainer, LoadOptions) | 指定されたストリームから新しい画像を読み取れるかどうかを判定し、オプションで *loadOptions* を使用します。 |
| [CreateInstance](../../aspose.psd/iimageloaderdescriptor/createinstance/)() | 新しいローダーインスタンスを作成します。 |

### 関連項目

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


