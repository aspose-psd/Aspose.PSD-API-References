---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PixelDataFormat 속성. 알파, 빨강, 초록, 파랑 각각에 16비트를 사용하여 픽셀당 64비트로 정의된 PixelDataFormat을 가져옵니다."
type: docs
weight: 110
url: /ko/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

픽셀당 64비트이며 알파, 빨강, 초록, 파랑 각각에 16비트가 할당된 경우 정의된 [`PixelDataFormat`](../)을 가져옵니다.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

픽셀당 64비트이며 알파, 빨강, 초록, 파랑 각각에 16비트가 할당된 경우 정의된 [`PixelDataFormat`](../)입니다.

## 예제

다음 코드는 구식 Color 구조체 대신 RawColor 클래스를 지원하는 예시를 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 또 보기

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


