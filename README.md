Update: 
keras.utils.np_utils has been removed.

Previous version:
from keras.utils.np_utils import to_categorical     (now commented in the code)
.
.
.
y_train = to_categorical(y_train, 10)
y_test = to_categorical(y_test, 10)


Instead updated code is like this:

import keras import utils
.
.
.
y_train = utils.to_categorical(y_train, 10)
y_test = utils.to_categorical(y_test, 10)
