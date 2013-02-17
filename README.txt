ActionViewIntentHandler registers itself through its intent-filter 
in AndroidManifest.xml as a handler of android.intent.action.VIEW.

ActionViewIntentLauncher launches a browser intent, which, if
ActionViewIntentHandler is installed, causes it to be added to 
the list of ACTION.VIEW handlers that the user is asked to 
choose from.
