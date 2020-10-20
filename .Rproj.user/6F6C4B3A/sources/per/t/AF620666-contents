setwd("D:/RKurse/Dokumentation/crashcouRse")
library("rmarkdown")

rmarkdown::clean_site()  # delete old files
rmarkdown::render_site(encoding="UTF-8") # render all files new; UTF-8 for ä, ö, ü, ß

{
library(stringr); library(knitr)
filenames <- list.files(pattern=".Rmd") 
dont <- str_detect(filenames, paste(c("appendix", "kontakt", "index"), collapse="|"))
filenames <- filenames[!dont]

# site.wd <- getwd()
#   setwd("D:/RKurse/Dokumentation/Vorführung")
#   for (i in 1:length(filenames)){
#     purl(paste0(site.wd,"/",filenames[i]))
#     print(filenames[i])
#   }
#   setwd(site.wd)  
} # tranlsate website to R codes as well
