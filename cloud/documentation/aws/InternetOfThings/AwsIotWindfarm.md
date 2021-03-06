# AwsIotWindfarm
```text
elements/aws/InternetOfThings/AwsIotWindfarm
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsIotWindfarm icon](../../../icons/aws/InternetOfThings/AwsIotWindfarm.png) | ![AwsIotWindfarm element](AwsIotWindfarm.element.png) | ![AwsIotWindfarm card](AwsIotWindfarm.card.png) |
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

' loads the AwsIotWindfarm element
include('elements/aws/InternetOfThings/AwsIotWindfarm')
AwsIotWindfarm('element', 'Iot Windfarm', 'an optional tech field')
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

' loads the AwsIotWindfarm element
include('elements/aws/InternetOfThings/AwsIotWindfarm')
AwsIotWindfarm('element', 'Iot Windfarm', 'an optional tech field')
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

' loads the AwsIotWindfarm card
include('elements/aws/InternetOfThings/AwsIotWindfarm')
AwsIotWindfarmCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsIotWindfarm card
include('elements/aws/InternetOfThings/AwsIotWindfarm')
AwsIotWindfarmCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
