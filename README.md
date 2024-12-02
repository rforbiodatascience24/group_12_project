# Group_12_project

## Project contributors

*Name - Study number - Github name:*

Agnes Lorenzen - s194692 - AgnesDTU

Cecille J. E. Hobbs - s203542- CecilleHobbs

Freja E. Klippmann - s205803 - FRELI17

Julie Dalgaard Petersen - s204570 - juldp

Mille Rask Sander - s203556 - MilleRask

All group members have contributed equally to the project and data discussions.

## Description

Polycystic ovary syndrome, abbreviated PCOS, is a disease documented in women, that affects their hormone and reproductive health. However, it has not been reported what the cause of PCOS is or if there are any health-related triggers. Most individuals suffering from PCOS experience irregular periods, follicles and ovary-related problems, and increased hormone production [1]. Furthermore, PCOS has been correlated with causing a risk of potential complications in regards to pregnancy [2].

There have been many speculations, as to what causes PCOS. Some of the reported factors that may influence PCOS have been stated to be: increased male-related hormones (e.g. androgens) and increased insulin [2]. As of now, there is no treatment for PCOS, however, most symptoms can be managed to the patient’s need.

## Purpose

The purpose of this study is to test if there is any relationship between PCOS and some common PCOS-associated factors. In the grander scheme, the aim is to investigate whether there is a correlation between some of the most popular PCOS disease factors and whether it may be more of a causality.

## Data

The dataset used for this analysis has been published on Kraggle and created by the author Prasoon Kottarathil and consists of data collected from 10 hospitals across Kerala, India [4]. The dataset consists of various factors, belonging to clinical and physical variables. The cleaned dataset consist of the following:

**Variable *- unit***

| Variable | PCOS_diagnosis | age    | weight | height | pulse | breaths_pr_min | hemaglobin | cycle_RI            | period_length | Col11 | Col12 | Col13 | Col14 | Col15 | Col16 | Col17 | Col18 | Col19 | Col20 | Col21 | Col22 | Col23 | Col24 | Col25 | Col26 | Col27 | Col28 | Col29 | Col30 | Col31 | Col32 | Col33 | Col34 | Col35 | Col36 | Col37 | Col38 |
|-----|--------|----|-----|-----|----|-----|-------|-----|-----|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|-----------|
| Unit     | (yes/no)       | (year) | (kg)   | (cm)   | (bpm) | (breaths/min)  | (g/dl)     | (regular/irregular) | (days)        |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |

PCOS_diagnosis - *(yes/no)*

age - *(years)*

weight - *(kg)*

height - *(cm)*

pulse - *(bpm)*

breaths_pr_min - *(breaths/min)*

hemaglobin - *(g/dl)*

cycle_RI - *(regular/irregular)*

period_length - *(days)*

pregnant - *(yes/no)*

abortions - *(yes/no)*

bethaHCG_1 - *(mIU/mL)*

betaHCG_2 - *(mIU/mL)*

FSH - *(mIU/mL)*

LH - *(mIU/mL)*

FSH_LH_ratio - *(mIU/mL)*

hip - *(cm)*

waist - *(cm)*

TSH - *(mIU/mL)*

AMH - *(ng/mL)*

PRL - *(ng/mL)*

vitaminD3 - *(ng/mL)*

PRG - *(ng/mL)*

RBS - *(mg/mL)*

weight_gain - *(yes/no)*

hair_growth - *(yes/no)*

darker_skin - *(yes/no)*

hair_loss - *(yes/no)*

pimples - *(yes/no)*

exercise - *(yes/no)*

BP_systolic - *(mmHg)*

BP_diastolic - *(mmHg)*

follicle_no_R - *(count)*

follicle_no_L - *(count)*

avg_fsize_L - *(mm)*

avg_fsize_R - *(mm)*

endometrium - *(mm)*

## Usage

For usages of the data, please download “R/00_all.qmd” on an RStudio server to achieve the results from this data analysis.

## References

[1] Polycystic ovary syndrome, Mayo Clinic. Accessed: 22 November 2024. Link: <https://www.mayoclinic.org/diseases-conditions/pcos/symptoms-causes/syc-20353439>

[2] Polycystic Ovary Syndrome (PCOS), Cleveland Clinic. Accessed: 22 November 2024. Link: <https://my.clevelandclinic.org/health/diseases/8316-polycystic-ovary-syndrome-pcos>

[3] Polycystic Ovary Syndrome (PCOS), Johns Hopkins Medicine. Accessed: 22 November 2024. Link: <https://www.hopkinsmedicine.org/health/conditions-and-diseases/polycystic-ovary-syndrome-pcos>

[4] Kottarathil, Prasson (2020). Polycystic ovary syndrome (PCOS). Kaggle dataset, retrieved from link: <https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos>
