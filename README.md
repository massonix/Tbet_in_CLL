# TBET expression in tonsillar naive and memory B-cells

The aim of this repo is to assess the expression of TBET (TBX21) in naive and memory B-cells from our [tonsil atlas](https://www.biorxiv.org/content/10.1101/2022.06.24.497299v1.full).
This analysis is part of a project aimed at characterizing the expression and function of TBET in chronic lymphocytic leukemia (CLL).

The notebook [TBET_in_tonsillar_B_cells.Rmd](https://github.com/massonix/Tbet_in_CLL/blob/main/TBET_in_tonsillar_B_cells.Rmd) documents how to download the data from Zenodo and how to reproduce the associated figures of the paper. In addition, we provide the [compiled html file](https://github.com/massonix/Tbet_in_CLL/blob/main/TBET_in_tonsillar_B_cells.html) which can be visualized [online](http://htmlpreview.github.io/?https://github.com/massonix/Tbet_in_CLL/blob/main/TBET_in_tonsillar_B_cells.html). Importantly, the session information at the end of the html documents the environment used (operating system, R version, packages and versions).

To clone the repository you can run the following command in the terminal:

```{bash}
git clone https://github.com/massonix/Tbet_in_CLL.git
cd Tbet_in_CLL
```

Then, you can repeat the analysis in rstudio opening the Tbet_in_CLL.Rproj, which will ensure that all paths are relative to the root directory:

```{bash}
rstudio
```

Note that the file "All_Bcells_level_5_auc.csv" was too large to share with this GitHub repository. Thus, we uploaded it to [FigShare](https://figshare.com/articles/dataset/AUCell_values_regulons_B-cells_tonsil_atlas/23223347). We can download the file from the command line as follows:

```{bash}
cd data
wget https://figshare.com/ndownloader/files/40933895
mv 40933895 All_Bcells_level_5_auc.csv
```
