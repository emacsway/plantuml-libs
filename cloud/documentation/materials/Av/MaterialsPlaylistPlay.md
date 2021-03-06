# MaterialsPlaylistPlay
```text
elements/materials/Av/MaterialsPlaylistPlay
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsPlaylistPlay icon](../../../icons/materials/Av/MaterialsPlaylistPlay.png) | ![MaterialsPlaylistPlay element](MaterialsPlaylistPlay.element.png) | ![MaterialsPlaylistPlay card](MaterialsPlaylistPlay.card.png) |
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
include('styles/materials')

' loads the MaterialsPlaylistPlay element
include('elements/materials/Av/MaterialsPlaylistPlay')
MaterialsPlaylistPlay('element', 'Playlist Play', 'an optional tech field')
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
include('styles/materials')

' loads the MaterialsPlaylistPlay element
include('elements/materials/Av/MaterialsPlaylistPlay')
MaterialsPlaylistPlay('element', 'Playlist Play', 'an optional tech field')
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
include('styles/materials')

' loads the MaterialsPlaylistPlay card
include('elements/materials/Av/MaterialsPlaylistPlay')
MaterialsPlaylistPlayCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/materials')

' loads the MaterialsPlaylistPlay card
include('elements/materials/Av/MaterialsPlaylistPlay')
MaterialsPlaylistPlayCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
