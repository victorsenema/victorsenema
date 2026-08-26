<h1 align="center">Victor Gava Senema</h1>

<p align="center">
  <b>Computer Science student @ UFU</b><br>
  Computer Vision &nbsp;·&nbsp; 3D Geometry Processing &nbsp;·&nbsp; Machine Learning
</p>

<p align="center">
  <a href="https://linkedin.com/in/victor-senema-341275389">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<br>

## About Me

Undergraduate Computer Science student at **UFU — Universidade Federal de Uberlândia**, focused on **computer vision** and **machine learning**.

I'm currently building my capstone project: a Blender extension that automates the retopology of 3D head models that turns dense, hard-to-edit meshes into clean, animation-ready quad topology.

**Spoken languages:** Portuguese (native) &nbsp;·&nbsp; English (advanced)

<br>

## Featured Project — Blender Retopology Extension

**[Blender_Retopology_Extension](https://github.com/victorsenema/Blender_Retopology_Extension)**

<p align="center">
  <img src="assets/retopology-demo.gif" width="720" alt="Blender Retopology Extension — fitting a quad template onto a 3D head model" />
</p>

A Blender add-on that fits a clean quad template onto a 3D head mesh, so the artist ends up with usable topology without retopologizing by hand.

**How the fitting works**

- **Critical points.** The user marks the critical regions that define the mesh's edge loops: mouth, eyes, nose, jawline. A symmetry solver mirrors them across the X axis, so only one half is placed by hand.

- **Thin Plate Spline warp.** Each critical point is paired with its counterpart on the template, and a **Thin Plate Spline (TPS)** deformation interpolates the warp across every remaining vertex, bending the template into the target's proportions instead of just scaling it.

- **Blender's native toolset.** The fit is finished with Blender's own functions, such as **Shrinkwrap** and **Subdivision Surface**.

<br>

## Tech Stack

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=py,c" height="40" />
      &nbsp;<code>SQL</code>
    </td>
  </tr>
  <tr>
    <td><b>Machine Learning &amp; Computer Vision</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=pytorch,opencv" height="40" />
      &nbsp;<code>YOLO / Ultralytics</code> <code>NumPy</code> <code>Pandas</code>
    </td>
  </tr>
  <tr>
    <td><b>Data &amp; Databases</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite" height="40" />
    </td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=git,github,vscode" height="40" />
      &nbsp;<code>Jupyter</code>
    </td>
  </tr>
  <tr>
    <td><b>3D &amp; Graphics</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=blender" height="40" />
      &nbsp;<code>Blender Python API</code> <code>bmesh</code>
    </td>
  </tr>
</table>

<br>

## Projects

| Project | Description |
| :--- | :--- |
| **[License-Plate-Recognizer](https://github.com/victorsenema/License-Plate-Recognizer)** | License plate detection and recognition pipeline. The model was trained on a public dataset, but every plate was **labelled manually** to build the training set, and the whole training run was done locally on my own machine. |
| **[Math-Expression-Interpreter](https://github.com/victorsenema/Math-Expression-Interpreter)** | An interpreter for mathematical expressions written in **C** — it tokenizes, parses and evaluates arithmetic expressions from scratch. |
