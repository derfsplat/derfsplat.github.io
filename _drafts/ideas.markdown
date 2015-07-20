blog ideas

Add npm global path to windows path
=============================
$nodeGlobalPath = Invoke-Expression "npm config get prefix"
C:\dev\Angular\fred-code> [Environment]::SetEnvironmentVariable('PATH', [Environment]::GetEnvironmentVariable('PATH' + ';' + $nodeGlobalPath)

EF Test Reporitory
===============
working around cached entities when doing add / get / verify

