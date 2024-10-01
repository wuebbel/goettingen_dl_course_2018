# Clone of J. Adlers github repository

This is a clone of J. Adlers repository adler-j/goettingen_dl_course_2018. The repository contains the course material (input and output) for the "Mathematics of deep learning with an emphasis on inverse problems" course at Göttingen 2018. Several typos from the original were corrected. See the second commit for all changes.

## Installing Dependencies

The latest version of ODL and some supporting libraries are needed in order to use these notebooks. See the [installation instructions](code/part0_install.ipynb) for further information.

## Jupyter Notebooks

Part of the material will be published as [Jupyter notebooks](http://jupyter.org/). If you're familiar with Mathematica notebooks, you won't be surprised.

To install the notebook software, you can either use `conda`:

    conda install notebook

or `pip`:

    pip install notebook

You can then start the software by running

    jupyter notebook

in a terminal. Sometimes one gets `OSError: [Errno 99] Cannot assign requested address`. In this case an explicit IP has to be given, which should be the equivalent to `localhost` in your case:

    jupyter notebook --ip=127.0.0.1

The notebooks can also be viewed online as static HTML pages. This works (somewhat) on GitHub directly, but better with [nbviewer](https://nbviewer.jupyter.org/). Just copy the URL of the notebook into the text field at that page.

## Feedback

If you find any errors or experience issues, please get back to us ([@ozanoktem](https://github.com/ozanoktem) or [@adler-j](https://github.com/adler-j)) or [create an issue](https://github.com/adler-j/odlworkshop/issues/new).
