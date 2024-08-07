UIAComWrapper
=============

[![Build status](https://ci.appveyor.com/api/projects/status/oje79eml48u4t5aa/branch/master?svg=true)](https://ci.appveyor.com/project/ivan-danilov/uiacomwrapper/branch/master)
[![Test status](http://flauschig.ch/batch.php?type=tests&account=ivan-danilov&slug=UIAComWrapper&branch=master)](https://ci.appveyor.com/project/ivan-danilov/UiaComWrapper/branch/master)

The UI Automation COM-to-.NET Adapter makes it possible to use the new Windows Automation API 3.0 COM interfaces, with their improved reliability and performance, while still using the same System.Windows.Automation classes as in earlier versions of UI Automation

Changes
-------
### v1.1.0.15 
- return null when GridPattern.GetItem cannot fin an element instead of throwing exception.