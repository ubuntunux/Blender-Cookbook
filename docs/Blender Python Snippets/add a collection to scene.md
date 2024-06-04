> [Blender Cookbook](../README.md) / [Blender Python Snippets](README.md) / add a collection to scene.md
## add a collection to scene
```
>>> collection = bpy.data.collections.new('New Collection')
>>> bpy.context.scene.collection.children.link(collection)
```