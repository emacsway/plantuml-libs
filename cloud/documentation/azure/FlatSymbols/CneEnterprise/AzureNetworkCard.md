# AzureNetworkCard
```text
elements/azure/FlatSymbols/CneEnterprise/AzureNetworkCard
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureNetworkCard icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureNetworkCard.png) | ![AzureNetworkCard element](AzureNetworkCard.element.png) | ![AzureNetworkCard card](AzureNetworkCard.card.png) |
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

' loads the AzureNetworkCard element
include('elements/azure/FlatSymbols/CneEnterprise/AzureNetworkCard')
AzureNetworkCard('element', 'Network Card', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureNetworkCard element
include('elements/azure/FlatSymbols/CneEnterprise/AzureNetworkCard')
AzureNetworkCard('element', 'Network Card', 'an optional tech field')
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

' loads the AzureNetworkCard card
include('elements/azure/FlatSymbols/CneEnterprise/AzureNetworkCard')
AzureNetworkCardCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureNetworkCard card
include('elements/azure/FlatSymbols/CneEnterprise/AzureNetworkCard')
AzureNetworkCardCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```