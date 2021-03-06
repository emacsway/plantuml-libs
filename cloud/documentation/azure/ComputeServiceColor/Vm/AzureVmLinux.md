# AzureVmLinux
```text
elements/azure/ComputeServiceColor/Vm/AzureVmLinux
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureVmLinux icon](../../../../icons/azure/ComputeServiceColor/Vm/AzureVmLinux.png) | ![AzureVmLinux element](AzureVmLinux.element.png) | ![AzureVmLinux card](AzureVmLinux.card.png) |
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

' loads the AzureVmLinux element
include('elements/azure/ComputeServiceColor/Vm/AzureVmLinux')
AzureVmLinux('element', 'Vm Linux', 'an optional tech field')
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

' loads the AzureVmLinux element
include('elements/azure/ComputeServiceColor/Vm/AzureVmLinux')
AzureVmLinux('element', 'Vm Linux', 'an optional tech field')
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

' loads the AzureVmLinux card
include('elements/azure/ComputeServiceColor/Vm/AzureVmLinux')
AzureVmLinuxCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureVmLinux card
include('elements/azure/ComputeServiceColor/Vm/AzureVmLinux')
AzureVmLinuxCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
