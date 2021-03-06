# AwsAppConfig
```text
elements/aws/ManagementGovernance/AwsAppConfig
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsAppConfig icon](../../../icons/aws/ManagementGovernance/AwsAppConfig.png) | ![AwsAppConfig element](AwsAppConfig.element.png) | ![AwsAppConfig card](AwsAppConfig.card.png) |
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
include('styles/aws')

' loads the AwsAppConfig element
include('elements/aws/ManagementGovernance/AwsAppConfig')
AwsAppConfig('element', 'App Config', 'an optional tech field')
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
include('styles/aws')

' loads the AwsAppConfig element
include('elements/aws/ManagementGovernance/AwsAppConfig')
AwsAppConfig('element', 'App Config', 'an optional tech field')
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
include('styles/aws')

' loads the AwsAppConfig card
include('elements/aws/ManagementGovernance/AwsAppConfig')
AwsAppConfigCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/aws')

' loads the AwsAppConfig card
include('elements/aws/ManagementGovernance/AwsAppConfig')
AwsAppConfigCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
