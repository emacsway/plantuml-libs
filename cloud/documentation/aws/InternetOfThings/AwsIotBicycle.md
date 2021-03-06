# AwsIotBicycle
```text
elements/aws/InternetOfThings/AwsIotBicycle
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsIotBicycle icon](../../../icons/aws/InternetOfThings/AwsIotBicycle.png) | ![AwsIotBicycle element](AwsIotBicycle.element.png) | ![AwsIotBicycle card](AwsIotBicycle.card.png) |
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

' loads the AwsIotBicycle element
include('elements/aws/InternetOfThings/AwsIotBicycle')
AwsIotBicycle('element', 'Iot Bicycle', 'an optional tech field')
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

' loads the AwsIotBicycle element
include('elements/aws/InternetOfThings/AwsIotBicycle')
AwsIotBicycle('element', 'Iot Bicycle', 'an optional tech field')
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

' loads the AwsIotBicycle card
include('elements/aws/InternetOfThings/AwsIotBicycle')
AwsIotBicycleCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsIotBicycle card
include('elements/aws/InternetOfThings/AwsIotBicycle')
AwsIotBicycleCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
