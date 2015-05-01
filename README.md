# GoCat
Data logging app with GPS, Map Overlays, Speed graphs, and support for PTD Bean data logger

#Things this currently does
- Uses iPhone CLLocation to log GPS data to an internal database.  GPS points are mapped onto a MapView
- Basic graphs implemented to show current and average data
- The speed graph can be dragged, so the user can see where abouts on the map the data point correlates too
- Support for LightBlue Bean BLE communication
- Other graphs implemented - trying to be obtuse about their use so they can reused for anything.  There are 2 types: 1 supports a single dataset, the other supports multiple datasets.

#Simulator mode
I have added a simulation mode - press and hold the Start button to enable it.  Then in iOS Simulator Debug menu, choose one of the GPS presets under Location.
