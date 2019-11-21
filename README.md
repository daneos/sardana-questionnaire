# sardana-questionnaire
Draft for the Sardana Users Questionnaire

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
