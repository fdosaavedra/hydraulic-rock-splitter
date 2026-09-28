# 🪨 Hydraulic Rock Splitter

**B.Sc. Mechanical Engineering capstone project** at Pontificia Universidad Católica de Chile (Jul to Dec 2024), developed for the **Municipality of Puente Alto**, Santiago.

The goal was a portable **hydraulic wedge system** that breaks rock masses without explosives or heavy machinery. A hydraulic cylinder drives a wedge between two feathers inside a pre-drilled hole, and the lateral force splits the rock along a controlled line.

<p align="center">
  <img src="images/final-test-split-block.jpg" width="45%" alt="Concrete block split during the final test" />
  <img src="images/team.jpg" width="50%" alt="Project team at the final presentation" />
  <br><em>Left: a concrete test block split by the prototype during the final presentation. Right: the team.</em>
</p>

## 👤 My Role

Five-person team. A teammate and I carried most of the technical work. I was responsible for:

- 🔎 Preliminary research: rock mechanics, rock mass classification and existing splitting equipment
- 📐 Methodology and design of the wedge system
- 🧮 Engineering calculations
- 🖥️ CAD modeling (Autodesk Inventor) and FEA simulations
- 📋 Bill of materials
- 🏭 Manufacturing and assembly in the workshop

---

## 1. Design

The system has three main parts: an electric **hydraulic power unit**, a **hydraulic cylinder** with a custom flange, and the **wedge and feather** set that goes into the rock.

<p align="center">
  <img src="images/wedge-cad.jpg" width="30%" alt="Wedge CAD" />
  <img src="images/cylinder-flange-cad.jpg" width="34%" alt="Cylinder flange CAD" />
  <img src="images/hydraulic-power-unit.jpg" width="30%" alt="Hydraulic power unit" />
</p>

## 2. Simulation

I checked the critical components with **finite element analysis** (von Mises stress) before manufacturing, to verify that the wedge and its housing could carry the splitting load.

<p align="center">
  <img src="images/fea-housing-stress.png" width="45%" alt="FEA of the wedge housing" />
  <img src="images/fea-wedge-stress.png" width="45%" alt="FEA of the wedge" />
</p>

## 3. Bill of Materials

The full assembly was documented in a bill of materials that separates custom-made parts from purchased and standard parts (ISO/DIN fasteners, dowel pins).

<p align="center">
  <img src="images/bill-of-materials.png" width="70%" alt="Bill of materials" />
</p>

## 4. Manufacturing

Custom parts were cut, machined and assembled in the university workshop.

<p align="center">
  <img src="images/manufacturing-cutting.jpg" width="32%" alt="Cutting steel" />
  <img src="images/machined-parts.jpg" width="32%" alt="Machined parts" />
  <img src="images/machine-shop.jpg" width="32%" alt="CNC machine" />
</p>
<p align="center">
  <img src="images/cylinder-parts.jpg" width="32%" alt="Cylinder and parts on the workbench" />
  <img src="images/assembly.jpg" width="32%" alt="Assembly" />
  <img src="images/test-setup.jpg" width="32%" alt="Test setup with the power unit" />
</p>

## 5. Testing

At the final presentation, the prototype was connected to the power unit and inserted into a concrete test block. **The block split along the wedge line**, validating the design.

---

## 🧰 Tools

![Autodesk Inventor](https://img.shields.io/badge/Inventor-E8A33D?style=flat-square&logo=autodesk&logoColor=black)
![FEA](https://img.shields.io/badge/FEA-Stress_Analysis-2A78D6?style=flat-square)
![Hydraulics](https://img.shields.io/badge/Hydraulics-555555?style=flat-square)
![Machining](https://img.shields.io/badge/Machining-555555?style=flat-square)

> 📄 The full project report (design calculations, pressures and forces) will be added to this repository.
