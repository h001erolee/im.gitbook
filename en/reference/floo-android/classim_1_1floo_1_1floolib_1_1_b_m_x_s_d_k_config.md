---
title: im::floo::floolib::BMXSDKConfig
summary: SDK settings management
---

# im::floo::floolib::BMXSDKConfig

SDK settings management

## Public Classes

|       | Name                                                                                                    |
| ----- | ------------------------------------------------------------------------------------------------------- |
| class | [**HostConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config\_1\_1\_host\_config.md) |

## Public Functions

|                           | Name                                                                                                                                                                                                                                                      |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| synchronized void         | [**delete**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-delete)()                                                                                                                                                         |
|                           | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_s_d_k_config.md#function-bmxsdkconfig"><strong>BMXSDKConfig</strong></a>([BMXClientType] type, String vsn, String dataDir, String cacheDir, String pushCertName, boolean deliveryAck)<br>Constructor</p> |
|                           | [**BMXSDKConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-bmxsdkconfig)(\[BMXClientType] type, String vsn, String dataDir, String cacheDir, String pushCertName)                                                      |
|                           | [**BMXSDKConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-bmxsdkconfig)(\[BMXClientType] type, String vsn, String dataDir, String cacheDir, String pushCertName, String appId, String appSecret, boolean deliveryAck) |
|                           | [**BMXSDKConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-bmxsdkconfig)(\[BMXClientType] type, String vsn, String dataDir, String cacheDir, String pushCertName, String appId, String appSecret)                      |
| String                    | [**getDataDir**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getdatadir)()                                                                                                                                                 |
| String                    | [**getCacheDir**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getcachedir)()                                                                                                                                               |
| \[BMXClientType]          | [**getClientType**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getclienttype)()                                                                                                                                           |
| String                    | [**getVsn**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getvsn)()                                                                                                                                                         |
| String                    | [**getSDKVersion**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getsdkversion)()                                                                                                                                           |
| String                    | [**getPushCertName**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getpushcertname)()                                                                                                                                       |
| void                      | [**setPushCertName**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setpushcertname)(String arg0)                                                                                                                            |
| String                    | [**getUserAgent**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getuseragent)()                                                                                                                                             |
| boolean                   | [**carryUsernameInMessage**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-carryusernameinmessage)()                                                                                                                         |
| void                      | [**setCarryUsernameInMessage**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setcarryusernameinmessage)(boolean arg0)                                                                                                       |
| boolean                   | [**enableDeliveryAck**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-enabledeliveryack)()                                                                                                                                   |
| void                      | [**setEnableDeliveryAck**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setenabledeliveryack)(boolean arg0)                                                                                                                 |
| BMXLogLevel               | [**getLogLevel**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getloglevel)()                                                                                                                                               |
| void                      | [**setLogLevel**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setloglevel)(BMXLogLevel arg0)                                                                                                                               |
| boolean                   | [**getConsoleOutput**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getconsoleoutput)()                                                                                                                                     |
| void                      | [**setConsoleOutput**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setconsoleoutput)(boolean arg0)                                                                                                                         |
| void                      | [**setHostConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-sethostconfig)(BMXSDKConfig.HostConfig config)                                                                                                             |
| BMXSDKConfig.HostConfig   | [**getHostConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-gethostconfig)()                                                                                                                                           |
| boolean                   | [**getLoadAllServerConversations**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getloadallserverconversations)()                                                                                                           |
| void                      | [**setLoadAllServerConversations**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setloadallserverconversations)(boolean enable)                                                                                             |
| void                      | [**setLoadAllServerConversations**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setloadallserverconversations)()                                                                                                           |
| String                    | [**getDeviceUuid**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getdeviceuuid)()                                                                                                                                           |
| void                      | [**setDeviceUuid**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setdeviceuuid)(String uuid)                                                                                                                                |
| String                    | [**getDBCryptoKey**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getdbcryptokey)()                                                                                                                                         |
| void                      | [**setDBCryptoKey**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setdbcryptokey)(String cryptoKey)                                                                                                                         |
| boolean                   | [**getVerifyCertificate**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getverifycertificate)()                                                                                                                             |
| void                      | [**setVerifyCertificate**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setverifycertificate)(boolean verify)                                                                                                               |
| void                      | [**setVerifyCertificate**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setverifycertificate)()                                                                                                                             |
| boolean                   | [**getEnableDNS**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getenabledns)()                                                                                                                                             |
| void                      | [**setEnableDNS**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setenabledns)(boolean enable)                                                                                                                               |
| void                      | [**setEnableDNS**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setenabledns)()                                                                                                                                             |
| String                    | [**getUserDNSAddress**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getuserdnsaddress)()                                                                                                                                   |
| void                      | [**setUserDNSAddress**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setuserdnsaddress)(String dns)                                                                                                                         |
| String                    | [**getAppID**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getappid)()                                                                                                                                                     |
| void                      | [**setAppID**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setappid)(String appID)                                                                                                                                         |
| String                    | [**getAppSecret**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getappsecret)()                                                                                                                                             |
| void                      | [**setAppSecret**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setappsecret)(String appSecret)                                                                                                                             |
| \[BMXPushProviderType]    | [**getPushProviderType**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getpushprovidertype)()                                                                                                                               |
| void                      | [**setPushProviderType**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setpushprovidertype)(\[BMXPushProviderType] type)                                                                                                    |
| \[BMXPushEnvironmentType] | [**getPushEnvironmentType**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getpushenvironmenttype)()                                                                                                                         |
| void                      | [**setEnvironmentType**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setenvironmenttype)(\[BMXPushEnvironmentType] type)                                                                                                   |
| long                      | [**getDebugLogReceiverId**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getdebuglogreceiverid)()                                                                                                                           |
| void                      | [**setDebugLogReceiverId**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-setdebuglogreceiverid)(long uid)                                                                                                                   |

