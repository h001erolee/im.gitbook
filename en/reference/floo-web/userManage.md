# userManage

## userManage <a href="#module_usermanage" id="module_usermanage"></a>

* [userManage](userManage.md#module\_usermanage)
  * [.getToken()](userManage.md#module\_usermanage\_\_gettoken) ⇒ `string`
  * [.getUid()](userManage.md#module\_usermanage\_\_getuid) ⇒ `number`
  * [.getAppid()](userManage.md#module\_usermanage\_\_getappid) ⇒ `string`
  * [.getConversationList()](userManage.md#module\_usermanage\_\_getconversationlist) ⇒ [`Array.<ConversationItem>`](types.md#module\_types\_\_conversationitem)
  * [.getDeviceSN()](userManage.md#module\_usermanage\_\_getdevicesn) ⇒ `number`
  * [.asyncBindDeviceToken(param)](userManage.md#module\_usermanage\_\_asyncbinddevicetoken) ⇒ `Promise.<boolean>`
  * [.asyncUnbindDeviceToken(param)](userManage.md#module\_usermanage\_\_asyncunbinddevicetoken) ⇒ `Promise.<boolean>`
  * [.asyncRegister(opt)](userManage.md#module\_usermanage\_\_asyncregister) ⇒ [`Promise.<UserSettings>`](types.md#module\_types\_\_usersettings)
  * [.asyncUpdateAvatar(params)](userManage.md#module\_usermanage\_\_asyncupdateavatar) ⇒ `Promise.<boolean>`
  * [.asyncUpdateNickName(params)](userManage.md#module\_usermanage\_\_asyncupdatenickname) ⇒ `Promise.<boolean>`
  * [.asyncGetProfile()](userManage.md#module\_usermanage\_\_asyncgetprofile) ⇒ [`Promise.<UserProfile>`](types.md#module\_types\_\_userprofile)
  * [.asyncUpdateProfile(params)](userManage.md#module\_usermanage\_\_asyncupdateprofile) ⇒ `Promise.<boolean>`
  * [.asyncGetSettings()](userManage.md#module\_usermanage\_\_asyncgetsettings) ⇒ [`Promise.<UserSettings>`](types.md#module\_types\_\_usersettings)
  * [.asyncUpdateSettings(settings)](userManage.md#module\_usermanage\_\_asyncupdatesettings) ⇒ `Promise.<boolean>`

### userManage.getToken() ⇒ `string` <a href="#module_usermanage__gettoken" id="module_usermanage__gettoken"></a>

Get token of logged-in user

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `string` - User's token\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.getUid() ⇒ `number` <a href="#module_usermanage__getuid" id="module_usermanage__getuid"></a>

Get uid of logged-in user

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `number` - User ID\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.getAppid() ⇒ `string` <a href="#module_usermanage__getappid" id="module_usermanage__getappid"></a>

Get appid

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `string` - APP ID\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.getConversationList() ⇒ [`Array.<ConversationItem>`](types.md#module\_types\_\_conversationitem) <a href="#module_usermanage__getconversationlist" id="module_usermanage__getconversationlist"></a>

Get list of recent conversations

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.getDeviceSN() ⇒ `number` <a href="#module_usermanage__getdevicesn" id="module_usermanage__getdevicesn"></a>

Get device serial number

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `number` - Device serial number\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncBindDeviceToken(param) ⇒ `Promise.<boolean>` <a href="#module_usermanage__asyncbinddevicetoken" id="module_usermanage__asyncbinddevicetoken"></a>

Bind push device

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `Promise.<boolean>` - Success or not

| Param                | Type     | Description                                                                                          |
| -------------------- | -------- | ---------------------------------------------------------------------------------------------------- |
| param                | `object` | Bind request                                                                                         |
| param.device\_sn     | `number` | Device serial number                                                                                 |
| param.notifier\_name | `string` | The certificate name, that is, the name set when uploading the certificate in the LanyingIM Console. |
| param.device\_token  | `string` | Push device token                                                                                    |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncUnbindDeviceToken(param) ⇒ `Promise.<boolean>` <a href="#module_usermanage__asyncunbinddevicetoken" id="module_usermanage__asyncunbinddevicetoken"></a>

Unbind push device

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `Promise.<boolean>` - Success or not

| Param          | Type     | Description          |
| -------------- | -------- | -------------------- |
| param          | `object` | Unbind request       |
| param.deviceSn | `number` | Device serial number |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncRegister(opt) ⇒ [`Promise.<UserSettings>`](types.md#module\_types\_\_usersettings) <a href="#module_usermanage__asyncregister" id="module_usermanage__asyncregister"></a>

User registeration

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: [`Promise.<UserSettings>`](types.md#module\_types\_\_usersettings) - User settings

| Param        | Type     | Description      |
| ------------ | -------- | ---------------- |
| opt          | `object` | User information |
| opt.username | `string` | Username         |
| opt.password | `string` | Password         |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncUpdateAvatar(params) ⇒ `Promise.<boolean>` <a href="#module_usermanage__asyncupdateavatar" id="module_usermanage__asyncupdateavatar"></a>

Update avatar

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `Promise.<boolean>` - Success or not

| Param         | Type     | Description |
| ------------- | -------- | ----------- |
| params        | `object` | Parameter   |
| params.avatar | `string` | Avatar url  |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncUpdateNickName(params) ⇒ `Promise.<boolean>` <a href="#module_usermanage__asyncupdatenickname" id="module_usermanage__asyncupdatenickname"></a>

Update nickname

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `Promise.<boolean>` - Success or not

| Param             | Type     | Description |
| ----------------- | -------- | ----------- |
| params            | `object` | Parameter   |
| params.nick\_name | `string` | Nickname    |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncGetProfile() ⇒ [`Promise.<UserProfile>`](types.md#module\_types\_\_userprofile) <a href="#module_usermanage__asyncgetprofile" id="module_usermanage__asyncgetprofile"></a>

Get user profile

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: [`Promise.<UserProfile>`](types.md#module\_types\_\_userprofile) - User information\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncUpdateProfile(params) ⇒ `Promise.<boolean>` <a href="#module_usermanage__asyncupdateprofile" id="module_usermanage__asyncupdateprofile"></a>

Update user profile

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `Promise.<boolean>` - Success or not

| Param                | Type     | Description                                               |
| -------------------- | -------- | --------------------------------------------------------- |
| params               | `object` |                                                           |
| params.description   | `string` | Description                                               |
| params.nick\_name    | `string` | Nickname                                                  |
| params.private\_info | `string` | Private information, visible only to yourself             |
| params.public\_info  | `string` | Public information, visible to both friends and strangers |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncGetSettings() ⇒ [`Promise.<UserSettings>`](types.md#module\_types\_\_usersettings) <a href="#module_usermanage__asyncgetsettings" id="module_usermanage__asyncgetsettings"></a>

Get user settings

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: [`Promise.<UserSettings>`](types.md#module\_types\_\_usersettings) - User information\
**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```

### userManage.asyncUpdateSettings(settings) ⇒ `Promise.<boolean>` <a href="#module_usermanage__asyncupdatesettings" id="module_usermanage__asyncupdatesettings"></a>

Modify user settings

**Kind**: static method of [`userManage`](userManage.md#module\_usermanage)\
**Returns**: `Promise.<boolean>` - Success or not

| Param    | Type                                                     | Description      |
| -------- | -------------------------------------------------------- | ---------------- |
| settings | [`UserSettings`](types.md#module\_types\_\_usersettings) | Updated settings |

**Example**

```js
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-web' data-class='userManage'></div>
```
