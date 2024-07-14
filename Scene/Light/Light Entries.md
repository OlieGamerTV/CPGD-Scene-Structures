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

## Examples

### Light2 Entry Example
```
Light:
      __Type: Light2
      LightNum: 1
      Enable: 1
      IsSpecular: 0
      Color:
        __Type: Color
        R: 57
        G: 50
        B: 44
      Dir:
        __Type: Vector
        X: 0.908720
        Y: 0.222132
        Z: -0.353391
```

### AmbLight Entry Example
```
AmbLight:
      __Type: AmbLight2
      LightNum: 1
      Color:
        __Type: Color
        R: 200
        G: 200
        B: 255
```
