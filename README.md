# sardana-questionnaire

User interface components
=========================

General questions
-----------------

* What is your main interface to Sardana?
	- Spock
	- TaurusGUI
	- Other GUI application
	- Other
* What other interfaces do you use?

Spock
-----

* Do you use multiple Spock profiles? If so, what is the use case?
* Do you use Spock's built-in help (<macro>?)?
* Do you use tab completion?
* Do you configure experiment using macros or expconf widget?
* Do you use showscan for viewing scans/liveplotting?
* Do you use macrodata available in Spock?
* Do you edit macros using Spock features (edmac, etc...)?
* Do you use view options?
* Do you use Spock also as Python or Tango console?
* Are you interested in integrating Spock console into other applications?

MacroExecutor
-------------

* Do you use MacroExecutor?
* Do you use it as standalone application?
* Do you use favourites?
* Do you use pause function?
* Do you edit commands manually in the yellow Spock line?

Sequencer
---------

* Do you use Sequencer?
* Do you use it as standalone application?
* Do you save/load XML sequences?
* Do you load text sequences?
* Do you use pause/resume?

Expconf
-------

* Do you use Expconf widget?
* Do you use advanced measurement group configuration?
* Do you use liveplotting provided by expconf?
* Do you use snapshot groups?
* Do you configure scan storage with expconf?

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
* Do you use the sequencer
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