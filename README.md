# Inovato Quadra K3S project

A hobby project to turn a number of [Quadra](https://www.inovato.com/category/quadra) mini-PCs into a K3S hobby cluster.  Including 3d printable accessories.

## FreeCAD files

In the 'freecad' directory, you'll find 3d printable models for use with this project.  If you're only interested in running K3S, they aren't strictly necessary.  However, running the passively cooled Quadra with heavier workloads may require [active cooling](https://forum.inovato.com/post/keeping-the-quadra-cool-12455928?pid=1333518445).  3D printing can provide an easy way to get active cooling for your Quadra(s), without modifying or disassembling them.

## Ansible / Python

We'll use the [k3s-ansible project](https://github.com/k3s-io/k3s-ansible) to automate the installation of k3s, and to provide a basis for other automation.  Familiarity with Ansible and Python will certainly be helpful, though you aren't going to need to know how to develop in either.

We'll mostly be editing files and running commands.  Do not worry, if these technologies aren't familiar.

