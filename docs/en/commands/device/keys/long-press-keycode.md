[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
# Long Press Key Code

Press and hold a particular key code on an Android device
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
## Example Usage

```java
// Java
driver.longPressKeyCode(AndroidKeyCode.HOME);

```

```python
# Python
self.driver.long_press_keycode(10);

```

```javascript
// Javascript
// webdriver.io example
driver.longPressKeyCode(10);

// wd example
await driver.longPressKeycode(10);

```

```ruby
# Ruby
# ruby_lib example
long_press_keycode(10)

# ruby_lib_core example
@driver.long_press_keycode(10)

```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
// TODO C# sample

```

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
## Description

See https://developer.android.com/reference/android/view/KeyEvent.html# for reference of available Android key codes

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
## Support

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | None | None | None |
| Android | [Espresso](/docs/en/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | None | None | None |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
### Appium Clients

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/windows/PressesKeyCode.html#longPressKeyCode-int-) |
|[Python](https://github.com/appium/python-client/releases/latest)| All | [github.com](https://github.com/appium/python-client/blob/master/README.md#long_press) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L2478) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#long_press_keycode-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| All | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All | [github.com](https://github.com/appium/appium-dotnet-driver/) |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
## HTTP API Specifications

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
### Endpoint

`POST /session/:session_id/appium/device/long_press_keycode`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to route the command to|

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
### JSON Parameters

|name|type|description|
|----|----|-----------|
| keycode | `number` | Key code pressed on the device. See [Key Event](http://developer.android.com/reference/android/view/KeyEvent.html). |
| metastate | `number` | Metastate for the keypress. See [Key Event](http://developer.android.com/reference/android/view/KeyEvent.html). |
| flags | `number` | Flags for the keypress. See [Key Event](http://developer.android.com/reference/android/view/KeyEvent.html). |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
### Response

null

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/long-press-keycode.yml)
## See Also

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L377)
