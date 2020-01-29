- [Introduction](#org74c4463)
  - [Motivation & Goals](#org79d08ed)
  - [Product concept](#orgb032d50)
- [Repository Struct](#org79cf582)



<a id="org74c4463"></a>

# Introduction

The present work, within the scope of the curricular unit of Laboratórios e Práticas Integradas I, consists in the project of the development of a product, namely, a pedagogic kit about automatic control. The theme selected by the project’s team was a conveyor belt, showcasing the velocity control of the load transported by the conveyor, independently from its mass. In this section are presented the project’s motivation and goals, the product concept, the project planning and the document organisation.


<a id="org79d08ed"></a>

## Motivation & Goals

The main goal of the project is to develop a didactic kit to ease the learning of automatic control with the following characteristics:

-   Low complexity — to be an useful tool in a wide range of ages;
-   Subject comprehensive — to be able to integrate topics on several domains of electronics engineering, with particular focus on the curricular units taught on the fifth semester of the MIEEIC;
-   affordable: to allow replication and usage by any social stratum;
-   safe: without posing any danger for the user well-being and the surrounding ones, as well as not causing any materials.
-   didactic: fostering the learning on the topics in a practical and fun way;
-   pedagogic: documenting the project to allow replication by any individual in a simple and convenient manner.


<a id="orgb032d50"></a>

## Product concept

The envisioned product consists of a didactic kit to enable the learning about automatic control. For this purpose, it focuses on a simple control problem — load movement control (velocity and direction) in a conveyor, similar to the ones present at the airports for user transportation. However, it will allow the user to experiment several types of controllers and the effect of each one in the system to control.

The goal is to control the velocity of the conveyor, virtually independently of its load. Thus, the addition or removal of load (e.g. passengers) should not affect the velocity of the conveyor. Additionally, the transportation direction must also be modifiable.

Furthermore, a laboratory guide is to be produced, similar to the ones used in Laboratórios e Práticas Integradas I (LPI1).


<a id="org79cf582"></a>

# Repository Struct

-   Control Guidebook: contains the guidebook created from the project
-   Datasheets: contains the relevant electronics datasheets
-   Manuals: contains the assembly manual and the user manual
-   Mechanics: contains the mechanics parts (STL format) for 3D printing:
-   PCB: printed circuit board - Bill of Materials, Schematics and Layouts
-   Simulations: control simulations
-   Tests: relevant tests performed
