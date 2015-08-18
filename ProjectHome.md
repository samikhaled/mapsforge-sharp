This project wants to port the Java/Android-project 'mapsforge' to C#. This project will result in a map control implementable into Windows Phone or Windows Desktop apps. The mapsforge.map-files should be readable and prepared for the use as generic vector data, also without usage in a map control.

The implementation should only use classes of the .Net-framework which are also available in the Windows Phone .Net-framework namespace.

This port will not copy the sources from Java to C# in a class by class and line by line manner. Only the map reader is close to the Java sources. The usage of the vector data is a new implementation aligned to the needs for Windows Phone.