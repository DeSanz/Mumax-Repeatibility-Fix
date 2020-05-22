# Mumax-Repeatibility-Fix
Test file for solver buffer fix in Mumax and windows executable including the fix
#

The test .mx3 file checks if the buffer of your Mumax engine is being refreshed properly by running two loops. 
In the second loop a refresh of the buffer is forced while the first loop runs at the default mode of your executable.

A compiled Windows executable with the fix included in (https://github.com/mumax/3/issues/260) is also available for reference.
This executable prints "debug1" every time the solver deletes it memory.
