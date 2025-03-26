# Desmos Dynamic Triangle:
In the following link is the (hopefully) completed iteration of a completely dynamic triangle calculated and rendered within Desmos using the only Desmos capabilities we have in the Derivita embed.
The main part you want to focus on is the "input values". There are a handful that can be chosen via Omaha. Those being:
- `r_{ound}` --  This tells Desmos which decimal place to round the angles to. Default is one.
- `r_{oundD}` -- This tells Desmos which decimal place to round the distances to. Default is one.
- `A_{label}` -- This is the label for angle A. 0 = Nothing is displayed. 1 = Both Degree and Letter is displayed. 2 = Only Degree is displayed. 3 = Only Letter is displayed.
- `B_{label}` -- This is the label for angle B. 0 = Nothing is displayed. 1 = Both Degree and Letter is displayed. 2 = Only Degree is displayed. 3 = Only Letter is displayed.
- `C_{label}` -- This is the label for angle C. 0 = Nothing is displayed. 1 = Both Degree and Letter is displayed. 2 = Only Degree is displayed. 3 = Only Letter is displayed.
- `a_{label}` -- This is the label for distance a. 0 = Nothing is displayed. 1 = Both Distance and Letter is displayed. 2 = Only Distance is displayed. 3 = Only Letter is displayed.
- `b_{label}` -- This is the label for distance b. 0 = Nothing is displayed. 1 = Both Distance and Letter is displayed. 2 = Only Distance is displayed. 3 = Only Letter is displayed.
- `c_{label}` -- This is the label for distance c. 0 = Nothing is displayed. 1 = Both Distance and Letter is displayed. 2 = Only Distance is displayed. 3 = Only Letter is displayed.
- `x_1` -- The X-Value of point A.
- `y_1` -- The Y-Value of point A.
- `x_2` -- The X-Value of point B.
- `y_2` -- The Y-Value of point B.
- `x_3` -- The X-Value of point C.
- `y_3` -- The Y-Value of point C.

If you want to add distance labeling (cm, in, mi, ft, etc.) you need to do so manually per question as Desmos variables cannot store strings.

The Output Variables are as follows:
- `a` for the distance from point B to point C
- `b` for the distance from point C to point A
- `c` for the distance from point A to point B
- `\theta_{do1}` for angle C unrounded.
- `\theta_{do2}` for angle B unrounded.
- `\theta_{do3}` for angle A unrounded
- **Use the output list `O_L` to access all output values, inputted in the order listed above.**

*I will also create a template graph in the new `Templates` folder under `Student Sandbox` so we can duplicate and move the duplicated question instead of needing to copy paste all the functions manually every single time.*
https://www.desmos.com/calculator/2u760ovhkv
