## Pedestrian Detector Using OpenCV

**Steps**

* Install [openCV](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html)
* Place the image to be analyzed in root directory of the project. (In this case I use peds.jpeg)
* Execute following comand from root of the directory : `python Pedestrian Detector.py Pedestrians.jpeg`
* It takes a few seconds for it to run, you should following output if running against `Pedestrians.jpeg` image.

```
    $ python pedestrian.py peds.jpeg
    Found 31 pedestrian!
    Image written to file-system :  True
    [ INFO:0] Initialize OpenCL runtime...
```

* If all goes good, you should see a `Detected Pedestrians.jpeg` in the root directory. That is the analyzed image.
