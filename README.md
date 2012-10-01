State-Mappable-Task-Board
=========================

This SDK 2.0 Task Board allows mappable states for customized task work flow.

To use the app, a few things must be done in the app itself:
1. A custom field is required for tasks.  This must be a drop-down list of the desired state (column) names.
2. The name used to refer to this field MUST be entered in the code where referenced as the "mappedFromField".  See line 37 of the code for more.
3. The table columns must be named to reflect the state names.  See line 40 of the code for more.

An important caveat: if task state changes are made on the Iteration Status page, you may get out of sync with this app if the custom field is not updates for that task at the same time!

See the header of the actual code for more details.

Story Board Screenshot:<P>
![Alt text](https://github.com/jkrooswyk/State-Mappable-Task-Board/raw/master/Task Board Mappable screenshot.png)