## Protected Functions

|      | Name                                                                                                                                                                                     |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      | [**BMXSDKConfig**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-bmxsdkconfig)(long cPtr, boolean cMemoryOwn)                                               |
| void | [**finalize**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-finalize)()                                                                                    |
| long | [**getCPtr**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md#function-getcptr)([BMXSDKConfig](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_s\_d\_k\_config.md) obj) |

## Public Functions Documentation

### function delete

```java
inline synchronized void delete()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function BMXSDKConfig

```java
inline BMXSDKConfig(
    BMXClientType type,
    String vsn,
    String dataDir,
    String cacheDir,
    String pushCertName,
    boolean deliveryAck
)
```

Constructor

**Parameters**:

* **type** Client type
* **vsn** Client OS version
* **dataDir** Storage path of chat data
* **cacheDir** Storage path of cached data
* **pushCertName** Push certificate name
* **deliveryAck** Whether to send message delivery acknowledgement

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function BMXSDKConfig

```java
inline BMXSDKConfig(
    BMXClientType type,
    String vsn,
    String dataDir,
    String cacheDir,
    String pushCertName
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function BMXSDKConfig

```java
inline BMXSDKConfig(
    BMXClientType type,
    String vsn,
    String dataDir,
    String cacheDir,
    String pushCertName,
    String appId,
    String appSecret,
    boolean deliveryAck
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function BMXSDKConfig

```java
inline BMXSDKConfig(
    BMXClientType type,
    String vsn,
    String dataDir,
    String cacheDir,
    String pushCertName,
    String appId,
    String appSecret
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getDataDir

```java
inline String getDataDir()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getCacheDir

```java
inline String getCacheDir()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getClientType

```java
inline BMXClientType getClientType()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getVsn

```java
inline String getVsn()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getSDKVersion

```java
inline String getSDKVersion()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getPushCertName

```java
inline String getPushCertName()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setPushCertName

```java
inline void setPushCertName(
    String arg0
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getUserAgent

```java
inline String getUserAgent()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function carryUsernameInMessage

```java
inline boolean carryUsernameInMessage()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setCarryUsernameInMessage

```java
inline void setCarryUsernameInMessage(
    boolean arg0
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function enableDeliveryAck

```java
inline boolean enableDeliveryAck()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setEnableDeliveryAck

```java
inline void setEnableDeliveryAck(
    boolean arg0
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getLogLevel

```java
inline BMXLogLevel getLogLevel()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setLogLevel

```java
inline void setLogLevel(
    BMXLogLevel arg0
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getConsoleOutput

```java
inline boolean getConsoleOutput()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setConsoleOutput

```java
inline void setConsoleOutput(
    boolean arg0
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setHostConfig

```java
inline void setHostConfig(
    BMXSDKConfig.HostConfig config
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getHostConfig

```java
inline BMXSDKConfig.HostConfig getHostConfig()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getLoadAllServerConversations

```java
inline boolean getLoadAllServerConversations()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setLoadAllServerConversations

```java
inline void setLoadAllServerConversations(
    boolean enable
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setLoadAllServerConversations

```java
inline void setLoadAllServerConversations()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getDeviceUuid

```java
inline String getDeviceUuid()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setDeviceUuid

```java
inline void setDeviceUuid(
    String uuid
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getDBCryptoKey

```java
inline String getDBCryptoKey()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setDBCryptoKey

```java
inline void setDBCryptoKey(
    String cryptoKey
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getVerifyCertificate

```java
inline boolean getVerifyCertificate()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setVerifyCertificate

```java
inline void setVerifyCertificate(
    boolean verify
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setVerifyCertificate

```java
inline void setVerifyCertificate()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getEnableDNS

```java
inline boolean getEnableDNS()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setEnableDNS

```java
inline void setEnableDNS(
    boolean enable
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setEnableDNS

```java
inline void setEnableDNS()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getUserDNSAddress

```java
inline String getUserDNSAddress()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setUserDNSAddress

```java
inline void setUserDNSAddress(
    String dns
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getAppID

```java
inline String getAppID()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setAppID

```java
inline void setAppID(
    String appID
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getAppSecret

```java
inline String getAppSecret()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setAppSecret

```java
inline void setAppSecret(
    String appSecret
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getPushProviderType

```java
inline BMXPushProviderType getPushProviderType()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setPushProviderType

```java
inline void setPushProviderType(
    BMXPushProviderType type
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getPushEnvironmentType

```java
inline BMXPushEnvironmentType getPushEnvironmentType()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setEnvironmentType

```java
inline void setEnvironmentType(
    BMXPushEnvironmentType type
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getDebugLogReceiverId

```java
inline long getDebugLogReceiverId()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function setDebugLogReceiverId

```java
inline void setDebugLogReceiverId(
    long uid
)
```

## Protected Functions Documentation

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function BMXSDKConfig

```java
inline BMXSDKConfig(
    long cPtr,
    boolean cMemoryOwn
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function finalize

```java
inline void finalize()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```

### function getCPtr

```java
static inline long getCPtr(
    BMXSDKConfig obj
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXSDKConfig'></div>
```



Updated on 2022-01-26 at 17:18:31 +0800
