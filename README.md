# Assignment_2.1
How to Import SAS XPORT files into R with the foreign package?
ans:The foreign package with the read.xport() function also allows you to get your SAS XPORT files into R:

library(foreign)

data <- read.xport("")

How to Import SAS Files into R with the Haven package?
ans:Just like the foreign and the sas7bdat packages, the haven package also allows you to read in b7dat files into R with the read_sas() function:

library(haven)

data <- read_sas("")

How to read Weka Attribute-Relation File Format (ARFF) files in R?
ans: Data from Weka Attribute-Relation File Format (ARFF) files can be read in with the read.arff() function:

library(foreign)

data <- read.arff("")

How to read a heavy csv/tsv file using readr package?
library(tidyverse)

mydata <- read_tsv("mtcars.txt")

mydata <- read_csv("mtcars.csv")
