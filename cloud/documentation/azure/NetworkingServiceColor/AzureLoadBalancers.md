# AzureLoadBalancers
```text
elements/azure/NetworkingServiceColor/AzureLoadBalancers
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureLoadBalancers icon](../../../icons/azure/NetworkingServiceColor/AzureLoadBalancers.png) | ![AzureLoadBalancers element](AzureLoadBalancers.element.png) | ![AzureLoadBalancers card](AzureLoadBalancers.card.png) |
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

' loads the AzureLoadBalancers element
include('elements/azure/NetworkingServiceColor/AzureLoadBalancers')
AzureLoadBalancers('element', 'Load Balancers', 'an optional tech field')
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

' loads the AzureLoadBalancers element
include('elements/azure/NetworkingServiceColor/AzureLoadBalancers')
AzureLoadBalancers('element', 'Load Balancers', 'an optional tech field')
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

' loads the AzureLoadBalancers card
include('elements/azure/NetworkingServiceColor/AzureLoadBalancers')
AzureLoadBalancersCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureLoadBalancers card
include('elements/azure/NetworkingServiceColor/AzureLoadBalancers')
AzureLoadBalancersCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
