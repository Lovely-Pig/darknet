# darknet

```sh
$ make

$ cd data/custom
$ python write_img_paths.py
$ python voc2yolo.py
$ cd ../..

$ wget https://pjreddie.com/media/files/yolov3.weights

$ ./darknet detector train cfg/custom.data cfg/yolov3.cfg yolov3.weights
```
