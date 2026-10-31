# UAV Sizing Workbench

An interactive, step-by-step tool for sizing small UAVs. Move a control and every chart, equation and the to-scale aircraft drawing update immediately.

It follows the method in Steven A. Brandt, "Small UAV Design Development and Sizing", chapter 10 of the *Handbook of Unmanned Aerial Vehicles* (Valavanis and Vachtsevanos, eds., Springer, 2015). This is an independent study aid and is not affiliated with the author or publisher.

## What it covers

Both electric and fueled aircraft, in the chapter's order:

1. Configuration
2. Drag polar
3. Constraint analysis
4. Battery energy or mission fuel
5. Weights
6. Sizing
7. Iteration with a fixed fuselage
8. Optimization

Each slider input is tagged **Chapter**, **Read from figure** or **Example**, so you can see which values come from the source and which are assumptions. The chapter gives no fueled-aircraft numbers, and it omits the Red Falcon's drag polar and mission time, so those values are fitted or illustrative. The tool's notes explain each one.

## Running it

It is one self-contained HTML file. Open `index.html` in a browser, or serve the folder with any static host.
