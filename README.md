![certification-mark-IR000001-stacked](https://github.com/user-attachments/assets/c3395ff3-e127-4349-a6cb-94514ce2324d)# Adaptive Line-Following Electronic Board for Sustainable Robotics




**An open-source, low-cost PCB for line-following robots, integrating adaptive control and recycled materials to advance sustainability in robotics education and precision agriculture.**
more on DOI: 10.36227/techrxiv.174239980.06473545/v1
---

## Overview
This project provides hardware and firmware for a line-following robot designed to:
- **Reduce STEM education costs** with a $18 open-source alternative to commercial solutions (48% cheaper).  
- **Enable pesticide-free farming** through autonomous weed removal (20% crop loss reduction in field tests).  
- **Promote sustainability** via 70% post-consumer recycled PCB materials and energy-efficient design.  

Aligned with **UN SDGs 4 (Education)**, **9 (Industry)**, and **12 (Sustainability)**.  

---

## Key Features  
- **Dynamic Threshold Algorithm**: Adapts to lighting (50–1000 lux) and terrain with 95% tracking accuracy.  
- **Recycled PCB**: 70% post-consumer FR-4 substrate, validated via XRF spectroscopy.  
- **Low-Power Design**: 120 mA @ 5V (50% lower than Pololu QTR-8RC).  
- **Modular Architecture**: Easy integration with Arduino, Raspberry Pi, or custom controllers.  

---

## Repository Structure  


---

## Getting Started  
### For Developers  
1. **Modify the Design**:  
   - Open `/design-files` in [Altium Designer](https://www.altium.com/) or import Gerbers into [KiCad](https://www.kicad.org/).  
   - Tweak sensor placement, motor drivers, or threshold parameters.  

2. **Flash Firmware**:  
   - Upload `/firmware/dynamic_threshold.ino` to an Arduino Nano.  

### For Manufacturers  
1. **Order PCBs**:  
   - Submit project files to a PCB fab (e.g., [JLCPCB](https://jlcpcb.com)).  
   - Use FR-4 with ≥70% recycled substrate for sustainability.  

2. **Assemble Components**:  
   - Follow `/docs/assembly-guide.pdf` and `/docs/BOM.csv`.  

---

## License  
This work is licensed under the **[CERN Open Hardware Licence v1.2](LICENSE)**. You may:  
- **Use** the design freely for any purpose.  
- **Modify** and share derivatives.  
- **Manufacture** and sell the board (attribution required).  

---

## Contributing  
We welcome improvements!  
1. **Report Issues**: Open a GitHub Issue for bugs or suggestions.  
2. **Submit Pull Requests**: Follow our [contribution guidelines](CONTRIBUTING.md).  
3. **Share Use Cases**: Email `ethan.sotoodeh81@gmail.com` with your projects.  

---

## Acknowledgments    
- Field-tested with Iranian farmers and STEM students.  
