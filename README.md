# Enums
Enumerations



**Enum**

```
enum exampleEnum {
case case1
case case2
}
let enumConstant = exampleEnum.case1
```
<br />
<br />

```
enum EnumAssociated {
    case first
    case second(second: String)
    case third(third: String)
    case fourth(fourth: Int)
}
let enumAssociated = EnumAssociated.second(second: "second")
```
