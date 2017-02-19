# Requirements for the workshop

you should bring your own laptop with a hard drive (no Chromebooks or tablet-/surface-type devices are supported). Any reasonably modern (< 5-year-old) Windows, OS X or Linux operating system will do. The following software should be installed:

- Python 3.5 or above
- jupyter notebook
- ipython 
- mne-python (version 13.1 or above)
- scikit-learn (version 18.1 or above)
- pandas (version 19.2 or above)
- numpy (version 1.11 or above)

Some of the scikit learn functions changed from 17 to 18 so it is important to have 18.1 or above.

To install the packages need, install anaconda python distribution from [continuum.io](https://www.continuum.io/downloads), then download the requirements.txt (link) and from a ternimal run:

conda create -n mne python=3.5 --file requirements.txt

then: source activate mne
finally: pip install mne


if you want the mne to be your standard python, after the installation type in the terminal:

MacOS:
echo "source activate mne" >> .bash_profile 

Linux:
echo "source activate mne" >> .bashrc

Windows:
No idea, sorry.



## Additional resources 

[Jupyter notebook](https://www.youtube.com/watch?v=HW29067qVWk) 
