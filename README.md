# Sardana Users Questionnaire

## Acquisition

* [bool] Do you use timerable channels
    * do you use different timers depending on the application
    * do you use per measurement preparation
    * do you use per acquisition preparation
    * do you use single acquisition
* [bool] Do you use counter/timer
    * do you use the monitor mode?
* [bool] Do you use 1D or 2D
    * do you use value referencing (SEP2)
    * do you use value referencing pattern (SEP2)
* [bool] Do you use 0D
    * [multi] what function do you apply on the buffer?
    * [new] [open] do you need other functions, which?
    * [new] do you need single acquisition
* [bool] Do you use pseudo counter
    * [new] do you need single acquisition
    * [new] do you need generic pseudo counter (dynamic roles)
* [bool] Do you use measurement group acquisition?
    * [bool] Do you change measurement group configuration?
       * Do you use enabled configuration parameter? And the same for the next ones:
       * output
       * shape
       * data type
       * plot type
           * Spectrum
           * [new] Image
       * plot axes
           * <idx>
           * <mov>
       * timer
       * monitor
       * synchronizer
       * synchronization
       * [new] conditioning
       * [new] normalization
       * nexus path
* [bool] do you use continuous scans
    * [new] do you need timestamps
    * [new] do you need direct integration of Taurus attributes (no need to define a controller)?
   
# Motion

* [bool] Do you use physical motor controllers?
    * Do you use backlash correction
    * Do you use software limits protection
    * Do you use user position transofrmation (steps_per_unit, offset, sign).
    * Do you use dial position?
    * Do you use base_rate?
* [bool] Do you use grouped motion (pseudo motors or motor groups):
    * Do you use emergency break
* [bool] Do you use pseudo motor controllers?
    * Do you use various levels of pseudo motors.
    * Do you use drift correction.   
* [bool] Do you use DiscretePseudoMotors
* [bool] Do you use HKL Pseudo Motors.
