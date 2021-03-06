# GcpAiHub
```text
elements/gcp/AiAndMachineLearning/GcpAiHub
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![GcpAiHub icon](../../../icons/gcp/AiAndMachineLearning/GcpAiHub.png) | ![GcpAiHub element](GcpAiHub.element.png) | ![GcpAiHub card](GcpAiHub.card.png) |
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
include('styles/gcp')

' loads the GcpAiHub element
include('elements/gcp/AiAndMachineLearning/GcpAiHub')
GcpAiHub('element', 'Ai Hub', 'an optional tech field')
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
include('styles/gcp')

' loads the GcpAiHub element
include('elements/gcp/AiAndMachineLearning/GcpAiHub')
GcpAiHub('element', 'Ai Hub', 'an optional tech field')
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
include('styles/gcp')

' loads the GcpAiHub card
include('elements/gcp/AiAndMachineLearning/GcpAiHub')
GcpAiHubCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/gcp')

' loads the GcpAiHub card
include('elements/gcp/AiAndMachineLearning/GcpAiHub')
GcpAiHubCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
