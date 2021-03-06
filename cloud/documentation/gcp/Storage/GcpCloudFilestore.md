# GcpCloudFilestore
```text
elements/gcp/Storage/GcpCloudFilestore
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![GcpCloudFilestore icon](../../../icons/gcp/Storage/GcpCloudFilestore.png) | ![GcpCloudFilestore element](GcpCloudFilestore.element.png) | ![GcpCloudFilestore card](GcpCloudFilestore.card.png) |
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

' loads the GcpCloudFilestore element
include('elements/gcp/Storage/GcpCloudFilestore')
GcpCloudFilestore('element', 'Cloud Filestore', 'an optional tech field')
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

' loads the GcpCloudFilestore element
include('elements/gcp/Storage/GcpCloudFilestore')
GcpCloudFilestore('element', 'Cloud Filestore', 'an optional tech field')
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

' loads the GcpCloudFilestore card
include('elements/gcp/Storage/GcpCloudFilestore')
GcpCloudFilestoreCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GcpCloudFilestore card
include('elements/gcp/Storage/GcpCloudFilestore')
GcpCloudFilestoreCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
