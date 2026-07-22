# Civ-Team-411 GYM PULSE
The Gym Structural Load Monitoring Dashboard is a MATLAB App Designer application that helps gym managers monitor occupancy and floor vibration. The dashboard uses an interactive gym map, heat maps, and graphs to identify heavily used areas and provide recommendations to improve gym layout and reduce structural stress.
## Setup Instructions

1. Download or clone the project files.
2. Ensure the following files are located in the same project directory:
   - `app_interactive.mlapp`
   - `zone_occupancy.mat`
   - `zone_metadata.mat`
   - `structural_response_reference.mat`
   - `floor_vibration_sensor_locations.mat`
   - `floor_vibration_acceleration.mat`
3. Open MATLAB.
4. Navigate to the project folder.
5. Open `app_interactive.mlapp`.
---

## Running the Project

1. Click **Run** in MATLAB App Designer.
2. Use the **Time of Day** slider to select a time.
3. Toggle between **Occupancy** and **Floor Acceleration** heat maps.
4. Select a gym zone to view occupancy information.
5. Review the **High Load Areas** list and **Recommended Actions** panel.

---

## Dependencies / External Tools

- MATLAB (R2024a or newer recommended)
- MATLAB App Designer

Required data files:

- `zone_occupancy.mat`
- `zone_metadata.mat`
- `structural_response_reference.mat`
- `floor_vibration_sensor_locations.mat`
- `floor_vibration_acceleration.mat`

---

## Results

The completed application provides:

- Interactive gym floor map
- Occupancy heat map
- Floor acceleration heat map
- Occupancy vs. Time graph
- High load area identification
- Engineering recommendations based on occupancy and vibration data
