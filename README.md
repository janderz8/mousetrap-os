# Mousetrap plugin for OpenSesame

__Easily build mouse-tracking experiments with OpenSesame.__

[![DOI](https://zenodo.org/badge/22029/PascalKieslich/mousetrap-os.svg)](https://zenodo.org/badge/latestdoi/22029/PascalKieslich/mousetrap-os)

The mousetrap plugin provides two items that implement mouse-tracking in [OpenSesame](http://osdoc.cogsci.nl/).
Both offer different ways of implementing mouse-tracking:

![alt text](plugins/mousetrap_response/mousetrap_response_large.png "mousetrap_response plug-in") The [mousetrap_response item](plugins/mousetrap_response/mousetrap_response.md) tracks mouse movements while another stimulus (e.g., a sketchpad) is presented.

![alt text](plugins/mousetrap_form/mousetrap_form_large.png "mousetrap_form plug-in") The [mousetrap_form item](plugins/mousetrap_form/mousetrap_form.md) allows tracking of mouse movements in custom forms specified using OpenSesame script.

More information about each item can be found in the corresponding helpfile (as linked above).
Besides, a number of example experiments that demonstrate the basic features of the items can be found in the [examples folder](examples).

Once data have been collected with the mousetrap plugin, the data can be processed, analyzed and visualized using the [mousetrap R package](https://github.com/PascalKieslich/mousetrap).


## General information
Mousetrap is developed by Pascal Kieslich and Felix Henninger.

It is published under the [GNU General Public License (version 3)](LICENSE).

## Installation

### Latest stable version

To install the latest release, please run the following commands in OpenSesame's [debug window](http://osdoc.cogsci.nl/manual/interface/#the-debug-window):

```python
import pip
pip.main(['install', 'https://github.com/PascalKieslich/mousetrap-os/archive/stable.zip'])
```

You'll need to restart OpenSesame after the installation for the mousetrap items to work.

If the installation fails due to missing write access, you may have to run OpenSesame with administrator privileges for the installation (on Windows, right-click the OpenSesame program icon and select [Run as Administrator](https://technet.microsoft.com/en-us/library/cc732200.aspx)).

The [installation of plugins](http://osdoc.cogsci.nl/manual/environment/#installing-plugins-and-extensions) is covered in more detail in the OpenSesame documentation, which also covers alternate methods. To install mousetrap manually, please download the archive attached to the [latest release](https://github.com/PascalKieslich/mousetrap-os/releases/latest)

[Release notes for the latest version](https://github.com/PascalKieslich/mousetrap-os/releases/latest) are available, as for all [previous releases](https://github.com/PascalKieslich/mousetrap-os/releases).

### Development version

To install the latest development version, please follow the above instructions, replacing the command with the following:

```python
import pip
pip.main(['install', 'https://github.com/PascalKieslich/mousetrap-os/archive/master.zip'])
```


## Mailing list

If you would like to receive information about new releases, you can add your email to the [mailing list](http://eepurl.com/co1AqX).


## Citation

If you use mousetrap in your published research, we kindly ask that you cite it as follows:

Kieslich, P. J., & Henninger, F. (2016).
Mousetrap: Mouse-tracking plugins for OpenSesame (Version 1.2.1).
doi:
[10.5281/zenodo.163404](https://doi.org/10.5281/zenodo.163404)


## Acknowledgments
Mousetrap extends the many useful features of OpenSesame developed by the [OpenSesame development team](http://osdoc.cogsci.nl/team/) led by [Sebastiaan Mathôt](http://www.cogsci.nl/smathot).
Mousetrap uses modified icons from the [Moka Icon Theme (by Sam Hewitt)](https://snwh.org/moka). We thank Anja Humbs for testing a development version. This work was supported by the University of Mannheim’s Graduate School of Economic and Social Sciences, which is funded by the German Research Foundation.
