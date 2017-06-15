# 3D files for some common molecules (29 total)

This repo have pdb, x3d, blend and fbx files for each molecule (*I lost pdb & x3d files for 2 molecules so they only have 27 files*)

*filenames.txt contains the name of all the molecules*

*Elements in these molecules is color coded, colors.txt files contains info about which color represents which molecules*

# Why?
I used these files in a fun little side project [MolView](https://github.com/electron0zero/MolView)

# What are these files
**These 3D models represent actual structure of molecule because these are created using pdb files**

### pdb(protein data bank) files
These are the files used to represent a molecule's structure

I downloaded these from PDB(protein data bank)

### x3d files
x3d files are generated from pdb files by using jmol

Open pdb files in jmol and then export it as x3d

### blend files
These files are blender files

Created using importing x3d and doing some cleanup(Join elements, reduce triangle count, rename materials)

These can be edited using blender

### fbx files
These files are exported from blend files(using blender obviously)

Can be used/Viewed in Windows 10 Model View(3D View) Application
