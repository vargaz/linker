The Mono linker is a tool one can use to only ship the minimal possible set of functions that a set of 
programs might require to run as opposed to the full libraries.

It is used by the various Xamarin products to extract only the bits of code that are needed to run
an application on Android, iOS and other platforms.

This file was extracted from Mono (github.com/mono/mono) on November 1st, 2016 to allow easier
sharing of the linker code with other .NET projects.
