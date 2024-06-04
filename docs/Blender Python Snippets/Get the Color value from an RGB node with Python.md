> [Blender Cookbook](../README.md) / [Blender Python Snippets](README.md) / Get the Color value from an RGB node with Python.md
## Get the Color value from an RGB node with Python
url: https://blender.stackexchange.com/questions/132142/how-do-i-get-the-color-value-from-an-rgb-node-with-python

```
rgb = bpy.data.materials['MyMaterial'].node_tree.nodes['RGB'].outputs[0].default_value

# bpy_prop_array type to list
color = list(rgb)
```