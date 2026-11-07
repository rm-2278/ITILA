
### Re-generating the sample image
If you tweak the exercise layout, rebuild the showcase image with:

```bash
cd Exercises
pdflatex -interaction=nonstopmode exercise_2_14.tex
pdftocairo -png -singlefile -r 150 exercise_2_14.pdf exercise_2_14
```
The `standalone` class keeps the page tightly cropped, so the resulting PNG can be dropped anywhere in the README without extra editing.

### Issues
3.7
5.14, 5.16
6
7
8
9
20.3, 20.4, 20.5

## Read
1, 2, 3, 4, 5, 6, 7, 8, 9
20, 21


## Done
1, 2, 4
21
