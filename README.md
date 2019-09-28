# hello
import matplotlib.pyplot as plt
import numpy as np

logoImg = np.ones((30,30,3))

logoImg[:,:10,:2] = 0

logoImg[:10,:,:2] = 0

logoImg[20:,:,:2] = 0

plt.imsave("logo.png", logoImg)
