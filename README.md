# AS---Bring-App-To-Foreground
LANGUAGE:     Apple Script
DESCRIPTION:  Select an Open Application, and Bring It to the Foreground


1 - Open "AppleScript Editor" From Your Mac                 (Search it in Spotlight)
2 - Paste the Code Below, and Run / Complile the Script:


  tell application "*NAMEofAPPLICATION*" to activate



Examples:

  tell application "Safari" to activate                   (must have Safari Open, otherwise Load it First)
  
  tell application "Google Chrome" to activate            (must have Google Chrome Open, otherwise Load it First)
  
  tell application "Finder" to activate                   (Finder is always Open on a Mac)
  
  tell application "iTunes" to activate                   (must have iTunes Open, otherwise Load it First)
  


