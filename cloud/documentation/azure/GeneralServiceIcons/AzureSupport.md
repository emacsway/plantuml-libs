# AzureSupport
```text
elements/azure/GeneralServiceIcons/AzureSupport
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureSupport icon](../../../icons/azure/GeneralServiceIcons/AzureSupport.png) | ![AzureSupport element](AzureSupport.element.png) | ![AzureSupport card](AzureSupport.card.png) |
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

' loads the AzureSupport element
include('elements/azure/GeneralServiceIcons/AzureSupport')
AzureSupport('element', 'Support', 'an optional tech field')
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

' loads the AzureSupport element
include('elements/azure/GeneralServiceIcons/AzureSupport')
AzureSupport('element', 'Support', 'an optional tech field')
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

' loads the AzureSupport card
include('elements/azure/GeneralServiceIcons/AzureSupport')
AzureSupportCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureSupport card
include('elements/azure/GeneralServiceIcons/AzureSupport')
AzureSupportCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
