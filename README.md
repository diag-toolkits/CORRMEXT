CORRMEXT is an open-source resource use data and message logs analysis toolkit. It is developed using C++. The toolkit uses a configuration file, which is generated by using the command `diagtk -generateCfgFile`. In the configuration file, the user can specify: (i) the directory for the resource use data, (ii) the directory for the message logs, (iii) the names of the resource use counters, (iv) the names of message types, (v) the year for the message logs, and (vi) the correlation method. When the toolkit is executed using the configuration file, it automatically executes the CORRMEXT workflow and generates the correlation reports. The reports can then be used for diagnosis.

Download CORRMEXT [here.](https://tinyurl.com/y7wpv488)  
To execute, simply run `diagtk -autorunCORRMEXT [config-file]` where `[config-file]` is the name of the configuration file.
