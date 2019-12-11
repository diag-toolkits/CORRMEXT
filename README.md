## About CORRMEXT ##
CORRMEXT is an open-source resource use data and message logs analysis toolkit. It is developed using C++. The toolkit uses a configuration file. In the configuration file, the user can specify: (i) the directory for the resource use data, (ii) the directory for the message logs, (iii) the names of the resource use counters, (iv) the names of message types, (v) the year for the message logs, and (vi) the correlation method. When the toolkit is executed using the configuration file, it automatically executes the CORRMEXT workflow and generates the correlation reports. The reports can then be used for diagnosis.

## Obtain CORRMEXT ##
A 64-bit version compiled for Linux is available for downloading [here.](https://tinyurl.com/y7wpv488)  If you have an enquiry about the tool, feel free to get in touch with me. (Email: echuah@turing.ac.uk or edwardchuah@acm.org)

## Install CORRMEXT ##
Unzip the file into a directory of your choice.  Add `[directory]/corrmext/toolkit/DiagTK/Release` to the directory path in your favourite Linux shell.  First, run the command `diagtk -generateCfgFile` to create a configuration file.  An empty config-file with default name *cfgfile* will be generated.  Fill the configuration file with your requirements.  Then, run the command `diagtk -autorunCORRMEXT [config-file]` where `[config-file]` is the name of the configuration file.

## Acknowledgement ##
This research was supported by The Alan Turing Institute under the EPSRC, UK grant EP/N510129/1 and The Alan Turing Institute-Intel partnership,
