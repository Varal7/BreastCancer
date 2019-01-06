# Breast Cancer Outcome Caculator

CSV to CSV utility for [Breast Cancer Outcome Calculator](http://www.lifemath.net/cancer/breastcancer/outcome/index.php)

## Installation

Requires node and npm

```
npm install
```

## Usage

```
node index.js example.csv output.csv
```

## Expected input

* age                                                      
* diameter in cm
* nodenumber - if unknown, set to -1
* erstatus - 0 unk - 1 pos - 2 neg
* prstatus - 0 unk - 1 pos - 2 neg
* her2status - 0 unk - 1 pos - 2 neg
* histology
    - 0 - Unknown
    - 1 - Ductal
    - 2 - Lobular
    - 3 - Intraductal+LCIS
    - 4 - Mucinous
    - 5 - Medullary
    - 6 - Tubular
    - 7 - Comedo
    - 8 - Scirrhous
    - 9 - Inflammatory
    - 10 - Paget's disease
    - 11 - Papillary
    - 12 - Cribiform
    - 13 - Apocrine
    - 14 - Phyllodes
* grade  - 0 unk - 1 well diff - 2 moder diff - 3 poor diff


## Notice

James Michaelson PhD  
May be freely used for any scientific purpose; 
For permission to use commercially or in a website,  
contact Dr. Michaelson at james.michaelson@gmail.com  
For the mathematical essentials used below, see:  
Michaelson JS et al. "The effect of tumor size and lymph node status on breast carcinoma lethality"  
Cancer. 2003;98:2133-2143.
