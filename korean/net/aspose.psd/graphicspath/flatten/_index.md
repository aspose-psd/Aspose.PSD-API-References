---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GraphicsPath 메서드. 이 경로의 각 곡선을 연결된 선분 시퀀스로 변환합니다."
type: docs
weight: 90
url: /ko/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

이 경로의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

```csharp
public void Flatten()
```

### 또 보기

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

지정된 변환을 적용한 다음 이 [`GraphicsPath`](../)의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

```csharp
public void Flatten(Matrix matrix)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | Matrix | 평탄화하기 전에 이 [`GraphicsPath`](../)를 변환하는 데 사용할 [`Matrix`](../../matrix/)입니다. |

### 또 보기

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

이 [`GraphicsPath`](../)의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | Matrix | 평탄화하기 전에 이 [`GraphicsPath`](../)를 변환하는 데 사용할 [`Matrix`](../../matrix/)입니다. |
| 평탄도 | 단일 | 곡선과 평탄화된 근사 사이의 허용 가능한 최대 오차를 지정합니다. 기본값은 0.25이며, 평탄도 값을 낮추면 근사에 사용되는 선분 수가 증가합니다. |

### 또 보기

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


