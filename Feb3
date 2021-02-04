import tensorflow as tf
import numpy as np
from tensorflow import keras


model = tf.keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])])
model.compile(optimizer='sgd', loss='mean_squared_error')

xs = np.array([-1, 0, 1, 2, 3, 4], dtype = float)
ys = np.array([-2, 1, 4, 7, 10, 13], dtype = float)

model.fit(xs, ys, epochs = 500)

print(model.predict([7]))

model = tf.keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])])
model.compile(optimizer='sgd', loss='mean_squared_error')

xs = np.array([4, 3, 5, 4, 2, 3], dtype = float)
ys = np.array([399, 97, 347, 289, 250, 229], dtype = float)

model.fit(xs, ys, epochs = 500)

print(model.predict([2]))
print(model.predict([3]))
print(model.predict([4]))
print(model.predict([5]))
