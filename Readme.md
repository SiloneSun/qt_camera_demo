> Just copy QT5.12 camera example here.



Ubuntu20.02 : How to run the demo

install QT5.12
```
sudo apt-get install cmake qt5-default qtcreator
```

open qtcreater
```
sudo qtcreater
```




Some error you may meet and how to fix:

error: Unknown module(s) in QT: multimedia multimediawidgets
```
sudo apt-get install qtmultimedia5-dev

```

no service found for - "org.qt-project.qt.mediaplayer"
```
sudo apt-get install libqt5multimedia5-plugins 
```


no examples in QT5.12
```
sudo apt-get install qtbase5-examples qtbase5-doc-html
```


