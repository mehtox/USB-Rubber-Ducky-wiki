@echo off
COLOR 2B  
echo -----hellO-----
echo enter your first name
SET /p var=
echo enter your sirname 
set /p var2=
echo.
color 3B 
echo welcome %var% %var2% 
echo.
color 4b
pause: >nul
color 3a 
echo thank you
PAUSE: >nul
color 5f
echo do you want to launch google chrome? y/n
set /p var3=
color 7b
pause: >nul
if %var3%==y start chrome www.google.com
pause: 
exit


