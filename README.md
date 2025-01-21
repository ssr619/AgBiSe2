# AgBiSe2
## THE PROBLEM
when I use the code 
```bash
pydefect s -p ../unitcell/structure_opt/CONTCAR --matrix 2 1 1
```
warning appears, like the following

![image](https://github.com/ssr619/AgBiSe2/blob/main/pictures/99550b68745e9b2c5d96a148a736f70.png)

Then I use the code to find the conventional cell of CONTCAR

```bash
vise si -p ../unitcell/structure_opt/CONTCAR -c

```
But when I use above command to construct supcell by the conventional cell

```bash
pydefect s -p CONTCAR_conventional --matrix 2 1 1
```

The warning also appears.

![image](https://github.com/ssr619/AgBiSe2/blob/main/pictures/20250121174507.png)

And the symmetry of the conventional cell(R-3m) is changed compared with the CONTCAR(P-3m1)
![image](https://github.com/ssr619/AgBiSe2/blob/main/pictures/afe11d8f54826ecd40a4b3637bee1ad.png)

![image](https://github.com/ssr619/AgBiSe2/blob/main/pictures/739638b1b8d5e6214312913ab447a71.png)

And I want to know how to make the symmetry unchanged when construct the supercell.
