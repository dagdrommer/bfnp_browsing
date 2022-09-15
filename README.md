# BFNP_browsing

Browsing prediction based on site information in the BFNP

## ToDo

1. Merge Data

## Possible Models

1. GLMER, then Random forest (Kupderschmid 2019)

2. Generalized Geoadditive Mixed Model

## Current issues

### Dafuer habe ich Daten aber keine Koordinaten (alle Flachen) `dbp[! dbp %in% plot]`

 [1] "FRG-2282010" "FRG-2282018" "RLG-6134139" "RLG-6134143" "RLG-6138131" "RLG-6138135" "RLG-6142135"
 
 [8] "RLG-6142139" "SNP-259"     "SNP-262"     "SNP-266"     "SNP-267"

### *Dafuer habe ich aus Sumava daten, aber keine Koordinaten in GIS*

*"154" "178" "197" "199" "259" "262" "266" "267"*

### *Fuer den NP fehlen Koordinaten zu den Datenpunkten (Koord) (nur relevant, wenn 2015 und/oder 2021 auch einbezogen werden sollen)*

*[1] 2078064 2210034 2218018 2218034 2226002 2234002 2274004 3242082 3250106 3258114 3266122 4202130 5046112*

*[14] 5070096 5086080 5086098 5094040 5094088 5118080*

*kursiv* in Bearbeitung von Marc

## Infos zu Rasterdaten

- Habitate nur fuer BFNP und halben Sumava (ausser SECR red deer)
- LIDAR Metriken nur fuer BFNP
