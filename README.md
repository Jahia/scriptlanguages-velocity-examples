# scriptlanguages-velocity-examples

A simple example on how to use Velocity as a scripting language for Jahia DX views.
All standard Jahia DX variables are exposed as Velocity variables, you can display node contents,
etc. For more information about Jahia Digital Experience Manager (DX), please go to: 
https://www.jahia.com/platform/digital-experience-manager

## Requirements
- Jahia 7.2.0.0 or more recent
- Maven 3.0+ for module compilation
- JDK 7+

## Usage

1. Compile the whole project using : mvn clean install
2. Deploy the `target/scriptlanguages-velocity-example*.jar` module
3. In Edit mode, add a Basic Content -> Velocity node rendering content node, and enter a value for the velocityText property.
The value of this property will be displayed by the node template written in Velocity.

## Example template

You will find an example template in the following directory : `src/main/resources/jnt_velocityNode/html/velocityNode.vm`