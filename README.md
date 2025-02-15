# OpenInSAR
OpenInSAR is a system for SAR and InSAR time series analysis.

This software will undergo extensive refactoring and development over the course of a 2 year project.

This current version was developed through a PhD project at Imperial College London. The accompanying thesis will be available [here when finalised](https://spiral.imperial.ac.uk/simple-search?location=%2F&query=Transient+Scattering&rpp=1&sort_by=score&order=desc&filter_field_1=author&filter_type_1=equals&filter_value_1=Agar).

### Get started
[Running an analysis in Matlab/Octave](https://github.com/insar-uk/OpenInSAR/blob/main/doc/quickstart_guides/Matlab_and_Octave.md)


### Requirements
OpenInSAR is designed to be highly portable. Currently, the only interface is Matlab, we are working on Python and C++ entry points.

#### Matlab/Octave
- Matlab 2021a (or later)
- [OR] Octave 7.2.0 (or later)
- wget

#### Python
Many of the interactive elements of OpenInSAR require Python, and have been tested using:
- Python 3.11
- PyQt5 5.15.4

Please see the [Python quickstart guide](https://github.com/insar-uk/OpenInSAR/blob/main/doc/quickstart_guides/Python_interactive.md)

### Software
Details of the software can be found in the [design directory](hhttps://github.com/insar-uk/OpenInSAR/blob/main/doc/design/). An interactive dashboard has been developed to provide an overview of the software and will by available soon.


### Testing

OI is tested on Windows 10 and Ubuntu 20.04.
In Matlab you can perform tests using:

```matlab
>> OI.Test()
```

An interactive testing dashboard has been developed and will be available soon.
