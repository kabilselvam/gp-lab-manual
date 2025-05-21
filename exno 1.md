# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date: 05/03/25
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
**1. Open Unreal Engine:**
* Launch Unreal Engine and create a new project or open an existing project.
  
**2. Create a New Material:**
* In the Content Browser, right-click and select ‘Material’ to create a new material.
* Name it appropriately (e.g., ‘M_EffectMaterial’).

**3. Adjust the Emissive Property:**
* Open the material by double-clicking on it.
* In the Material Editor, use a Constant3Vector node to define a color for the emissive effect.
* Connect the node to the Emissive Color input of the Material node.
* Adjust the color's brightness by multiplying it with a constant to simulate glowing material.
  
**4. Modify the Roughness:**
* Use a Scalar Parameter node to control the roughness (0 for smooth, 1 for rough).
* Connect this node to the Roughness input of the material node.
  
**5. Control Metallic Property:**
* Use another Scalar Parameter node to define metallicity (0 for non￾metallic, 1 for metallic).
* Connect the scalar to the Metallic input of the material node.
  
**6. Apply the Material to a 3D Model:**
* Drag and drop the material onto a 3D model in the scene to see the effects in real-time.
  
**7. Tweak the Values:**
* Experiment with different values for emissive color, roughness, and metallic properties to see how they affect the appearance of the material.
  
**8. Take Screenshots:**
* Capture the visual results using the Screenshot tool within Unreal Engine

## Output:
### 1. Base Color
![image](https://github.com/user-attachments/assets/f8cedde1-d1a2-4c2d-995f-dd5044ca3254)

### 2. Emissive property (glowing material):
![image](https://github.com/user-attachments/assets/f4e7a07b-58d3-49d3-bf9f-6190af8f497a)

### 3. Roughness property (matte vs shiny surfaces):
![image](https://github.com/user-attachments/assets/a567713d-133c-487b-bc9d-9c77959c58b8)

### 4. Metallic property (metallic vs non-metallic appearance):
![image](https://github.com/user-attachments/assets/806dac4a-93b5-4b01-b683-ec4199e9f3db)

### 5. Final Output:
![gp1 1](https://github.com/user-attachments/assets/020fc32f-376a-4bab-9c2d-15a4e0534ed6)

## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
