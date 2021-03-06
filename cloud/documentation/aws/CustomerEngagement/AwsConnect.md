# AwsConnect
```text
elements/aws/CustomerEngagement/AwsConnect
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsConnect icon](../../../icons/aws/CustomerEngagement/AwsConnect.png) | ![AwsConnect element](AwsConnect.element.png) | ![AwsConnect card](AwsConnect.card.png) |
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

' loads the AwsConnect element
include('elements/aws/CustomerEngagement/AwsConnect')
AwsConnect('element', 'Connect', 'an optional tech field')
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

' loads the AwsConnect element
include('elements/aws/CustomerEngagement/AwsConnect')
AwsConnect('element', 'Connect', 'an optional tech field')
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

' loads the AwsConnect card
include('elements/aws/CustomerEngagement/AwsConnect')
AwsConnectCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsConnect card
include('elements/aws/CustomerEngagement/AwsConnect')
AwsConnectCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
