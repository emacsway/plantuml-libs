# MaterialsCardMembership
```text
elements/materials/Action/MaterialsCardMembership
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsCardMembership icon](../../../icons/materials/Action/MaterialsCardMembership.png) | ![MaterialsCardMembership element](MaterialsCardMembership.element.png) | ![MaterialsCardMembership card](MaterialsCardMembership.card.png) |
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

' loads the MaterialsCardMembership element
include('elements/materials/Action/MaterialsCardMembership')
MaterialsCardMembership('element', 'Card Membership', 'an optional tech field')
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

' loads the MaterialsCardMembership element
include('elements/materials/Action/MaterialsCardMembership')
MaterialsCardMembership('element', 'Card Membership', 'an optional tech field')
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

' loads the MaterialsCardMembership card
include('elements/materials/Action/MaterialsCardMembership')
MaterialsCardMembershipCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsCardMembership card
include('elements/materials/Action/MaterialsCardMembership')
MaterialsCardMembershipCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
