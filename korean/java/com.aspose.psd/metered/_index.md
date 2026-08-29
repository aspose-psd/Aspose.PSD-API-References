---
title: "Metered"
second_title: "Java용 Aspose.PSD API 참조"
description: "통합을 위한 계량 메서드를 제공합니다."
type: docs
weight: 71
url: /ko/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

통합을 위한 계량 메서드를 제공합니다.

이 예제에서는 계량된(public) 및 개인(private) 키를 설정하려고 시도합니다.

// 구성 요소 jar 파일: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 이 인스턴스와 같은지 확인합니다. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비 크레딧을 가져옵니다 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비 파일 크기를 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 계량된(public) 및 개인(private) 키를 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


### FlushTimeout_internalized {#FlushTimeout-internalized}
```
public static int FlushTimeout_internalized
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 이 인스턴스와 같은지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 Object입니다. |

**Returns:**
boolean - 지정된 Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


소비 크레딧을 가져옵니다

**Returns:**
java.math.BigDecimal - 소비 수량
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


소비 파일 크기를 가져옵니다

**Returns:**
java.math.BigDecimal - 소비 파일 크기
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


계량된(public) 및 개인(private) 키를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키 |
| privateKey | java.lang.String | 비공개 키 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

