# Amnis Assortment System

![CC-BY-NC 4.0](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)

Removable assortment box system designed to a grid found in some commercial
assortment cases. Please see compatibility with other assortment systems below.

You can print these boxes to use with your cases or print and glue the grid in
to bottom of your own drawers. Follow this repository for new types of boxes in
the future.

[Check out the pictures of this system!](/pics/)


## Box categories

### Z10 (Full Height)

These boxes are the baseline for height. Z10 means 100%, which are designed to fit
Raaco Assorter 55 cases. Z10 boxes are plain boxes with angled surface for name
sticker and box removal. See compatibility below.

Sizes: Normal grid, sizes from 1x1 onwards.  
Height: 47mm.  
Naming example: 3x1z10-box.stl  
  - 3 y-units long, 1 x-unit wide. Z10 series. Plain box.  

### Z06 (Lidded)

These boxes are designed to be used in combination with lids, where the combined
height is 100%. The boxes themselves are plain and 60% height, and lack angled surface
found on Z10 series. The lids also have normal grid, which allows them to be used, 
for example, as standalone items on drawers. The lids also have angled feature which
allows them to be easily lifted apart from boxes below.

Sizes: Normal grid.  
Height: 47mm with combined box & lid.  
  - Boxes: 29mm.  
  - Lids: 20mm.  
Naming example: 3x2z06-box.stl  
  - 3 y-units long, 2 x-unit wide. Z06 series box.  
Naming example: 3x2z06-lid-drills-jobber-6to1by05.stl  
  - 3 y-units long, 2 x-unit wide. Z06 series lid. Meant to fit "jobber" (standard)
  size drills from 6mm to 1mm with 0.5mm step.  

#### Acknowledgements

Check out [Alexandre Chappel on Youtube.](https://www.youtube.com/c/achappel) He has been the
inspiration for this project and definitely deserves your support.


# Print settings

```
For Ender 3 V2 with 0.4mm nozzle.

Layer height: 0.3mm
Line width: 0.4mm
Wall line count: 2
Top layers: 2
Bottom layers: 1
Infill percentage: 10%
Infill pattern: Cubic
Build plate adhesion type: Skirt
```

# Compatibility

#### Verified to fit:  

- Raaco Assorter 55 system
  - Amnis Assortment System was designed to be compatible with Raaco Assorter
  55, since those are the cheapest proper assortment boxes easily available in
  Finland.
  - Assorter 55 boxes also fit the grid defined in this project.
  - [Assorter 55 4x8-0 case](https://www.raaco.com/en/productpage/?sku=136204&category=3539)
  
#### Should fit, but not verified:

- Clas Ohlson (CoCraft) 31-1433
  - [31-1433](https://www.clasohlson.com/fi/S&auml;ilytyslaatikko-Cocraft/p/31-1433)
  
# FAQ

#### What is Amnis?

Amnis is a Finnish domain I own for my personal server. At the time of writing
there are no public facing functions.

#### About licensing.

This repository is licensed under [CC-BY-NC 4.0](LICENSE.md). If you are interested
in commercial usage, please contact me for licensing.

#### About contributing.

At the time of writing I am not planning on accepting contributions. You can of course
design your own boxes to be compatible with this system, under the terms of the license.
Please do not use "Amnis" on your own parts.

If you note problems with these models, please create an issue and I might look at it..


# About commits

#### New part

```md
🚀 feat (context): what's the part?

Closer description. Interesting facts about the part.

(References to issues etc) <- optional
```

#### Fixed part

```md
🔨 fix (context): what is fixed?

Closer description. Why was this fix necessary?

(References to issues etc) <- optional
```

#### Documentation change

```md
📄 docs (context): What was done to documentation?

Closer description. Why was the documentation change necessary?

(References to issues etc) <- optional
```

#### Removal of parts and/or documents

```md
❌ cleanup (context): What was removed / cleaned?

Closer description.

(References to issues etc) <- optional
```