# AwsMigrationHub
```text
elements/aws/MigrationTransfer/AwsMigrationHub
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsMigrationHub icon](../../../icons/aws/MigrationTransfer/AwsMigrationHub.png) | ![AwsMigrationHub element](AwsMigrationHub.element.png) | ![AwsMigrationHub card](AwsMigrationHub.card.png) |
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

' loads the AwsMigrationHub element
include('elements/aws/MigrationTransfer/AwsMigrationHub')
AwsMigrationHub('element', 'Migration Hub', 'an optional tech field')
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

' loads the AwsMigrationHub element
include('elements/aws/MigrationTransfer/AwsMigrationHub')
AwsMigrationHub('element', 'Migration Hub', 'an optional tech field')
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

' loads the AwsMigrationHub card
include('elements/aws/MigrationTransfer/AwsMigrationHub')
AwsMigrationHubCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsMigrationHub card
include('elements/aws/MigrationTransfer/AwsMigrationHub')
AwsMigrationHubCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
