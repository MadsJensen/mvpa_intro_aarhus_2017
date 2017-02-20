Hi all,

I little information regarding the practical aspecst of the workshop.

There is a google drive folder:

- (https://drive.google.com/drive/folders/0B1fYmfwNJfjiZXFmODdkSXVKU0E?usp=sharing)

This has the Jupyter Notebooks and other resources we will use at the workshop and help to setup the python we will need. 


# Requirements for the workshop

You should bring your own laptop with a hard drive (no Chromebooks or tablet-/surface-type devices are supported). Any reasonably modern (< 5-year-old) Windows, OS X or Linux operating system will do. The following software should be installed:

- Python 3.5 or above
- jupyter notebook
- ipython 
- mne-python (version 13.1 or above)
- scikit-learn (version 18.1 or above)
- pandas (version 19.2 or above)
- numpy (version 1.11 or above)

Some of the scikit-learn functions changed from 17 to 18 so it is important to have 18.1 or above.

To install the packages need, install anaconda python distribution from [continuum.io](https://www.continuum.io/downloads), then download the requirements.txt (in the google drive folder) and from a terminal run:

``` python
    conda create -n mne python=3.5 --file requirements.txt

```

then:
```python
    source activate mne
```

finally:
``` python
    pip install mne
```


If you want the mne to be your standard python, after the installation type in the terminal:


OSX:

``` bash
    echo "source activate mne" >> .bash_profile 

```

Linux:
``` bash
    echo "source activate mne" >> .bashrc

```

Windows:
No idea, sorry.

##
We will be using Jupyter Notebooks for the tutorials, so please spend a few minutes to try one if you have not tried them before, see below for suggestions but there are many others tutorials online. 

# Additional resources 
- [Jupyter notebook quick start](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/)
    - http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/
- [Jupyter notebook tutorial video](https://www.youtube.com/watch?v=HW29067qVWk) 
    - https://www.youtube.com/watch?v=HW29067qVWk
