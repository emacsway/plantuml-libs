# MaterialsNotInterested
```text
elements/materials/Av/MaterialsNotInterested
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsNotInterested icon](../../../icons/materials/Av/MaterialsNotInterested.png) | ![MaterialsNotInterested element](MaterialsNotInterested.element.png) | ![MaterialsNotInterested card](MaterialsNotInterested.card.png) |
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

' loads the MaterialsNotInterested element
include('elements/materials/Av/MaterialsNotInterested')
MaterialsNotInterested('element', 'Not Interested', 'an optional tech field')
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

' loads the MaterialsNotInterested element
include('elements/materials/Av/MaterialsNotInterested')
MaterialsNotInterested('element', 'Not Interested', 'an optional tech field')
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

' loads the MaterialsNotInterested card
include('elements/materials/Av/MaterialsNotInterested')
MaterialsNotInterestedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsNotInterested card
include('elements/materials/Av/MaterialsNotInterested')
MaterialsNotInterestedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
