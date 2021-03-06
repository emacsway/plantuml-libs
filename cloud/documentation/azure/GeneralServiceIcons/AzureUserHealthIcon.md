# AzureUserHealthIcon
```text
elements/azure/GeneralServiceIcons/AzureUserHealthIcon
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureUserHealthIcon icon](../../../icons/azure/GeneralServiceIcons/AzureUserHealthIcon.png) | ![AzureUserHealthIcon element](AzureUserHealthIcon.element.png) | ![AzureUserHealthIcon card](AzureUserHealthIcon.card.png) |
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
include('styles/azure')

' loads the AzureUserHealthIcon element
include('elements/azure/GeneralServiceIcons/AzureUserHealthIcon')
AzureUserHealthIcon('element', 'User Health Icon', 'an optional tech field')
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
include('styles/azure')

' loads the AzureUserHealthIcon element
include('elements/azure/GeneralServiceIcons/AzureUserHealthIcon')
AzureUserHealthIcon('element', 'User Health Icon', 'an optional tech field')
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
include('styles/azure')

' loads the AzureUserHealthIcon card
include('elements/azure/GeneralServiceIcons/AzureUserHealthIcon')
AzureUserHealthIconCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/azure')

' loads the AzureUserHealthIcon card
include('elements/azure/GeneralServiceIcons/AzureUserHealthIcon')
AzureUserHealthIconCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
