Further improvement of a NO to NO2 converter for CE-DOAS measurements
======================================================================

This is my Bachelorthesis form the year 2016. It is concerned with the
improvement of the above mentioned converter. A CE-DOAS instrument is
used to determine atmospheric trace gases, in my case nitrogen dioxide
(NO2). Unfortunately in the current configuration it is not possible
to measure nitrogen monoxide directly. Hence the need for a
converter.

The thesis covers the basic principle for DOAS measurements, the
chemical background needed for the conversion and some calibration
measurements including the evaluations.

Abstract
--------
This bachelor thesis aims at a further improvement of a nitrogen monoxide (NO) to nitrogen dioxide (NO2) converter, which will be used in conjunction with a NO 2 ICAD instrument to measure the nitrogen oxide (NOx) pollution in urban areas. The main component
of this converter is an ozone generator. This work succeeded in making its output NO2 free,
thus making its use in the converter possible. Next, a characterization of the converter was
performed and the possible NO measurement accuracy was determined. Moreover, first
productive applications were tested by performing live vehicle measurements in Heidelberg. There are still further investigations necessary to reach the full potential of this setup.
First and foremost, the adsorption behavior of ozone at the teflon walls of the tubes has to
be investigated in order to allow for more practical measurement modes.

Building the thesis
-------------------

This thesis was built on a linux system using the `tex-live-full` package. The packages I used make it necessary to use `xelatex` to build it (`pdflatex` will fail). The following commands should build the thesis:
```bash
git clone git@github.com:Emrys-Merlin/Bachelor-Physics.git .
cd Bachelor-Physics
xelatex Bachelor.tex
biber Bachelor
xelatex Bachelor.tex
```
Afterwards you should find a `Bachelor.pdf` file in your working directory.
