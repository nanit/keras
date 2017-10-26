## Install instructions
* git clone to this repositroy

* To install Keras, `cd` to the Keras folder and run the install command:
```sh
python setup.py develop
```
(Inside the virtual env)

## List of changes from the 2.0.4 version:

* **keras/callbacks.py:** <br />
Changed the class _ModelCheckpoint_. <br />
Added the paramter _min_delta_:
```
 min_delta: minimum change in the monitored quantity
            to qualify as an improvement, i.e. an absolute
            change of less than min_delta, will count as no
            improvement.
```


* **keras/engine/topology.py + keras/utils/layer_utils.py:**  <br />
Added the option to print the model's summary to a log file.


* **keras/preprocessing/image.py:** <br />
Sorted the files list to be able to train the U-net.
