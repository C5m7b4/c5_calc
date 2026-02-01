# Calculator 🧮

To install for development, make sure you are in the root directory and run this command:

```bash
pip install -e .
```

The -e is for `editable` and will automatically update your package while you are testing.

ℹ️ If you want to test the library, you can use the `scripts` folder to store all your junk. You can also put Jupyter notebooks in there so you can further play with the library.

Also as a pre-req you need to install these packages if you are just getting started

```bash
py -m pip install twine build
```

Then to build your package for deployment to Pypi

```bash

py -m build
```

To publish the package, run this command:

```bash

twine upload dist/* --skip-existing
```

now you can install your package from Pypi

```bash
pip install c5_calc
```




