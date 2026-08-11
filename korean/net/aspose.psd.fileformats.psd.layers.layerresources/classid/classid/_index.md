---
title: "ClassID.ClassID"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ClassID 생성자. ClassID 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

`[`ClassID`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ClassID(byte[] classID)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| classID | Byte[] | 클래스 ID를 바이트 시퀀스로 나타냅니다. |

### 또 보기

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

`[`ClassID`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| classID | Byte[] | 클래스 ID를 바이트 시퀀스로 나타냅니다. |
| isZeroLength | Boolean | `true` 로 설정하면 [길이가 0입니다]. 기록된 문자열 길이는 0이지만 실제는 4입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | classID는 null입니다. |

### 또 보기

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

`[`ClassID`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ClassID(int classID)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| classID | Int32 | 클래스 ID. |

### 또 보기

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

`[`ClassID`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ClassID(uint classID)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| classID | UInt32 | 클래스 ID. |

### 또 보기

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

`[`ClassID`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| classID | String | ASCII 인코딩의 클래스 ID. |
| isZeroLength | Boolean | `true` 로 설정하면 [길이가 0입니다]. |

## 예제

이 예제는 이미지에서 가져온 레이어가 smart object 레이어로 변환되고 저장된 PSD 파일이 올바른 것을 보여줍니다.

```csharp
[C#]

// 이미지에서 가져온 레이어가 smart object 레이어로 변환되고 저장된 PSD 파일이 올바른지 테스트합니다.

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 또 보기

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

`[`ClassID`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public ClassID(string classID)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| classID | String | ASCII 인코딩의 클래스 ID. |

### 또 보기

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


