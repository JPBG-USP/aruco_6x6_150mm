# Arucos 6x6

This repository contains 3D models of 6x6 ArUco markers (`DICT_6X6_1000`, ids 0–50) for Gazebo. Each marker measures 150mm x 150mm. The marker is surrounded by a white border one module wide (18.75mm), so the sign is 187.5mm x 187.5mm x 30mm. The border is the quiet zone detectors need to find the marker.

The model origin is 75mm below the marker centre, at the marker's bottom edge. The white border extends 18.75mm below the origin.

After cloning this repo you will need to add the path to this repo on the Gazebo resource path

```bash
export GZ_SIM_RESOURCE_PATH=$GZ_SIM_RESOURCE_PATH:<path_to_repo>
```