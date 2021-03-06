# CAMPAIGN MONITOR MODULE FOR FUEL CMS
This is a [FUEL CMS](http://www.getfuelcms.com) campaign_monitor module which can be used to display summary campaign information from Campaign Monitor.

## INSTALLATION
There are a couple ways to install the module. If you are using GIT you can use the following method
to create a submodule:

### USING GIT
1. Open up a Terminal window, "cd" to your FUEL CMS installation then type in: 
Type in:
``php index.php fuel/installer/add_git_submodule https://github.com/daylightstudio/FUEL-CMS-Google-Keywords-Module.git campaign_monitor``

2. Then to install, type in:
``php index.php fuel/installer/install campaign_monitor``


### MANUAL
1. Download the zip file from GitHub:
[https://github.com/daylightstudio/FUEL-CMS-Campaign-Monitor-Module](https://github.com/daylightstudio/FUEL-CMS-Campaign-Monitor-Module)

2. Create a "campaign_monitor" folder in fuel/modules/ and place the contents of the campaign_monitor module folder in there.

3. Then to install, open up a Terminal window, "cd" to your FUEL CMS installation then type in:
``php index.php fuel/installer/install campaign_monitor``

## UNINSTALL

To uninstall the module which will remove any permissions and database information:
``php index.php fuel/installer/uninstall campaign_monitor``

### TROUBLESHOOTING
1. You may need to put in your full path to the "php" interpreter when using the terminal.
2. You must have access to an internet connection to install using GIT.


## DOCUMENTATION
To access the documentation, you can visit it [here](http://docs.getfuelcms.com/modules/campaign_monitor).

## TEAM
* David McReynolds, Daylight Studio, Main Developer

## BUGS
To file a bug report, go to the [issues](https://github.com/daylightstudio/FUEL-CMS-Google-Keywords-Module/issues) page.

## LICENSE
The campaign_monitor Module for FUEL CMS is licensed under [APACHE 2](http://www.apache.org/licenses/LICENSE-2.0).