PythonIDLE
==========

My Configurations about PythonIDLEs
# IDLE:
## Usage:

### Linux:
- Copy the .idlerc folder to `$HOME` folder
- Re-start IDLE

### Windows:
- Copy the .idlerc folder to `%HOMEPATH%`
- Re-start IDLE

## Specific Shortcuts:
- `Ctrl + p`: Previous history
- `Ctrl + n`: Next history
- `Ctrl + a`: Begin of the line
- `Ctrl + e`: End of the line
- `Alt + d`: Delete word right
- `Ctrl + w`: Delete word left
- `Alt + p`:  Print page
- `Alt + n`:  New page
- `Ctrl + Shift + a`: Select all


# IPython
## Installation

### Linux(Ubuntu)
- Mandatory
<pre><code>$ sudo apt-get install ipython
    Installed packages (automatic):
        python-configobj
        python-decorator
        python-simplegeneric
</code></pre>

- Optional
<pre><code>$ sudo apt-get install ipython-qfconsole  [Recommend]
    Installed packages (automatic):
        libpgm-5.1.0
        libzmq1
        python-pygments
        python-zmq
$ sudo apt-get install ipython-doc
$ sudo apt-get install notebook
$ sudo apt-get install python-matplotlib
$ sudo apt-get install python-numpy
</code></pre>

### Windows
- Mandatory
<pre><code>IPython:      pip install ipython
PyReadline:   pip install pyreadline 
</code></pre>

- Optional
<pre><code>Pygments:     pip instal Pygments
PyQt:         http://sourceforge.net/projects/pyqt/ 
PySide        easy_install pyside
</code></pre>

## Configuration
### Linux(Ubuntu)
- Copy the style file to `/usr/lib/python2.7/dist-packages/pygments/styles` folder
- Copy .config folder to `$HOME/.config`

### Windows
- Copy the Style file to `$PYTHONHOME\Lib\site-packages\pygments\sytles` folder.
    - For example: Copy `marslo.py` to `C:\Python27\Lib\site-packages\pygments\styles`
- Copy the `.ipython` to `%HOMEPATH%`
    - For example: Copy the whole `.ipython` foler to `C:\Users\<USERNAME>` (Win7); `C:\Documents and Settings\<USERNAME>` (Windows XP)

# Spyder2
## Installation
- Copy the `.spyder2` folder to `%HOMEPATH%`
    - For example: Copy the whole `.spyder2` foler to `C:\Users\<USERNAME>` (Win7); `C:\Documents and Settings\<USERNAME>` (Windows XP)
- Restart the spyder

# Screenshots
## IDLE Screenshots:
![IDLE1](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/IDLE_Marslo4.png?raw=true)
![IDLE2](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/Screenshot2.png?raw=true)
## IPython screenshots
- $ ipython
![IPython](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/ipython.png?raw=true)
- $ ipython qtconsole --IPythonWidget.font_size=12 --IPythonWidget.font_family=Monaco --color=linux --style=marslo
![IPython QTConsole](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/qfconsole.png?raw=true)
- $ ipython qtconsole against Windows (Using shortcurts: qtconsole)
![Ipython_qtconsole_windows](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/Ipython_Qtconsole_Windows.png?raw=true)

## Spyder
![Spyder](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/spyder.png?raw=true)
