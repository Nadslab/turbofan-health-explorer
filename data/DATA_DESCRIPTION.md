# CMAPSS FD001 Data Description

Source: NASA CMAPSS turbofan engine simulated data (FD001 subset)
Files: train_FD001.txt, test_FD001.txt, RUL_FD001.txt
Format: whitespace-separated text, no header row

Columns:
- unit  int  Engine identifier
- cycle  int  Cycle index within an engine trajectory
- op1  float  Operating setting 1
- op2  float  Operating setting 2
- op3  float  Operating setting 3
- s1..s21  float  Sensor measurements per cycle

Totals:
- 26 columns  2 identifiers, 3 operating settings, 21 sensors

Processed small file saved to data/processed/train_FD001_small.parquet
