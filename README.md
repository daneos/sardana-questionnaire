# Sardana Users Questionnaire

User interface components
=========================

General questions
-----------------

* What is your main interface to Sardana?
	- Spock
	- TaurusGUI
	- Other GUI application
	- Other


Spock
-----

* Do you use multiple Spock profiles? If so, what is the use case?
* Do you use Spock's built-in help (<macro>?)?
* Do you use tab completion?
* Which Spock syntax features do you use?
* Are you interested in using Python syntax to run macros?
* Do you configure experiment using macros or expconf widget?
* Do you use showscan for viewing scans/liveplotting?
* Do you use macrodata available in Spock?
* Do you edit macros using Spock features (edmac, etc...)?
* Are you interested in editing controllers with edmac?
* Do you use view options?
* Do you use Spock also as Python or Tango console?
* Are you interested in integrating Spock console into other applications?

MacroExecutor
-------------

* Do you use MacroExecutor?
* Do you use it as standalone application?
* Do you use favourites?
* Do you use history?
* Do you use duplication of repeat parameters?
* Do you use pause function?
* Do you edit commands manually in the yellow Spock line?
* Are you interested in using custom widgets for configuring macro execution?

Sequencer
---------

* Do you use Sequencer?
* Do you use it as standalone application?
* Do you save/load XML sequences?
* Do you load text sequences?
* Do you use pause/resume?
* Do you use stop at given macro feature?
* Are you interested in running a sequence starting from given macro instead of the beginning?

Experiment configuration
------------------------

* What do you use to configure experiment?
* Do you use Expconf widget?
* Are you happy about the configuration changes popup?
* Do you use advanced measurement group configuration?
* Do you use liveplotting provided by expconf?
* Do you use snapshot groups?
* How do you configure snapshot groups?
* Do you configure scan storage with expconf?
* Do you use newfile macro to work with scan storage?
* Would you be interested in experiment configuration macros?

MacroButton
-----------

* Do you use MacroButton/any GUI that uses MacroButton?

SardanaEditor
-------------

* Do you edit macros or controllers on-line?
* Do you use SardanaEditor?
* How do you manage custom macros and controllers?

ShowScan
--------

* Do you use ShowScan to view acquired data?
* Do you use ShowScan online for liveplotting?
* How do you launch ShowScan?
* How do you configure plotting?

Pool*TV widgets
---------------

* Do you use any of Pool*TV widgets/GUI that uses them?
* Do you use compact view?
* Are all symbols and labels clear?

Future features
---------------

* How can components mentioned above be improved?
* Is using Sardana user interface straightforward and convenient?
* What features are missing from the existing components?
* What other user interface components could be useful?

Other
-----

* What other interfaces not mentioned here do you use?

Macros
======

* [bool] Do you edit own macros
   - which editor/tool do you use to edit them
   - [bool] do you use Input parameters
     - do you set the input parameter type
     - do you set its default value
     - do you limit its range, sett decimal places or step size
   - do you use Optional parameters
   - do you use the parameter type Any
   - do you return values in your macros
   - [bool] do you call macros inside your macros
     - which call do you use for that
     - do you access the data from the macros you call
   - do you add programmed hooks to your macros
   - do you make your macros hookable
   - do you access the macroserver environment in your macros
   - [bool] do you write logs in your macros
      - at which level
   - do you use the Report facility
   - do you set PausePoints in your macros
   - do you define the on_abort or/and on_stop function
   - [bool] do you plot data directly from your macro
     - what do you use for that
   - do you implement the possibility of showing its progress
   - do you implement the execution of simultaneous actions
* Do you execute your macros in CL, GUIs or both
* Do you use the general hooks

Data Handling
=============

* [bool] Do you save your data with sardana
  - which format/formats do you use
  - why

* [bool] Do you miss any data format
  - which one
  
* [bool] Have you defined own recorders
  - why

* [bool] Do you save data from 1D detectors
  - how

* [bool] Do you save data from 2D detectors
  - how

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
