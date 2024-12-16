# piano

A piano from javafx samples

## How to

Install openjfx sdk to be used as a module (beware windows vs linux)


### Build WSL

To build : under wsl, install the linux openjfx sdk 
Ex : 
piano
 |---> lib lib/javafx-sdk-23.0.1/lib/
 |---> src
 |---> pom.xml


### Run : windows

Does not run under wsl
Under windows, example
- install the windows openjfx sdk (not the linux one !!!) if not present in jdk
(java --list-modules)

- run with module path

PS C:\Program Files\BellSoft\LibericaJDK-21\bin>
./java --module-path ..\lib\javafx-sdk-23.0.1\lib --add-modules javafx.controls -jar '\\wsl$\ubuntu\home\ubu\piano\piano\target\piano-1.0-SNAPSHOT.ja
