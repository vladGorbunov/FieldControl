# FieldControl
Sources for FieldControl<BR>
  R9 compatibility testing in progress
<br>
Original FC (as of 2005, non-opensource) is here https://github.com/vladGorbunov/FieldControl-original (see screenshots there)
  
  ### Creation of your own FieldControl DB
  1. Open Domino Designer
  1. Menu->Window->Show Eclipse Views->Navigator
  1. In Navigator -> click RMB->New->Project->General->Project->Next->uncheck "Use default location"->Browse->select folder with project files (like ReadMe.md)->OK->Fill in Project name->Finish
  1. Select project created on previos step->click RMB->Team Development->associate with new NSF->Fill in new DB name->Finish
 ### Usage of FieldControl
1. Open FieldControl DB in IBM Notes ("About" document must be opened by itself)
1. Proceed with install steps there
 ### Use in previous releases of IBM Notes
  1. Create your own FieldControl in R9
  1. Make a copy of FieldControl DB via IBM Notes, explicitly specifying R5 ODS (specify ns5 extension for the new copy, like FieldControl.ns5)
  1. Use this \*.ns5 DB in any release, starting from R5
  
