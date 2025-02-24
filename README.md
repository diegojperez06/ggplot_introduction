# ggplot_introduction

## Table of Content

- [Project Overview](#project-overview)
- [Datasource](#datasource)
- [R Code](#r-code)
- [Conclusion](#conclusion)

## Project Overview

In this project I used RStudios to present different visuals over Palmer Penguins and present them in a clear and professional export using R Markdown. R allows for an effective way to present data analysis findings to shareholders using it's visualizations packages. 

## Datasource

The Plamer Penguins data source is contained within RStudios as a package. I loaded the data into my enviroment, and analyzed it prior to creating the visuals using differnt functions. Such as view(), colname() and class()

## R Code

Markdown file has been loaded to the repository dashboard under "__ggplot_intro_pdf__"


#### *Setting up my enviroment*
Notes: setting up R enviroment by loading `tidyverse` and 'palmerpenguins' packages

```{r loading packages}
library (tidyverse)
library(palmerpenguins)

```

#### *Visualization*

Displaying series of visualizations.

#### *Flipper and body mass in green*

Here I displayed the realtionship between flipper length and body mass.

```{r plotting in green}

ggplot(data=penguins,aes(x=flipper_length_mm,y=body_mass_g))+
  geom_point(color="green")

```

#### *Flipper and body mass by species*

Flipper length and body mass are broken down by species 

```{r by species}

ggplot(data=penguins,aes(x=flipper_length_mm,y=body_mass_g))+
  geom_point(aes(shape=species))

```

#### *Flipper and body mass by species and sex*

Here we plot flipper length and body mass and break it down by species and sex. 

```{r species and sex}
ggplot(data=penguins,aes(x=flipper_length_mm,y=body_mass_g))+
  geom_point(aes(color=species,
                 shape=species))+
  facet_wrap(~sex)

```

## Conclusion

In this project I learned to use R's ggplot visualization package to create compelling visuals. The overall goal was to get an understanding and basic learning experience into how I can use RStudios to effectively present data analysis findings. Learning how to use R Markdown allows me to present a data-driven story to shareholders, that can be peer-reviewed by others.  
