# CSP

Discovery of Druggable Cancer-Specific Pathway (CSP)

For the accessible resource, please go to [CSP website](https://www.meb.ki.se/shiny/truvu/CSP/).

- `pas`: Source code for pathway activation score (PAS) generation.

- `shiny`: Source code for [CSP website](https://www.meb.ki.se/shiny/truvu/CSP/).

PAS is calculated for Genomics of Drug Sensitivity in Cancer (GDSC), The Cancer Genome Atlas (TCGA) and BeatAML. 
You can download PAS of GDSC [here](https://drive.google.com/file/d/1XjH-HlNi4k-YEoF8Yqj_BJWBvfnrMudr/view?usp=sharing). For TCGA and BeatAML, we do not publish our results due to the limitation of storage space.
For further requests, please send an email to `quang.thinh.trac {at} ki.se`

To be able to access PAS of GDSC, you need to use `qs` package:

```
library(qs)
pas <- qread("/path/to/gdsc_pas.qs")
```



