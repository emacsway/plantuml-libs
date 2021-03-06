# GcpGroupExternalInfrastructure3rdParty
| Example | Resource |
| :-: | --- |
| ![GcpGroupExternalInfrastructure3rdParty group](GcpGroupExternalInfrastructure3rdParty.group.png) | `groups/gcp/GcpGroupExternalInfrastructure3rdParty` |
## Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/gcp')

' loads the GcpGroupExternalInfrastructure3rdParty group
include('groups/gcp/GcpGroupExternalInfrastructure3rdParty')
GcpGroupExternalInfrastructure3rdParty('element', 'External infrastructure 3rd party', 'an optional tech field')
@enduml
```
## Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../"

' loads the library
!include ../../library.puml

' loads the style
include('styles/gcp')

' loads the GcpGroupExternalInfrastructure3rdParty group
include('groups/gcp/GcpGroupExternalInfrastructure3rdParty')
GcpGroupExternalInfrastructure3rdParty('element', 'External infrastructure 3rd party', 'an optional tech field')
@enduml
```
