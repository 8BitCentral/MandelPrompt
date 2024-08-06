MandelPrompt is a tool that allows you to explore and zoom Mandelbrot fractals in the windows console.

Contents: 
 -Supported Operating Sytems
 -Capabilities and limitations

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

MandelPrompt has three versions as listed below:

 -MandelPrompt .Net 4.0_x64 - This supports 64-Bit systems, Windows 7, 8, 8.1, 10, 11 will allow it to work without any install. Windows XP and Vista will require .Net 4.0 to be installed.
 
 -MandelPrompt .Net 4.0_x86 - This supports 32-Bit systems, Windows 7, 8, 8.1, 10, 11 will allow it to work without any install. Windows XP and Vista will require .Net 4.0 to be installed.

 -MandelPrompt .Net 2.0_x86 - This supports 32-Bit systems, Windows XP, Vista, 7, 8, 8.1, 10, 11 will allow it to work without any install. Windows 98, Me and 2000 requires .Net 2.0 to be installed.
 MattKC ported .Net 2.0 to Windows 95 at: https://github.com/itsmattkc/dotnet9x . I have not tested this but it should work.

 In Windows XP the command prompt doesn't fullscreen without forcing an larger font so the screen resolution to text resolution converter doesn't work properly.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 -MandelPrompt allows the user to define coordinate positions as zooms to render fractals.
 -After the initial fractal has been generated you can press 'Z' to create a cursor that can be controlled with WASD, when space is pressed this location will be selected for zooming.
  The increase the zoom (ontop of the zoom that has already been performed) you can then enter an amount and then enter the iterations.
 -MandelPrompt supports 8 colours and runs with 4x6 text characters.