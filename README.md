# Functional Safety of a Lane Assistance System

This project aims to create major functional safety documents for a Lane Assistance System in ADAS, following the Functional safety : ISO 26262. ISO 26262 is an international standard for functional safety on electrical and/or electronic system in production automobiles defined by the International Organization for Standardization (ISO).

The Lane Assistance item alerts the driver that the vehicle has accidentally departed it’s lane and attempts to steer the vehicle back on track towards the centre of the lane, to prevent accidents.

The Lane Assistance System will have two functions:
  1.	**Lane departure warning:**
The lane departure warning function shall apply an oscillating steering torque to provide the driver a haptic feedback.
  2.	**Lane keeping assistance:**
The lane keeping assistance function shall apply the steering torque when active towards the centre of the lane,  in order to stay in the ego lane.

The documentation consists on the following documents

## Description of Documents
The included documents are:
 *  [Safety Plan](https://github.com/jumanamp/CarND-Functional-Safety-Project/blob/master/FuSa_Docs/01_SafetyPlan_LaneAssistance.pdf)
 *  [Hazard Analysis and Risk Assessment](https://github.com/jumanamp/CarND-Functional-Safety-Project/blob/master/FuSa_Docs/02_HazardAnalysisAndRiskAssessment.pdf)
 *  [Functional Safety Concept](https://github.com/jumanamp/CarND-Functional-Safety-Project/blob/master/FuSa_Docs/03_FunctionalSafetyConcept_LaneAssistance.pdf)
 *  [Technical Safety Concept](https://github.com/jumanamp/CarND-Functional-Safety-Project/blob/master/FuSa_Docs/04_TechnicalSafetyConcept_LaneAssistance.pdf)
 *  [Software Requirements](https://github.com/jumanamp/CarND-Functional-Safety-Project/blob/master/FuSa_Docs/05_SoftwareRequirementsAndArchitecture_LaneAssistance.pdf)


### Purpose of each document
**Safety Plan:**

Provide an overall framework for the Lane Assistance item, and to assign roles and responsibilities for functional safety for this item.

<p align="center">
<img width="1000" height="500" src="Architecture_Diagrams/graphic_asset_2.png">
</p>
<p align="center">
<em>High level System Architecture</em>
</p>



**Hazard Analysis and Risk Assessment:**

Analyse at least four potential hazardous situations and assess their risk. Then safety goals are derived for each hazardous situation.

**Functional Safety Concept**

Functional safety concept documents the high-level system safety requirements
from the general functionality of the item. The identified requirements are then attributed to the various parts of the item architecture.

<p align="center">
<img width="1000" height="500" src="Architecture_Diagrams/graphic_asset_3.png">
</p>
<p align="center">
<em>System Architecture at Functional Safety Concept Level</em>
</p>

**Technical Safety Concept**

Technical safety concept is to refine the functional safety requirements
established in the functional safety concept into technical safety requirements. As a part of product development, technical safety concept involves:

* Turning functional safety requirements into technical safety requirements.
* Allocating technical safety requirements to the system architecture.

<p align="center">
<img width="1000" height="500" src="Architecture_Diagrams/graphic_asset_4.png">
</p>
<p align="center">
<em>System Architecture at Technical Safety Concept Level</em>
</p>



**Software Requirements**

Derive new requirements for the software of the Lane Assistance item at a component level to identify potential issues in the software design that could lead to safety violations.

<p align="center">
<img width="1000" height="500" src="Architecture_Diagrams/graphic_asset_1.png">
</p>
<p align="center">
<em>System Software Architecture</em>
</p>
