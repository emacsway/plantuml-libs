# AwsShieldShieldAdvanced
```text
elements/aws/SecurityIdentityCompliance/AwsShieldShieldAdvanced
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsShieldShieldAdvanced icon](../../../icons/aws/SecurityIdentityCompliance/AwsShieldShieldAdvanced.png) | ![AwsShieldShieldAdvanced element](AwsShieldShieldAdvanced.element.png) | ![AwsShieldShieldAdvanced card](AwsShieldShieldAdvanced.card.png) |
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

' loads the AwsShieldShieldAdvanced element
include('elements/aws/SecurityIdentityCompliance/AwsShieldShieldAdvanced')
AwsShieldShieldAdvanced('element', 'Shield Shield Advanced', 'an optional tech field')
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

' loads the AwsShieldShieldAdvanced element
include('elements/aws/SecurityIdentityCompliance/AwsShieldShieldAdvanced')
AwsShieldShieldAdvanced('element', 'Shield Shield Advanced', 'an optional tech field')
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

' loads the AwsShieldShieldAdvanced card
include('elements/aws/SecurityIdentityCompliance/AwsShieldShieldAdvanced')
AwsShieldShieldAdvancedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsShieldShieldAdvanced card
include('elements/aws/SecurityIdentityCompliance/AwsShieldShieldAdvanced')
AwsShieldShieldAdvancedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
