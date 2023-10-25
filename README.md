# SW Associate Architecture
## 1. Overview
_**Task 1: Draw the operation and business environment of the system**_

With the aim of solving a problem by a computer, programmers need to understand that problem, then learn a programming language and use it to tells a computer how to solve that problem over and over. But later, problems in real world has been elvolved to be much more complexity and abtract day by day. To adapt with the changes of problem's requirements, it is necessary to draw a bigger picture of how a computer solve a problem and from that, we can find a more general ways to resolve the problem, called Software architecture. It is a research field which make fundamental structure choices for designing a system, shift developer's focus from lines-of-code to coarser-grained architectural elements (software components and connectors) and their overall interconnection structure. A good software architecture can helps the organization to recude cost of developing applications and increase the potential for maintaining and extending the further products.

//TODO: Vẽ sơ đồ ADL hoạt động, từ file -> diagram object -> graphic object

To support architecture-based development, formal modelling notations, analysis and development tools that operate on architectual specifications are needed. Architecture description languages (ADLs) has been proposed as the answer. Generally, an ADL for software development focuses on high-level structure of the overall application to present architect's ideas and thinkings rather than the implementation of any specific source module. ADL can be represent as fews type of diagrams as:
- Component and Connector View
- Deployment View
- Sequence Diagram
- Module View
- Work Assignment View
- Install View

Each diagram consists of multiple entities for architectural representation, called Element. As described in Figure 1, it can be classified into five types:
- Component
- Connector
- System
- Port
- Role

![image](https://github.com/phunm211/SW-Associate-Architecture/assets/19267057/6befa87d-faf9-490b-9900-be01d7ee979d)

For the sake of rendering a diagram into a graphical object to display on a screen, or saving it as a picture, it is required to use a Rendering API. In general, we can provide information of 3D coordinates, and then the graphic pipeline transforms these into colored 2D pixels on the screen. The graphic pipeline can be divided into several steps which can be executed parallelly on GPU. https://learnopengl.com/Getting-started/Hello-Triangle

(On Windows: GLViewport)

In this document, we proposed to design an ADL Framework to support editing and rendering ADL by a Graphic API. The Framework can be specifically implemented on the Windows operating system under a third-party ADL UI Application.

![SystemBoundary drawio](https://github.com/phunm211/SW-Associate-Architecture/assets/19267057/bd13d93e-5e2c-43d4-adf6-3ef7e86a1fec)

//TOD: Stakeholder table
Stakeholder | Interest in architecture

**_Task 2: Define the input and output of the system_**
## 2. Requirements
### 2.1. Functional Requirements

### 2.2. Non-functional Requirements
### 2.3. Quality Attributes
## 3. Architecture
## 4. Modules
# Appendix
## A. Domain Model

![UseCase drawio](https://github.com/phunm211/SW-Associate-Architecture/assets/19267057/058361fe-6b91-4118-9158-f6446d2d1767)

| **UC**          | UC_01: Create Diagram |
|-----------------|---|
| Description     | Creating an empty diagram  |
| Actor           | Application  |
| Pre-condition   | None  |
| Post-condition  | A empty diagram has been created\nA blank graphic object has been create |
| Basic flow      |   |
| Additional Flow |   |

| **UC**          |   |
|-----------------|---|
| Description     |   |
| Actor           |   |
| Pre-condition   |   |
| Post-condition  |   |
| Basic flow      |   |
| Additional Flow |   |
## B. Quality Scenarios
## C. Quality Scenarios Analysis
## D. Candidate Architectures
## E. Candidate Architecture Evaluation
## F. Architecture Design
## G. Architecture Evaluation (ATAM)
