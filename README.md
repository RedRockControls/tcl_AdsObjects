# tcl_AdsObjects

This library is intended for use in Beckhoff TwinCAT3 projects. 

It implements wrapper classes for Beckhoff ADS function blocks to provide a consistent object-oriented interface.

Unit tests are included that use the tcl_TwinCAT_UnitTestLibrary, which can be found at:
[tcl_TwinCAT_UnitTestLibrary](https://github.com/RedRockControls/tcl_TwinCAT_UnitTestLibrary)

Tests can be run in the library project, or instantiated and tested in the TwinCAT project that uses the library by declaring an instance of the function block TestSuite_AdsTests and executing it.

