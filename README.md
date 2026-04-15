On How to use these scripts :
Run them as administrator. (No, For real, they need to since it edits your execution policy)

Why? :: Because we aren't signed, and I will not sign them just for a silly project.
How? :: powershell.exe -ExecutionPolicy Unrestricted -File "script.ps1" | That execution policy
Applies only to the script.
But how can i be sure it's safe? :: It's a buncha .ps1 & .cmd files, just look into them
And if i don't want to? :: Then don't use it, or make it yourself.

  for hex2exe
  Put your input.txt with a valid string (often made by exe2hex.cmd) inside scripts
  run hex2exe (Powershell5 version for older powershell)
  grab output.exe
  
  It can convert any hex to anything, just rename it 
  ex: input.txt is a .zip file
  you obtain output.exe
  rename output.exe to {anything}.zip

  for exe2hex
  Put your input.exe
  run exe2hex (It works on PS 5 too)
  grab output.txt

  It can convert any file to hex, just rename it
  ex: input.exe is a zip file
  rename your {anything}.zip to input.exe
 
PS : This is a silly project done in like 5 minutes
