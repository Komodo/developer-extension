This extension provides helper tools for working with JavaScript
and Python inside of Komodo. If you want to play around with the
JavaScript API, do some simple python coding tests, probe the
Komodo API for an extension, or play with the internals of Komodo,
then this is for you!

Brief guide:

  * Once installed, access it through the Tools-&gt;Extension
    Developer menu
  * When working with the JavaScript tools, you'll generally want
    to set the Scope to be the main Komodo window first, otherwise
    the Komodo API won't be available to you.
  * Use Tab for completions on objects and scope, fantastic!
  
Note: This extension is based upon Ted Mielczarek's \"Extension
Developer's Extension\". The only differences between this version
and Ted's is:

  * Updated to include a Komodo overlay
  * Includes the Python Shell, this requires PyXPCOM (already
    provided by Komodo).
    
**Updates**

  * 6th April 2015
    * Make compatible with Komodo 9
  * Some time in 2013
    * Make compatible with Komodo 8
  * 5th July 2011
    * Make compatible with Komodo 7
  * 18th March 2010
    * Automatically set the JS Shell to the scope of the opening window
    * Remember (persist) the shell dialog size **Screenshots**

![][1]

![][2]

   [1]: http://community.activestate.com/files/images/js_shell.png
   [2]: http://community.activestate.com/files/images/py_shell.png