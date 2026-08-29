---
title: "License"
second_title: "Java용 Aspose.PSD API 참조"
description: "구성 요소에 대한 라이선스 부여 메서드를 제공합니다."
type: docs
weight: 65
url: /ko/java/com.aspose.psd/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

구성 요소에 대한 라이선스 부여 메서드를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCodeMessages()](#getErrorCodeMessages--) | 오류 코드 메시지를 가져옵니다. |
| [getRenewSubscriptionStartMessage()](#getRenewSubscriptionStartMessage--) | 구독 갱신 시작 메시지를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isLicensed_internalized()](#isLicensed-internalized--) | 제품이 라이선스가 부여되었는지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLicense()](#removeLicense--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | 구성 요소에 라이선스를 부여합니다. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 부여합니다. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 부여합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


이 클래스의 새 인스턴스를 초기화합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorCodeMessages() {#getErrorCodeMessages--}
```
public static ByteObjDictionary<String> getErrorCodeMessages()
```


오류 코드 메시지를 가져옵니다.

값: 오류 코드 메시지.

**Returns:**
com.aspose.java.optimization.maps.ByteObjDictionary<java.lang.String> - 오류 코드 메시지.
### getRenewSubscriptionStartMessage() {#getRenewSubscriptionStartMessage--}
```
public static String getRenewSubscriptionStartMessage()
```


구독 갱신 시작 메시지를 가져옵니다.

값: 구독 갱신 시작 메시지.

**Returns:**
java.lang.String - 구독 갱신 시작 메시지.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLicensed_internalized() {#isLicensed-internalized--}
```
public static boolean isLicensed_internalized()
```


제품이 라이선스가 부여되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 제품이 라이선스된 경우 true, 그렇지 않으면 false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeLicense() {#removeLicense--}
```
public static void removeLicense()
```




### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public void setLicense(File licenseFile)
```


구성 요소에 라이선스를 부여합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseFile | java.io.File | 파일 경로 이름의 표현 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


구성 요소에 라이선스를 부여합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 라이선스를 포함하는 스트림. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


구성 요소에 라이선스를 부여합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | java.lang.String | 전체 파일 이름이거나 짧은 파일 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

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

