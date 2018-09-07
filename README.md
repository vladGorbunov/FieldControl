# FieldControl, Notes R9 compatible
#### <a href="https://github.com/vladGorbunov/FieldControl-original/wiki">FieldControl is a Notes application that allows quick viewing, modifing, deletiting and creating fields in Notes documents in a convenient way. The main purpose of FieldControl is to modify fields that cannot be modified via existing forms...</a>

Original FC was for R5 (as of 2005, non-opensource, https://github.com/vladGorbunov/FieldControl-original , see screenshots there)

Current FieldControl is original FC without key checking and R9 main issues eliminated.
  
  ### Creation of your own FieldControl DB
  1. Copy \*.LSS from *includes* folder into Notes program folder 
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
  1. Use this \*.ns5 DB in any Notes release, starting from R5
  
