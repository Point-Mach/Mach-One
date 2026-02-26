# Mach One
### Extreme performance 3d printer based on croXY kinematics using ballscrews and high performance servo motors

![Status](https://img.shields.io/badge/Status-Development-orange)
![Design](https://img.shields.io/badge/Architecture-CroXY-blue)
![Motion](https://img.shields.io/badge/Drive-Ball--Screw-green)
![Feedback](https://img.shields.io/badge/Control-Closed--Loop-red)

**Mach One** is a high-performance 3D printer engineered to bridge the gap between hobbyist 3D printers and industrial-grade FFF machines. By utilizing a **Stationary-Servo CroXY** gantry and **SFY1616 Ball Screws**, this project aims to bridge the gap between consumer 3d printers, and industrial FFF manufacturing machines.

The Project is built from scratch, loosely inspired by other designs like the Pantheon HS3 and Annex K3.

---

## 🏗️ Engineering Core
The design of 

* **Thermal Isolation:** A "Cold-Zone" motor configuration ensures that NEMA 23 Integrated Servos remain outside the heated build volume, allowing for high performance during high temperature printing.
* **Ballscrew driven kinematics:** Replacement of traditional GT2 belts with **SFY1616 Ball Screws** to eliminate belt-stretch, reduce VFAs, and provide the mechanical advantage required for high-speed flow.
* **Servo drive:** Driven by **High performance servos**, providing real-time encoder feedback to achieve target accelerations of **35,000 $mm/s^2$** for **quality prints**(sub 50µm toolhead deflection) and peak accelerations of **120,000+ $mm/s^2$**.

## 📊 Technical Specifications (Targets)
| Feature | Specification |
| :--- | :--- |
| **Gantry Type** | Crossed-XY (CroXY) |
| **Motion Drive** | SFS1616 Ball Screws (X/Y) |
| **Max Accel** | 120,000 $mm/s^2$ |
| **Max Speed** | 1000 mm/s+ |
| **Chamber Temp** | up to 80°C (Actively heated) |

## 🚀 Development Roadmap
- [x] **Concept:** Motion architecture and performance targets.
- [x] **Phase 1:** Gantry and kinematic system design.
- [ ] **Phase 2:** Completion of the full CAD model.
- [ ] **Phase 3:** Assembly and benchmarking of a single axis kinematic system.
- [ ] **Phase 4:** Assembly and testing of the full machine.
- [ ] **Phase 5:** Public BOM release and documentation.

## 🤝 Partners & Support
<p align="center">
  <b>Motion Control powered by</b><br>
    <a href="https://www.duet3d.com/">
    <img src="https://ooznest.co.uk/wp-content/uploads/2023/01/Duet3D-Banner.png" 
         width="300" 
         style="background-color: white; padding: 10px; border-radius: 5px;">
  </a>
</p>

---

**Developed by Point-Mach Engineering.**
