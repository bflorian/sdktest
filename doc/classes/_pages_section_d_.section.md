[SmartApp](_smart_app_d_.smartapp.md) › [Page](_pages_page_d_.page.md) › [Section](_pages_section_d_.section.md)

# Section

A section is a labeled collection of settings. The contents can be made collapsable if desired.
To create a basic non-collapsable section:
```
page.section('section1', section => {
    // create settings here, e.g
    section.booleanSetting('turnBackOn')
}
```
To make this section collapsable (and initially collapsed):
```
page.section('section1', section => {
    section.hideable(true).hidden(true)

    // create settings here, e.g
    section.booleanSetting('turnBackOn')
}
```

## Methods

* [booleanSetting](_pages_section_d_.section.md#booleansetting)
* [decimalSetting](_pages_section_d_.section.md#decimalsetting)
* [defaultRequired](_pages_section_d_.section.md#defaultrequired)
* [deviceSetting](_pages_section_d_.section.md#devicesetting)
* [emailSetting](_pages_section_d_.section.md#emailsetting)
* [enumSetting](_pages_section_d_.section.md#enumsetting)
* [hidden](_pages_section_d_.section.md#hidden)
* [hideable](_pages_section_d_.section.md#hideable)
* [imageSetting](_pages_section_d_.section.md#imagesetting)
* [linkSetting](_pages_section_d_.section.md#linksetting)
* [modeSetting](_pages_section_d_.section.md#modesetting)
* [name](_pages_section_d_.section.md#name)
* [numberSetting](_pages_section_d_.section.md#numbersetting)
* [oauthSetting](_pages_section_d_.section.md#oauthsetting)
* [pageSetting](_pages_section_d_.section.md#pagesetting)
* [paragraphSetting](_pages_section_d_.section.md#paragraphsetting)
* [passwordSetting](_pages_section_d_.section.md#passwordsetting)
* [phoneSetting](_pages_section_d_.section.md#phonesetting)
* [sceneSetting](_pages_section_d_.section.md#scenesetting)
* [securitySetting](_pages_section_d_.section.md#securitysetting)
* [soundSetting](_pages_section_d_.section.md#soundsetting)
* [style](_pages_section_d_.section.md#style)
* [textSetting](_pages_section_d_.section.md#textsetting)
* [timeSetting](_pages_section_d_.section.md#timesetting)
* [videoSetting](_pages_section_d_.section.md#videosetting)


###  booleanSetting

▸ **booleanSetting**(`id`: string): *[BooleanSetting](_pages_boolean_setting_d_.booleansetting.md)*

Creates a new boolean setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[BooleanSetting](_pages_boolean_setting_d_.booleansetting.md)*

___

###  decimalSetting

▸ **decimalSetting**(`id`: string): *[DecimalSetting](_pages_decimal_setting_d_.decimalsetting.md)*

Creates a new decimal setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[DecimalSetting](_pages_decimal_setting_d_.decimalsetting.md)*

___

###  defaultRequired

▸ **defaultRequired**(`id`: string): *[Section](_pages_section_d_.section.md)*

Specifies that all settings in the session should default to being required

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[Section](_pages_section_d_.section.md)*

___

###  deviceSetting

▸ **deviceSetting**(`id`: string): *[DeviceSetting](_pages_device_setting_d_.devicesetting.md)*

Creates a new device setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[DeviceSetting](_pages_device_setting_d_.devicesetting.md)*

___

###  emailSetting

▸ **emailSetting**(`id`: string): *[EmailSetting](_pages_email_setting_d_.emailsetting.md)*

Creates a new email setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[EmailSetting](_pages_email_setting_d_.emailsetting.md)*

___

###  enumSetting

▸ **enumSetting**(`id`: string): *[EnumSetting](_pages_enum_setting_d_.enumsetting.md)*

Creates a new enumerated list setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[EnumSetting](_pages_enum_setting_d_.enumsetting.md)*

___

###  hidden

▸ **hidden**(`id`: string): *[Section](_pages_section_d_.section.md)*

Specifies that the section should initially be hidden

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[Section](_pages_section_d_.section.md)*

___

###  hideable

▸ **hideable**(`id`: string): *[Section](_pages_section_d_.section.md)*

Specifies that the section should be able to be hidden (though not initially hidden)

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[Section](_pages_section_d_.section.md)*

___

###  imageSetting

▸ **imageSetting**(`id`: string): *[ImageSetting](_pages_image_setting_d_.imagesetting.md)*

Creates a new image setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[ImageSetting](_pages_image_setting_d_.imagesetting.md)*

___

###  linkSetting

▸ **linkSetting**(`id`: string): *[LinkSetting](_pages_link_setting_d_.linksetting.md)*

Creates a new link setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[LinkSetting](_pages_link_setting_d_.linksetting.md)*

___

###  modeSetting

▸ **modeSetting**(`id`: string): *[ModeSetting](_pages_mode_setting_d_.modesetting.md)*

Creates a new mode setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[ModeSetting](_pages_mode_setting_d_.modesetting.md)*

___

###  name

▸ **name**(`id`: string): *[Section](_pages_section_d_.section.md)*

Sets the name (label) of the section. Normally not set if the i18n framework is being used

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[Section](_pages_section_d_.section.md)*

___

###  numberSetting

▸ **numberSetting**(`id`: string): *[NumberSetting](_pages_number_setting_d_.numbersetting.md)*

Creates a new number setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[NumberSetting](_pages_number_setting_d_.numbersetting.md)*

___

###  oauthSetting

▸ **oauthSetting**(`id`: string): *[OAuthSetting](_pages_oauth_setting_d_.oauthsetting.md)*

Creates a new OAuth2 setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[OAuthSetting](_pages_oauth_setting_d_.oauthsetting.md)*

___

###  pageSetting

▸ **pageSetting**(`id`: string): *[PageSetting](_pages_page_setting_d_.pagesetting.md)*

Creates a new page link setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[PageSetting](_pages_page_setting_d_.pagesetting.md)*

___

###  paragraphSetting

▸ **paragraphSetting**(`id`: string): *[ParagraphSetting](_pages_paragraph_setting_d_.paragraphsetting.md)*

Creates a new paragraph setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[ParagraphSetting](_pages_paragraph_setting_d_.paragraphsetting.md)*

___

###  passwordSetting

▸ **passwordSetting**(`id`: string): *[PasswordSetting](_pages_password_setting_d_.passwordsetting.md)*

Creates a new password setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[PasswordSetting](_pages_password_setting_d_.passwordsetting.md)*

___

###  phoneSetting

▸ **phoneSetting**(`id`: string): *[PhoneSetting](_pages_phone_setting_d_.phonesetting.md)*

Creates a new phone setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[PhoneSetting](_pages_phone_setting_d_.phonesetting.md)*

___

###  sceneSetting

▸ **sceneSetting**(`id`: string): *[SceneSetting](_pages_scene_setting_d_.scenesetting.md)*

Creates a new scene setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[SceneSetting](_pages_scene_setting_d_.scenesetting.md)*

___

###  securitySetting

▸ **securitySetting**(`id`: string): *[SecuritySetting](_pages_security_setting_d_.securitysetting.md)*

Creates a new security system setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[SecuritySetting](_pages_security_setting_d_.securitysetting.md)*

___

###  soundSetting

▸ **soundSetting**(`id`: string): *[SoundSetting](_pages_sound_setting_d_.soundsetting.md)*

Creates a new sound setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[SoundSetting](_pages_sound_setting_d_.soundsetting.md)*

___

###  style

▸ **style**(`id`: string): *[Section](_pages_section_d_.section.md)*

Sets the session style

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[Section](_pages_section_d_.section.md)*

___

###  textSetting

▸ **textSetting**(`id`: string): *[TextSetting](_pages_text_setting_d_.textsetting.md)*

Creates a new text setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[TextSetting](_pages_text_setting_d_.textsetting.md)*

___

###  timeSetting

▸ **timeSetting**(`id`: string): *[TimeSetting](_pages_time_setting_d_.timesetting.md)*

Creates a new time setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[TimeSetting](_pages_time_setting_d_.timesetting.md)*

___

###  videoSetting

▸ **videoSetting**(`id`: string): *[VideoSetting](_pages_video_setting_d_.videosetting.md)*

Creates a new video setting

**Parameters:**

Name | Type |
------ | ------ |
`id` | string |

**Returns:** *[VideoSetting](_pages_video_setting_d_.videosetting.md)*

