Aum Amma

## Installing Django

Please ensure python3 and pip are installed, if not already installed.

To install on Windows, go to https://docs.djangoproject.com/en/4.0/howto/windows/
- Open Command prompt
- Upgrade pip
  > python -m pip install --upgrade pip <br>
- Navigate to a folder where you want to create a project
- Create a virtual environment
  > python -m venv myenv <br>
- Change directory to the virtual environment and examine the contents
  > cd myenv <br>
  > dir <br>
  * Include/
  * Lib/
  * pyveng.cfg
  * Scripts
- Activate the virtual environment
  > python -m venv myenv <br>
- Install Django
  > python -m pip install Django
- Verify you Django installation
  > django-admin --version