# Mach One
### Extreme performance 3d printer based on croXY kinematics using ballscrews and high performance servo motors

![Status](https://img.shields.io/badge/Status-Development-orange)
![Design](https://img.shields.io/badge/Architecture-CroXY-blue)
![Motion](https://img.shields.io/badge/Drive-Ball--Screw-green)
![Feedback](https://img.shields.io/badge/Control-Closed--Loop-red)

**Mach One** is a high-performance additive manufacturing platform engineered to bridge the gap between hobbyist DIY machines and industrial-grade motion cells. By utilizing a **Stationary-Servo CroXY** gantry and **SFS1210 Ball Screws**, this project aims to bridge the gap between consumer 3d printers, and industrial FFF manufacturing machines.

---

## 🏗️ Engineering Core
The architecture is centered around three pillars of industrial design:

* **Thermal Isolation:** A "Cold-Zone" motor configuration ensures that NEMA 23 Integrated Servos remain outside the heated build volume, allowing for peak performance during high-temp (100°C+) chamber operations.
* **Precision Drive:** Replacement of traditional GT2 belts with **SFS1210 Ball Screws** to eliminate belt-stretch, reduce VFA, and provide the mechanical advantage required for high-speed flow.
* **Closed-Loop Motion:** Driven by **iSV57T Integrated Servos**, providing real-time encoder feedback to achieve target accelerations of **35,000 $mm/s^2$** for **quality prints** and peak accelerations of **80,000 $mm/s^2$**.

## 📊 Technical Specifications (Targets)
| Feature | Specification |
| :--- | :--- |
| **Gantry Type** | Crossed-XY (CroXY) |
| **Motion Drive** | SFS1616 Ball Screws (X/Y/Z) |
| **Motors** | iSV57T 180W Integrated Servos |
| **Target Accel** | 30,000 $mm/s^2$ |
| **Target Speed** | 500 mm/s+ |
| **Chamber Temp** | up to 110°C (Active) |

## 🚀 Development Roadmap
- [x] **Concept:** Motion architecture and kinematic validation.
- [ ] **Phase 1:** Finalizing Motor Mount & Thermal Shielding CAD. (Active)
- [ ] **Phase 2:** Alpha Frame assembly and Ball-Screw alignment testing.
- [ ] **Phase 3:** High-G motion benchmarking and firmware optimization.
- [ ] **Phase 4:** Public BOM release and documentation.

---

## 🤝 Sponsorship & Partnership
This project is made possible through technical partnerships with industry-leading motion control suppliers. We are currently documenting the integration of **StepperOnline** iSV series servos as the primary motion standard for this platform.

**Developed by Point-Mach Engineering Group.**
