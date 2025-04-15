^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package esc
^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Merge pull request `#1 <https://github.com/HippoCampusRobotics/esc/issues/1>`_ from VincentTUHH/main
  fixed bug of success status of arming service
* fixed bug of success status of arming service
* added README
* Contributors: Nathalie Bauschmann, Thies Lennart Alff, VincentTUHH

1.1.0 (2024-07-16)
------------------
* removed legacy python version of afro esc commander
* Contributors: Thies Lennart Alff

1.0.0 (2024-07-16)
------------------
* moved esc to separate repo
* make logging less overly verbose
* streamlined esc launch file
* refactored batterystate publishing
* migrated to sensor_msgs batterystate
* added docs for inputmapping in teensy esc commander
* make thrust mapping based on voltage in esc commander optional
* ditched yapf
* migrated to hippo_control_msgs
* do not try to set throttle for unavailable thrusters.
* set compatible QoS and working default i2c bus
* Niklas' changes squashed
* catch ctrl+c keyboard interrupt to avoid unhandled exceptions that are
  part of the 'normal usage'
* added pre-commit hooks
* added licenses and applied formatting to all source files
* added launch files
* changed default serial_port to reasonable value
* keep readiing bytes after errenous packet has been received
* added namepace
* fixed wrong conversion from mV to V
* publish actual thruster values
* implemented arming service and message handler
* implemented timers and publishers
* submodule updated
* simplified packet creation
* updated submodule
* added read/write serial functionality
* teensy commander implementation continued
* updated esc_serial submodule
* added submodule/teensy code
* added missing algorithm include
* reverted from clamp to min/max
* publish thruster commands on message arrival
* added compiler optimizations
* fixed issue with valid esc voltage count
* advertise battery topic
* let esc_commander publish battery voltage
* clean up of esc code
* sending zero throttle when arming at least once
* fixed arming check for esc
* improved logging
* added arming state publisher for esc
* added arming service for esc
* minor refactorings
* added compiler flags
* added esc package
* Contributors: Thies Lennart Alff
