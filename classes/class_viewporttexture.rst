.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the ViewportTexture.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_ViewportTexture:

ViewportTexture
===============

**Inherits:** :ref:`Texture<class_Texture>` **<** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

Texture which displays the content of a :ref:`Viewport<class_Viewport>`.

Properties
----------

+---------------------------------+-----------------------------------------------------------+
| :ref:`NodePath<class_NodePath>` | :ref:`viewport_path<class_ViewportTexture_viewport_path>` |
+---------------------------------+-----------------------------------------------------------+

Description
-----------

Displays the content of a :ref:`Viewport<class_Viewport>` node as a dynamic :ref:`Texture<class_Texture>`. This can be used to mix controls, 2D, and 3D elements in the same scene.

To create a ViewportTexture in code, use the :ref:`Viewport.get_texture<class_Viewport_get_texture>` method on the target viewport.

Property Descriptions
---------------------

.. _class_ViewportTexture_viewport_path:

- :ref:`NodePath<class_NodePath>` **viewport_path**

+----------+-----------------------------------+
| *Setter* | set_viewport_path_in_scene(value) |
+----------+-----------------------------------+
| *Getter* | get_viewport_path_in_scene()      |
+----------+-----------------------------------+

The path to the :ref:`Viewport<class_Viewport>` node to display. This is relative to the scene root, not to the node which uses the texture.

