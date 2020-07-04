# MITBIH_Arrhythmia_Database_Basic
- Basic how to view and use MITBIH Arrhythmia Database

## Repo Outline:
- MITBIH_basic_info.ipynb [Click Here](https://github.com/triarts/MITBIH_Arrhythmia_Database/blob/master/MITBIH_basic_info.ipynb)
  - Basic view of MITBIH dataset, including how to load data, Patient Metadata(Header), Gender, Channel, Categorize based on channel.
- MITBIH_save_to_csv.ipynb [Click Here](https://github.com/triarts/MITBIH_Arrhythmia_Database/blob/master/MITBIH_save_to_csv.ipynb)
- MITBIH_save_to_numpy.ipynb [Click Here](https://github.com/triarts/MITBIH_Arrhythmia_Database/blob/master/MITBIH_save_to_numpy.ipynb)

## Dataset Source: 
  - https://physionet.org/content/mitdb/1.0.0/

## About Database: [(source)](https://physionet.org/content/mitdb/1.0.0/)
The MIT-BIH Arrhythmia Database contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects studied by the BIH Arrhythmia Laboratory between 1975 and 1979. Twenty-three recordings were chosen at random from a set of 4000 24-hour ambulatory ECG recordings collected from a mixed population of inpatients (about 60%) and outpatients (about 40%) at Boston's Beth Israel Hospital; the remaining 25 recordings were selected from the same set to include less common but clinically significant arrhythmias that would not be well-represented in a small random sample.

The recordings were digitized at `360 samples per second` per channel with 11-bit resolution over a 10 mV range. Two or more cardiologists independently annotated each record; disagreements were resolved to obtain the computer-readable reference annotations for each beat (approximately 110,000 annotations in all) included with the database.

This directory contains the entire MIT-BIH Arrhythmia Database. About half (25 of 48 complete records, and reference annotation files for all 48 records) of this database has been freely available here since PhysioNet's inception in September 1999. The 23 remaining signal files, which had been available only on the MIT-BIH Arrhythmia Database CD-ROM, were posted here in February 2005.

Much more information about this database may be found in the MIT-BIH Arrhythmia Database Directory.


## Annotation beats:
  - Table view: https://archive.physionet.org/physiobank/database/html/mitdbdir/tables.htm#allbeats
  - Annotation List: https://archive.physionet.org/physiobank/annotations.shtml
  
## Additional info:
  - WFDB documentation: https://wfdb.readthedocs.io/en/latest/wfdb.html
  - Sampling rate: https://www.researchgate.net/post/Whats_the_Sampling_Period_of_the_ECG_signal_in_MIT-BIH_database
  - AAMI standard: https://www.researchgate.net/figure/Mapping-the-MIT-BIH-Arrhythmia-types-to-the-AAMI-Classes_tbl1_267411759
  - ECG paper review: https://www.sciencedirect.com/science/article/pii/S0169260715003314
  
  
## Core Requirement
  - `pip install wfdb`
  - `pip install numpy == 1.16.5`

---
```
**Please consider give  a star if you find this Repo is useful! :D**
```
