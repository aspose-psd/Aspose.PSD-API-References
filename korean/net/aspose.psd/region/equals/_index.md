---
title: "Region.Equals"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Region 메서드. 지정된 그리기 표면에서 지정된 Region이 이 Region과 동일한지 테스트합니다"
type: docs
weight: 40
url: /ko/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

지정된 그리기 표면에서 지정된 [`Region`](../)이 이 [`Region`](../)과 동일한지 테스트합니다.

```csharp
public bool Equals(Region region, Graphics g)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | Region | 테스트할 [`Region`](../). |
| g | Graphics | 그리기 표면을 나타내는 [`Graphics`](../../graphics/)입니다. |

### 반환 값

*g* 매개변수와 연관된 변환이 적용될 때 region의 내부가 이 region의 내부와 동일하면 True; 그렇지 않으면 false.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *g *or* region*은 null입니다. |

### 또 보기

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

객체가 동일한지 확인합니다.

```csharp
public override bool Equals(object obj)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | Object | 다른 객체. |

### 반환 값

동등성 비교 결과.

### 또 보기

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


