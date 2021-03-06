# AwsDatabaseMigrationService
```text
elements/aws/Database/AwsDatabaseMigrationService
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsDatabaseMigrationService icon](../../../icons/aws/Database/AwsDatabaseMigrationService.png) | ![AwsDatabaseMigrationService element](AwsDatabaseMigrationService.element.png) | ![AwsDatabaseMigrationService card](AwsDatabaseMigrationService.card.png) |
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

' loads the AwsDatabaseMigrationService element
include('elements/aws/Database/AwsDatabaseMigrationService')
AwsDatabaseMigrationService('element', 'Database Migration Service', 'an optional tech field')
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

' loads the AwsDatabaseMigrationService element
include('elements/aws/Database/AwsDatabaseMigrationService')
AwsDatabaseMigrationService('element', 'Database Migration Service', 'an optional tech field')
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

' loads the AwsDatabaseMigrationService card
include('elements/aws/Database/AwsDatabaseMigrationService')
AwsDatabaseMigrationServiceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsDatabaseMigrationService card
include('elements/aws/Database/AwsDatabaseMigrationService')
AwsDatabaseMigrationServiceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
