# AzureUdfFunction
```text
elements/azure/FlatSymbols/CneEnterprise/AzureUdfFunction
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureUdfFunction icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureUdfFunction.png) | ![AzureUdfFunction element](AzureUdfFunction.element.png) | ![AzureUdfFunction card](AzureUdfFunction.card.png) |
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

' loads the AzureUdfFunction element
include('elements/azure/FlatSymbols/CneEnterprise/AzureUdfFunction')
AzureUdfFunction('element', 'Udf Function', 'an optional tech field')
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

' loads the AzureUdfFunction element
include('elements/azure/FlatSymbols/CneEnterprise/AzureUdfFunction')
AzureUdfFunction('element', 'Udf Function', 'an optional tech field')
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

' loads the AzureUdfFunction card
include('elements/azure/FlatSymbols/CneEnterprise/AzureUdfFunction')
AzureUdfFunctionCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureUdfFunction card
include('elements/azure/FlatSymbols/CneEnterprise/AzureUdfFunction')
AzureUdfFunctionCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
