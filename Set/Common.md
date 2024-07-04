# Main .set Data
This will list the names of the main entries and components you will find inside of .set files.

## Common Data Types
| Name | Description |
| --- | --- |
| SetItemRoot | The root of the set file, every other entry goes in here. |
| SetData | A SetData entry. Used for creating a location point for use in other areas like scripting. |
| Vector | A Vector entry, comprised of three float entries for X, Y and Z. |
| Attr | An Attribution entry, comprised of a hex value, commonly 0x00000000. |
| UserData | An UserData entry, comprised of three byte entries for three data points. |

## Common Components
| Name | Description |
| --- | --- |
| __Type | The data type of the entry. String variable and required for every entry. |
| SetName | The unique name of the entry. |

## Examples

### Example Set Entry
```
SetItemRoot:
  Locater:
    __Type: SetData
    SetName: SET_Demo_ed
    Trans:
      __Type: Vector
      X: 0.000000
      Y: 0.000000
      Z: 0.000000
    Rot:
      __Type: Vector
      X: 0.000000
      Y: 0.000000
      Z: 0.000000
    Scale:
      __Type: Vector
      X: 1.000000
      Y: 1.000000
      Z: 1.000000
    Attr:
      __Type: Attr
      Attr: 0x00000000
    UserData:
      __Type: UserData
      Data1: 1
      Data2: 0
      Data3: 0
  Locater:
    __Type: SetData
    SetName: SET_Demo_ed_eff00
    Trans:
      __Type: Vector
      X: 10.000000
      Y: 0.000000
      Z: -100.000000
    Rot:
      __Type: Vector
      X: 0.000000
      Y: 0.000000
      Z: 0.000000
    Scale:
      __Type: Vector
      X: 1.000000
      Y: 1.000000
      Z: 1.000000
    Attr:
      __Type: Attr
      Attr: 0x00000000
    UserData:
      __Type: UserData
      Data1: 1
      Data2: 0
      Data3: 0
```
