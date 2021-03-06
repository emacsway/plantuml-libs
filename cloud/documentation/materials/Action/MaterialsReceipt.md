# MaterialsReceipt
```text
elements/materials/Action/MaterialsReceipt
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsReceipt icon](../../../icons/materials/Action/MaterialsReceipt.png) | ![MaterialsReceipt element](MaterialsReceipt.element.png) | ![MaterialsReceipt card](MaterialsReceipt.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsReceipt element
include('elements/materials/Action/MaterialsReceipt')
MaterialsReceipt('element', 'Receipt', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsReceipt element
include('elements/materials/Action/MaterialsReceipt')
MaterialsReceipt('element', 'Receipt', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsReceipt card
include('elements/materials/Action/MaterialsReceipt')
MaterialsReceiptCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsReceipt card
include('elements/materials/Action/MaterialsReceipt')
MaterialsReceiptCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
