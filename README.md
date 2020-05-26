# Bisa AI Data Engineering Competition 2020 Submission: 
# Epileptic Seizure EEG Dataset

## Deskripsi Data

Dataset yang berjudul “Epileptic Seizure EEG dataset” ini merupakan dataset fitur sinyal EEG pasien epilepsi pada saat pasien berada dalam dua keadaan, yaitu keadaan normal dan keadaan pada saat pasien mengalami kejang – kejang. Dataset ini bersumber dari [CHB-MIT](https://physionet.org/content/chbmit/1.0.0/). 

## Fitur Data
Pemilihan fitur data sinyal dilakukan dengan minjau fitur sinyal EEG apa saja yang umum digunakan yang terdapat pada paper yang berjudul [Deep learning-based electroencephalography analysis: a systematic review](https://iopscience.iop.org/article/10.1088/1741-2552/ab260c)

### Low level feature
Jumlah data low level feature: 4321 data (2161 kelas seizure + 2160 kelas normal)

__Time domain feature__
* Signal value mean
* Signal value variance
* Signal value standar deviance
* Signal value kurtosis
* Signal value skewness
* Signal value spectral centroid
* Signal value spectral entropy

__Frequency domain feature__
* Power spectral density mean
* Power spectral density variance
* Power spectral density standar deviance
* Power spectral density kurtosis
* Power spectral density skewness
* Ratio delta power in frequency bin
* Ratio theta power in frequency bin
* Ratio alpha power in frequency bin
* Ratio beta power in frequency bin

### High level feature
Jumlah data high level feature: 375 data (184 kelas seizure + 191 kelas normal)
* Spectrogram

![Spectogram](https://github.com/irfangirindra/bisa-ai-data-engineering-competition-2020/blob/master/fig/fig_spec.JPG)

## Download
Data dapat diunduh pada website dataset [BISA AI](https://bisa.ai/dashboard/Detail_dataset?id=8)

Dikarenakan data ini bersumber dari CHB-MIT, apabila ingin menggunakan data ini diharapkan untuk mencantumkan referensi sebagai berikut:
```
Ali Shoeb. Application of Machine Learning to Epileptic Seizure Onset Detection and Treatment. PhD Thesis, Massachusetts Institute of Technology, September 2009.
```

## Other Links

Report mengenai dataset ini dapat dilihat di [Medium BISA AI](https://medium.com/bisa-ai/report-dataset-kompetisi-data-engineering-4-epileptic-seizure-eeg-dataset-6b4fde4a4de9)
