# Clone of J. Adlers github repository

This is a clone of J. Adlers repository adler-j/goettingen_dl_course_2018. The repository contains the course material (input and output) for the "Mathematics of deep learning with an emphasis on inverse problems" course at Göttingen 2018. Several typos from the original were corrected. See the second commit for all changes.

# Running the code on University of Münster central jupyterhub
Note: Should you have problems installing odl, use pip install https://www.uni-muenster.de/AMM/num/assets/odl-1.0.0.dev0-py2.py3-none-any.whl.

Follow the commands.

1. Sign in to https://jupyterhub.wwu.de/.
2. Log in with your university of Münster account.
3. On the configuration page, choose memory 8GB-16GB and any vGPU (e.g.
NVIDIA TESLA M10) (but not "no vGPU support").
4. Leave everything else as is and click on start.
5. Open a new python notebook by clicking on the "+" above the file manager
and choosing "Python 3 (ipykernel)".
6. In the newly opened notebook, type
```! git clone https://www.github.com/wuebbel/goettingen_dl_course_2018 ```
Run the code by clicking on the triangle above the notebook, typing
shift-return or selecting "Run All Cells" from the "Run" Menu.
Check that some code is downloaded.
7. Close the notebook. In the pane on the left hand side, there should now
be a folder "goettingen_dl_course_2018".
9. Open it and go to code.
10. Open part0_install.ipynb.
11. Run the notebook by selecting "Run"->"Run all cells". Check that no
errors are produced.
12. Open part1_tv_denoising.ipynb. Again, run all cells, and check that no
errors are produced. You might also check whether the images look correct.
13. Do the same for the other notebooks (except for the exercises).

# Original comment
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
