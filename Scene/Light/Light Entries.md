# Light Data Entries

## Light2 Entry
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "Light2" |
| LightNum | Integer variable. The ID of the light in relation to other entries of the same type. |
| Enable | Boolean variable. True if the light is enabled. |
| IsSpecular | Boolean variable. True if the light supports specular lighting. |
| Color | Color variable. The color of the light. |
| Dir | Vector variable. The direction of the light. |

## AmbLight Entry
| Expected Components | Description |
| --- | --- |
| __Type | Should always return "AmbLight2" |
| LightNum | Integer variable. The ID of the light in relation to other entries of the same type. |
| Color | Color variable. The color of the light. |
