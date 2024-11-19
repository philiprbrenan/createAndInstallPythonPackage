<div>
    <p><a href="https://github.com/philiprbrenan/createandInstallPythonPackage"><img src="https://github.com/philiprbrenan/createandInstallPythonPackage/workflows/Test/badge.svg"></a>
</div>

# Create, Install and Run a Python package

This action uses **build** to create a **.whl** file containing the comamnd
line application app described in the **.toml** file.

The action then installs the app contained in the **.whl** file in a different
folder and a different python virtual environment and executed to verify that the
action has suceeded.

Documentation for [building packages.](https://setuptools.pypa.io/en/latest/userguide/quickstart.html)

Documentation for  [toml files.](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/#writing-pyproject-toml)

Documentation for your project should not be included in the **.whl** file, but
instead it should be added to a web site convenient to you and then referenced
via **Urls** as described in: [project urls](https://packaging.python.org/en/latest/guides/writing-pyproject-toml/#urls)
