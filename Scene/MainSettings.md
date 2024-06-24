# Main Settings Data Entries

## BloomSetting Entry
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "BloomSetting". |
| ProcType | ??? variable. No idea what this does. |
| Border | ??? variable. No idea what this does. |
| AddShift | ??? variable. No idea what this does. |
| SoftShiftX | Float variable. No idea what this does. |
| SoftShiftY | Float variable. No idea what this does. |
| Color | Color variable. The color of the light. |

## FogSettings Entry
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "FogSetting". |
| FogNum | Integer variable. No idea what this does. |
| FogType | Integer variable. No idea what this does. |
| ZStart | Float variable. The start point for the fog. |
| ZEnd | Float variable. The end point for the fog. |
| Color | Color variable. The color of the light. |

## HubCameraSetting Entry
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "HubCameraSetting". |
| TargetOffsetY | Float variable. The distance from origin on the Y axis. |
| Angle | Float variable. The angle of the camera. |
| Speed | Float variable. The speed of the camera. |
| Fovy | Float variable. The FOV of the camera. |
| Near | Float variable. The min rendering distance of the camera. |
| Far | Float variable. The max rendering distance of the camera. |
| LimitDistMin | Float variable. The min distance that the camera can go on the Z axis. |
| LimitDistMax | Float variable. The max distance that the camera can go on the Z axis. |
| LimitLeft | Float variable. The min distance that the camera can go on the X axis. |
| LimitRight | Float variable. The max distance that the camera can go on the X axis. |
| LimitUp | Float variable. The min distance that the camera can go on the Y axis. |
| LimitDown | Float variable. The max distance that the camera can go on the Y axis. |
| LimitBaseZ | Float variable. The base distance that the camera is at on the Z axis. |

## LightSetting Entry
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "LightSetting". |
| ... | All the light entries for the scene. |
