Prasher, S., Evans, JC., Thompson, MJ., & Morand-Ferron, J. Characterizing innovators: ecological and individual predictors of problem-solving performance. PLoS ONE.

File list (files found within Prasher-et-al-2019-plosone.zip)
LeverPullingPerformance.csv
PaperRippingPerformance.csv
Persistence&Repeatability.csv


File descriptions

LeverPullingPerformance.csv: Contains data on characteristics of individuals and measures from lever-pulling trials sorted to recreate the reported extended cox regression analysis.

Column: Description

LeverPullingPerformance$indiv: individual band number identification
LeverPullingPerformance$latency: latency to solve or become censored in the lever-pulling trials
LeverPullingPerformance$status: censoring status of latency to solve the lever-pulling task used for cox regression (0 = censored, 1 = uncensored)
LeverPullingPerformance$tstart: start time (in seconds) of each time interval used for the extended cox regression
LeverPullingPerformance$tstop: stop time (in seconds) of each time interval used for the extended cox regression
LeverPullingPerformance$contacts: number of contacts made with the task in each time interval
LeverPullingPerformance$domscore: dominance score based on interactions between birds at RFID feeders.
LeverPullingPerformance$urbanscore: urbanization score generated by PCA analysis used to infer degree of urbanization at each site.
LeverPullingPerformance$explscore: exploration score generated by PCA analysis.
LeverPullingPerformance$solve: indicator of whether the task was solved in each time interval (0 = unsolved, 1 = solved)
LeverPullingPerformance$site: code of each field site.
LeverPullingPerformance$habitat: rural (urban score < 0) or urban (urban score > 0) habitat type.
LeverPullingPerformance$age: age class � adult or juvenile.
LeverPullingPerformance$sex: female or male.


PaperRippingPerformance.csv: Contains data on characteristics of individuals and measures from paper-ripping trials sorted to recreate the reported extended cox regression analysis.

Column: Description

PaperRippingPerformance$indiv: individual band number identification.
PaperRippingPerformance$latency: latency to solve or become censored in the paper-ripping trials.
PaperRippingPerformance$status: censoring status of latency to solve the paper-ripping task used for cox regression (0 = censored, 1 = uncensored).
PaperRippingPerformance$tstart: start time (in seconds) of each time interval used for the extended cox regression.
PaperRippingPerformance$tstop: stop time (in seconds) of each time interval used for the extended cox regression.
PaperRippingPerformance$contacts: number of contacts made with the task in each time interval.
PaperRippingPerformance$domscore: dominance score based on interactions between birds at RFID feeders.
PaperRippingPerformance$urbanscore: urbanization score generated by PCA analysis used to infer degree of urbanization at each site.
PaperRippingPerformance$explscore: exploration score generated by PCA analysis.
PaperRippingPerformance$solve: indicator of whether the task was solved in each time interval (0 = unsolved, 1 = solved).
PaperRippingPerformance$site: code of each field site.
PaperRippingPerformance$habitat: rural (urban score < 0) or urban (urban score > 0) habitat type.


Persistence&Repeatability.csv: Contains data on the characteristics of individuals and measures from problem-solving trials used for the analysis of predictors of persistence and repeatability of problem-solving performance.

Column: Description

Persistence&Repeatability$capturedate: date (yyyymmdd) that each bird was captured
Persistence&Repeatability$site: code of each field site.
Persistence&Repeatability$indiv: individual band number identification
Persistence&Repeatability$age: age class � adult or juvenile.
Persistence&Repeatability$sex: female or male.
Persistence&Repeatability$habitat: rural (urban score < 0) or urban (urban score > 0) habitat type.
Persistence&Repeatability$urbanscore: urbanization score generated by PCA analysis used to infer degree of urbanization at each site.
Persistence&Repeatability$explscore: exploration score generated by PCA analysis.
Persistence&Repeatability$domscore: dominance score based on interactions between birds at RFID feeders.
Persistence&Repeatability$lpsolve: whether the lever-pulling task was solved (Y) or not (N).
Persistence&Repeatability$lplatency: latency to solve or become censored in the lever-pulling trials.
Persistence&Repeatability$lpstatus: censoring status of latency to solve the lever-pulling task used for cox regression (0 = censored, 1 = uncensored).
Persistence&Repeatability$lpcontacts: total number of contacts made with the lever-pulling task until the bird solved the task or the observation became censored.
Persistence&Repeatability$prsolve: whether the paper-ripping task was solved (Y) or not (N).
Persistence&Repeatability$prlatency: latency to solve or become censored in the paper-ripping trials.
Persistence&Repeatability$prstatus: censoring status of latency to solve the paper-ripping task used for cox regression (0 = censored, 1 = uncensored).
Persistence&Repeatability$prcontacts: total number of contacts made with the paper-ripping task until the bird solved the task or the observation became censored

