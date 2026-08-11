---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.PSD for .NET API Reference"
description: "IImageLoaderDescriptor メソッド。指定されたストリームから新しい画像を読み取れるか、必要に応じて loadOptions を使用して判定します。"
type: docs
weight: 10
url: /ja/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

指定されたストリームから新しい画像を読み取れるかどうかを判定し、オプションで *loadOptions* を使用します。

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | StreamContainer | ストリームコンテナ。 |
| loadOptions | LoadOptions | *loadOptions* で指定されたファイル形式の詳細。*loadOptions* は null の可能性があります。 |

### 戻り値

このディスクリプタで作成された画像ローダがストリームから画像を読み取れる場合は `true`、それ以外は `false`。

### 関連項目

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


