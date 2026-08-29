---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerMaskData 속성. PSD 파일에서 레이어 마스크의 마스크 Rectangle을 가져오거나 설정합니다. left, right, top 및 bottom 속성을 받아 Rectangle을 생성합니다"
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

PSD 파일에서 레이어 마스크의 마스크 [`Rectangle`](../../../aspose.psd/rectangle/)을 가져오거나 설정합니다. left, right, top 및 bottom 속성을 받아 [`Rectangle`](../../../aspose.psd/rectangle/)을 생성합니다

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

마스크 Rectangle.

## 예제

이 예제는 Adobe® Photoshop® 파일에서 래스터 레이어 마스크를 프로그래밍 방식으로 가져오고, 업데이트하고, 제거하고, 추가하는 방법을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// int 값을 빅 엔디안 바이트 순서로 변환하여 가져옵니다.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// 빅 엔디안에서 Int32로 변환된 값을 가져옵니다.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// PSD 이미지의 레이어에서 래스터 마스크를 가져와 파일에 저장합니다
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// 파일에서 래스터 마스크를 레이어에 추가하고 PSD 형식 이미지로 저장합니다
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // LayerMaskData만 추가해도 채널이 업데이트되지 않아 올바르게 저장되지 않습니다;
    // layer.LayerMaskData = mask; // 마스크 채널을 추가하지 않습니다

    // 마스크 추가(또는 업데이트)
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// 이 예제는 Adobe® Photoshop® 파일에서 래스터 레이어 마스크를 프로그래밍 방식으로 가져오고, 업데이트하고, 제거하고, 추가하는 방법을 보여줍니다.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // 레이어에서 래스터 마스크를 가져와 파일에 저장합니다
    SaveRasterMask("FourWithMasks2.msk", layer);

    // 레이어 마스크를 변경(반전)하고 이미지를 저장합니다
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // LayerMaskData만 변경하면 렌더링에 영향을 주기에 충분합니다.
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // 하지만 채널이 업데이트되지 않기 때문에 올바른 저장을 위해서는 LayerMaskData만 변경하는 것으로는 충분하지 않습니다;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // 레이어에서 래스터 마스크를 제거하고 이미지를 저장합니다.
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // 파일에서 래스터 마스크를 레이어에 추가하고 이미지를 저장합니다.
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### 또 보기

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


