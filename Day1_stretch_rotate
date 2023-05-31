# Lesson 1: Streching and rotating

## How to Stretch an Item Lengthways in Script Blender Python

You can change the scale of an object using the bpy module in Blender's Python API. Here is a basic example:

```python
import bpy

# Select the object by name
obj = bpy.data.objects['ObjectName']

# Change the scale in the X dimension (stretch lengthwise)
obj.scale.x = 2.0
How to Soften the Edges in Python Blender
Blender's Python API (bpy module) allows you to perform various operations programmatically that would normally be done through the GUI. One such operation is edge softening or applying smooth shading to objects.

Here is an example of how you can do this:

python
Copy code
import bpy

# Select the object by its name
obj = bpy.data.objects['ObjectName']

# Select the object's mesh data
mesh = obj.data

# Ensure that you're in 'OBJECT' mode
bpy.ops.object.mode_set(mode='OBJECT')

# Select all the polygons (also called 'faces') of the object
for poly in mesh.polygons:
    poly.select = True

# Switch to 'EDIT' mode to perform operations on the mesh
bpy.ops.object.mode_set(mode='EDIT')

# Apply smooth shading
bpy.ops.mesh.faces_shade_smooth()

# Switch back to 'OBJECT' mode
bpy.ops.object.mode_set(mode='OBJECT')
How to Round the Edges with Python
To round or bevel the edges of an object using Blender's Python API, you would typically add a 'Bevel' modifier to the object. Here is a simple script that demonstrates this:

python
Copy code
import bpy

# Select the object by its name
obj = bpy.data.objects['ObjectName']

# Add a Bevel modifier to the object
bevel_mod = obj.modifiers.new('BevelModifier', 'BEVEL')

# Set the properties of the Bevel modifier
bevel_mod.width = 0.1
bevel_mod.segments = 3
bevel_mod.limit_method = 'ANGLE'
bevel_mod.angle_limit = 0.785398   # 45 degrees
How to Rotate on the X Axis in Python
To rotate an object around the X-axis in Blender using the Python API, you can use the rotation_euler property of the object. Here's a simple script demonstrating this:

python
Copy code
import bpy
import math

# Select the object by its name
obj = bpy.data.objects['ObjectName']

# Rotate the object 90 degrees around the X-axis
obj.rotation_euler[0] = math.radians(90)
