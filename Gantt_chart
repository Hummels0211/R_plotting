library(ggplot2)
library(tidyr)
library(lubridate)  # For date and time formatting
# library(DiagrammeR)
# library(plan)
# library(plotrix)
library(timevis)

#####################################################################################
library(DiagrammeR)

mermaid("
gantt
dateFormat  DD/MM/YYYY
title A sample Gantt Diagramme

section Pipeline 1
This is completed             :done,          first_1,    06/06/2024, 25/06/2024
This is active                :active,        first_2,    2014-01-09, 3d
Do this later                 :               first_3,    after first_2, 5d
Do this after that            :               first_4,    after first_3, 5d

section Important Things
Completed, critical task      :crit, done,    import_1,   2014-01-06,24h
Also done, also critical      :crit, done,    import_2,   after import_1, 2d
Doing this important task now :crit, active,  import_3,   after import_2, 3d
Next critical task            :crit,          import_4,   after import_3, 5d

section The Extras
First extras                  :active,        extras_1,   after import_4,  3d
Second helping                :               extras_2,   after extras_1, 20h
More of the extras            :               extras_3,   after extras_1, 48h
")

#######################################################################################
