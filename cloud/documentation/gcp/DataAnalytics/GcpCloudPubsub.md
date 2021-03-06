# GcpCloudPubsub
```text
elements/gcp/DataAnalytics/GcpCloudPubsub
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![GcpCloudPubsub icon](../../../icons/gcp/DataAnalytics/GcpCloudPubsub.png) | ![GcpCloudPubsub element](GcpCloudPubsub.element.png) | ![GcpCloudPubsub card](GcpCloudPubsub.card.png) |
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

' loads the GcpCloudPubsub element
include('elements/gcp/DataAnalytics/GcpCloudPubsub')
GcpCloudPubsub('element', 'Cloud Pubsub', 'an optional tech field')
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

' loads the GcpCloudPubsub element
include('elements/gcp/DataAnalytics/GcpCloudPubsub')
GcpCloudPubsub('element', 'Cloud Pubsub', 'an optional tech field')
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

' loads the GcpCloudPubsub card
include('elements/gcp/DataAnalytics/GcpCloudPubsub')
GcpCloudPubsubCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GcpCloudPubsub card
include('elements/gcp/DataAnalytics/GcpCloudPubsub')
GcpCloudPubsubCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
