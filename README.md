
![Memory Halo 4 Frame](images/memory_halo_main.jpg)

# Memory Halo 4 Long Range Drone Frame

An open source 4 inch long range FPV drone, designed for those that prefer a stronger frame with less vibrations and no jello. This repository includes DXF carbon cutting files for CNC fabrication and STL files for 3D prints aswell as the hardware and documentation needed for one frame. 

## Features

- 4" propellor size
- Deadcat configuration (props out of view)
- 0-30 Degree camera angle, while staying protected
- Plenty of room inside to fit everything
- Stack mounting: 20x20mm M3 / 25.5x25.5mm M2 / 25.5x25.5mm M2 (angled 45°)
- Vtx mounting: 20x20mm M2 / 25.5x25.5mm M2
- Motor mounting: 9x9mm and 12x12mm
- Camera support: 19/20mm: Analog, Walksnail, DJI O3 Pro, O4, O4 Pro
- Lightweight: ~200g dry with O4 Pro, ~170g analog
- Supports single or double rear standoff design (seperate middle & top plate design for it)


## Hardware needed
Minimum needed to build the frame. Weight can slightly vary, this is just a guideline.

| Part name | Quantity | Material | Weight per piece (g) |
|-----------|----------|----------|----------------------|
| Bottom plate | 1 | Carbon  | 5.60 |
| Middle plate | 1 | Carbon  | 8.30 |
| Top plate | 1 | Carbon  | 8.30 |
| Arms | 4 | Carbon  | 4.60 |
| Camera plates | 2 | Carbon  | 2.10 |
| M2 20mm standoffs | 5 | Aluminium | 0.35 |
| M2 23mm standoff | 1 | Aluminium | 0.40 |
| M2 14mm screws | 4 | Aluminium | 0.65 |
| M2 9mm screws | 11 | Aluminium | 0.45 |
| M2 pressnuts | 4 | Aluminium | 0.45 |
| Battery pad | 1 | Rubber | 3 |
| 19/20mm camera mount | 1 | TPU | 2.2 |

### Note: for the double rear standoff version, you need the following extra:
| Part name | Quantity | Material | Weight per piece (g) |
|-----------|----------|----------|----------------------|
| M2 20mm standoffs | 1 | Aluminium | 0.35 |
| M2 9mm screws | 2 | Aluminium | 0.45 |

Total minimum frame weight single rear standoff: ~ 60g
Total minimum frame weight double rear standoff: ~ 63g

## Repository Content

This repository contains everything needed to manufacture and build the frame.

- **[/carbon](carbon/)** 
  DXF files for CNC cutting the carbon fiber plates.  
  Includes both **single rear standoff** and **double rear standoff** frame variants.

- **[/3d-prints](3d-prints/)**  
  STL files for TPU printed components such as camera mounts, gps and antenna mounts.

- **[/battery-pad](battery-pad/)**  
  DXF file for laser cutting the battery pad. 2 variations. 

- **[/betaflight-tune](betaflight-tune/)**  
  Betaflight tune specifically for the frame, to get as clean gyro data as possible.

- **[/docs](docs/)** 
  Documentation including:
  - Assembly instructions
  - Hardware requirements
  - Example build configurations

- **[/images](images/)** 
  Photos and diagrams of the frame and example builds.
  Full build examples are available in `/build examples.md`.

## License

This project is licensed under Creative Commons BY-NC 4.0:

- Personal/hobby builds allowed
- CNC shops may cut frames for personal use
- No mass production or commercial selling
- Do not claim as your design

Full license: https://creativecommons.org/licenses/by-nc/4.0/