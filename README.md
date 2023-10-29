# RNA-and-Deep-Learning

# Projeto Final - Modelos Preditivos Conexionistas

### Anna Carolina Menezes de Roldao

|**Classificação de Imagem**|**MobileNetV2**|**Tensorflow**|
|--|--|--|

|Classificação de Imagens<br>ou<br>Deteção de Objetos|ex.: YOLOv5|PyTorch ou Tensorflow|

## Performance

O modelo treinado possui performance variando 0.25 a 0.26. Com loss aumentando a cada época do treinamento. 

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```textEpoch 1/830
20/21 [===========================>..] - ETA: 0s - loss: 0.0269 - accuracy: 0.2531
Epoch 1: saving model to training_1/cp.ckpt
21/21 [==============================] - 8s 168ms/step - loss: 0.0269 - accuracy: 0.2523 - val_loss: -0.2259 - val_accuracy: 0.2500
Epoch 2/830
20/21 [===========================>..] - ETA: 0s - loss: -0.4428 - accuracy: 0.2547
Epoch 2: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 169ms/step - loss: -0.4434 - accuracy: 0.2555 - val_loss: -0.5876 - val_accuracy: 0.2609
Epoch 3/830
20/21 [===========================>..] - ETA: 0s - loss: -0.8211 - accuracy: 0.2609
Epoch 3: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 170ms/step - loss: -0.8144 - accuracy: 0.2617 - val_loss: -0.8806 - val_accuracy: 0.2609
Epoch 4/830
20/21 [===========================>..] - ETA: 0s - loss: -1.1331 - accuracy: 0.2625
Epoch 4: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 165ms/step - loss: -1.1332 - accuracy: 0.2617 - val_loss: -1.1908 - val_accuracy: 0.2609
Epoch 5/830
20/21 [===========================>..] - ETA: 0s - loss: -1.4455 - accuracy: 0.2625
Epoch 5: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -1.4537 - accuracy: 0.2617 - val_loss: -1.4793 - val_accuracy: 0.2609
Epoch 6/830
20/21 [===========================>..] - ETA: 0s - loss: -1.7671 - accuracy: 0.2594
Epoch 6: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -1.7614 - accuracy: 0.2617 - val_loss: -1.7306 - val_accuracy: 0.2609
Epoch 7/830
20/21 [===========================>..] - ETA: 0s - loss: -2.0406 - accuracy: 0.2625
Epoch 7: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -2.0406 - accuracy: 0.2617 - val_loss: -1.9947 - val_accuracy: 0.2609
Epoch 8/830
20/21 [===========================>..] - ETA: 0s - loss: -2.3113 - accuracy: 0.2625
Epoch 8: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -2.3317 - accuracy: 0.2617 - val_loss: -2.2695 - val_accuracy: 0.2609
Epoch 9/830
20/21 [===========================>..] - ETA: 0s - loss: -2.6222 - accuracy: 0.2625
Epoch 9: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -2.6165 - accuracy: 0.2617 - val_loss: -2.4922 - val_accuracy: 0.2609
Epoch 10/830
20/21 [===========================>..] - ETA: 0s - loss: -2.8907 - accuracy: 0.2609
Epoch 10: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -2.8718 - accuracy: 0.2617 - val_loss: -2.7207 - val_accuracy: 0.2609
Epoch 11/830
20/21 [===========================>..] - ETA: 0s - loss: -3.1166 - accuracy: 0.2609
Epoch 11: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -3.1226 - accuracy: 0.2617 - val_loss: -2.9696 - val_accuracy: 0.2609
Epoch 12/830
20/21 [===========================>..] - ETA: 0s - loss: -3.4244 - accuracy: 0.2609
Epoch 12: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -3.4019 - accuracy: 0.2617 - val_loss: -3.1945 - val_accuracy: 0.2609
Epoch 13/830
20/21 [===========================>..] - ETA: 0s - loss: -3.6512 - accuracy: 0.2625
Epoch 13: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 179ms/step - loss: -3.6518 - accuracy: 0.2617 - val_loss: -3.4426 - val_accuracy: 0.2609
Epoch 14/830
20/21 [===========================>..] - ETA: 0s - loss: -3.9340 - accuracy: 0.2625
Epoch 14: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -3.9291 - accuracy: 0.2617 - val_loss: -3.6854 - val_accuracy: 0.2609
Epoch 15/830
20/21 [===========================>..] - ETA: 0s - loss: -4.2019 - accuracy: 0.2625
Epoch 15: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -4.1929 - accuracy: 0.2617 - val_loss: -3.9208 - val_accuracy: 0.2609
Epoch 16/830
20/21 [===========================>..] - ETA: 0s - loss: -4.4606 - accuracy: 0.2609
Epoch 16: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -4.4595 - accuracy: 0.2617 - val_loss: -4.1731 - val_accuracy: 0.2609
Epoch 17/830
20/21 [===========================>..] - ETA: 0s - loss: -4.7630 - accuracy: 0.2594
Epoch 17: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -4.7481 - accuracy: 0.2617 - val_loss: -4.4230 - val_accuracy: 0.2609
Epoch 18/830
20/21 [===========================>..] - ETA: 0s - loss: -5.0371 - accuracy: 0.2594
Epoch 18: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -5.0214 - accuracy: 0.2617 - val_loss: -4.6649 - val_accuracy: 0.2609
Epoch 19/830
20/21 [===========================>..] - ETA: 0s - loss: -5.2947 - accuracy: 0.2625
Epoch 19: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -5.2894 - accuracy: 0.2617 - val_loss: -4.9147 - val_accuracy: 0.2609
Epoch 20/830
20/21 [===========================>..] - ETA: 0s - loss: -5.5397 - accuracy: 0.2625
Epoch 20: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -5.5666 - accuracy: 0.2617 - val_loss: -5.1731 - val_accuracy: 0.2609
Epoch 21/830
20/21 [===========================>..] - ETA: 0s - loss: -5.8243 - accuracy: 0.2609
Epoch 21: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -5.8380 - accuracy: 0.2617 - val_loss: -5.4030 - val_accuracy: 0.2609
Epoch 22/830
20/21 [===========================>..] - ETA: 0s - loss: -6.0689 - accuracy: 0.2625
Epoch 22: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -6.1096 - accuracy: 0.2617 - val_loss: -5.6652 - val_accuracy: 0.2609
Epoch 23/830
20/21 [===========================>..] - ETA: 0s - loss: -6.3793 - accuracy: 0.2609
Epoch 23: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -6.3966 - accuracy: 0.2617 - val_loss: -5.9067 - val_accuracy: 0.2609
Epoch 24/830
20/21 [===========================>..] - ETA: 0s - loss: -6.6468 - accuracy: 0.2609
Epoch 24: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -6.6607 - accuracy: 0.2617 - val_loss: -6.1412 - val_accuracy: 0.2609
Epoch 25/830
20/21 [===========================>..] - ETA: 0s - loss: -6.9641 - accuracy: 0.2609
Epoch 25: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -6.9265 - accuracy: 0.2617 - val_loss: -6.3660 - val_accuracy: 0.2609
Epoch 26/830
20/21 [===========================>..] - ETA: 0s - loss: -7.2005 - accuracy: 0.2609
Epoch 26: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -7.1953 - accuracy: 0.2617 - val_loss: -6.6308 - val_accuracy: 0.2609
Epoch 27/830
20/21 [===========================>..] - ETA: 0s - loss: -7.4994 - accuracy: 0.2594
Epoch 27: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -7.4761 - accuracy: 0.2617 - val_loss: -6.8713 - val_accuracy: 0.2609
Epoch 28/830
20/21 [===========================>..] - ETA: 0s - loss: -7.7661 - accuracy: 0.2594
Epoch 28: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -7.7419 - accuracy: 0.2617 - val_loss: -7.1089 - val_accuracy: 0.2609
Epoch 29/830
20/21 [===========================>..] - ETA: 0s - loss: -7.9487 - accuracy: 0.2625
Epoch 29: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -8.0117 - accuracy: 0.2617 - val_loss: -7.3844 - val_accuracy: 0.2609
Epoch 30/830
20/21 [===========================>..] - ETA: 0s - loss: -8.3589 - accuracy: 0.2625
Epoch 30: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -8.2955 - accuracy: 0.2617 - val_loss: -7.5838 - val_accuracy: 0.2609
Epoch 31/830
20/21 [===========================>..] - ETA: 0s - loss: -8.5015 - accuracy: 0.2609
Epoch 31: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -8.5340 - accuracy: 0.2617 - val_loss: -7.8409 - val_accuracy: 0.2609
Epoch 32/830
20/21 [===========================>..] - ETA: 0s - loss: -8.8321 - accuracy: 0.2594
Epoch 32: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -8.8046 - accuracy: 0.2617 - val_loss: -8.0588 - val_accuracy: 0.2609
Epoch 33/830
20/21 [===========================>..] - ETA: 0s - loss: -9.0720 - accuracy: 0.2609
Epoch 33: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -9.0697 - accuracy: 0.2617 - val_loss: -8.3156 - val_accuracy: 0.2609
Epoch 34/830
20/21 [===========================>..] - ETA: 0s - loss: -9.3918 - accuracy: 0.2609
Epoch 34: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -9.3463 - accuracy: 0.2617 - val_loss: -8.5465 - val_accuracy: 0.2609
Epoch 35/830
20/21 [===========================>..] - ETA: 0s - loss: -9.6087 - accuracy: 0.2625
Epoch 35: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -9.6113 - accuracy: 0.2617 - val_loss: -8.8051 - val_accuracy: 0.2609
Epoch 36/830
20/21 [===========================>..] - ETA: 0s - loss: -9.9265 - accuracy: 0.2625
Epoch 36: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -9.8910 - accuracy: 0.2617 - val_loss: -9.0420 - val_accuracy: 0.2609
Epoch 37/830
20/21 [===========================>..] - ETA: 0s - loss: -10.1951 - accuracy: 0.2594
Epoch 37: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 170ms/step - loss: -10.1633 - accuracy: 0.2617 - val_loss: -9.2945 - val_accuracy: 0.2609
Epoch 38/830
20/21 [===========================>..] - ETA: 0s - loss: -10.3631 - accuracy: 0.2625
Epoch 38: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -10.4402 - accuracy: 0.2617 - val_loss: -9.5690 - val_accuracy: 0.2609
Epoch 39/830
20/21 [===========================>..] - ETA: 0s - loss: -10.6766 - accuracy: 0.2625
Epoch 39: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -10.7202 - accuracy: 0.2617 - val_loss: -9.7977 - val_accuracy: 0.2609
Epoch 40/830
20/21 [===========================>..] - ETA: 0s - loss: -11.0520 - accuracy: 0.2609
Epoch 40: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -10.9827 - accuracy: 0.2617 - val_loss: -10.0101 - val_accuracy: 0.2609
Epoch 41/830
20/21 [===========================>..] - ETA: 0s - loss: -11.2655 - accuracy: 0.2625
Epoch 41: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -11.2285 - accuracy: 0.2617 - val_loss: -10.2474 - val_accuracy: 0.2609
Epoch 42/830
20/21 [===========================>..] - ETA: 0s - loss: -11.5383 - accuracy: 0.2625
Epoch 42: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -11.4963 - accuracy: 0.2617 - val_loss: -10.4859 - val_accuracy: 0.2609
Epoch 43/830
20/21 [===========================>..] - ETA: 0s - loss: -11.8614 - accuracy: 0.2625
Epoch 43: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -11.7618 - accuracy: 0.2617 - val_loss: -10.7132 - val_accuracy: 0.2609
Epoch 44/830
20/21 [===========================>..] - ETA: 0s - loss: -12.0041 - accuracy: 0.2609
Epoch 44: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -11.9978 - accuracy: 0.2617 - val_loss: -10.9419 - val_accuracy: 0.2609
Epoch 45/830
20/21 [===========================>..] - ETA: 0s - loss: -12.2647 - accuracy: 0.2609
Epoch 45: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -12.2715 - accuracy: 0.2617 - val_loss: -11.2049 - val_accuracy: 0.2609
Epoch 46/830
20/21 [===========================>..] - ETA: 0s - loss: -12.5475 - accuracy: 0.2625
Epoch 46: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -12.5523 - accuracy: 0.2617 - val_loss: -11.4468 - val_accuracy: 0.2609
Epoch 47/830
20/21 [===========================>..] - ETA: 0s - loss: -12.8033 - accuracy: 0.2609
Epoch 47: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -12.8293 - accuracy: 0.2617 - val_loss: -11.7030 - val_accuracy: 0.2609
Epoch 48/830
20/21 [===========================>..] - ETA: 0s - loss: -13.0595 - accuracy: 0.2625
Epoch 48: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -13.0991 - accuracy: 0.2617 - val_loss: -11.9438 - val_accuracy: 0.2609
Epoch 49/830
20/21 [===========================>..] - ETA: 0s - loss: -13.4639 - accuracy: 0.2609
Epoch 49: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -13.3749 - accuracy: 0.2617 - val_loss: -12.1663 - val_accuracy: 0.2609
Epoch 50/830
20/21 [===========================>..] - ETA: 0s - loss: -13.5273 - accuracy: 0.2625
Epoch 50: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -13.6254 - accuracy: 0.2617 - val_loss: -12.4296 - val_accuracy: 0.2609
Epoch 51/830
20/21 [===========================>..] - ETA: 0s - loss: -13.8505 - accuracy: 0.2625
Epoch 51: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -13.9013 - accuracy: 0.2617 - val_loss: -12.6600 - val_accuracy: 0.2609
Epoch 52/830
20/21 [===========================>..] - ETA: 0s - loss: -14.2172 - accuracy: 0.2625
Epoch 52: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -14.1593 - accuracy: 0.2617 - val_loss: -12.8788 - val_accuracy: 0.2609
Epoch 53/830
20/21 [===========================>..] - ETA: 0s - loss: -14.2687 - accuracy: 0.2625
Epoch 53: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -14.4161 - accuracy: 0.2617 - val_loss: -13.1499 - val_accuracy: 0.2609
Epoch 54/830
20/21 [===========================>..] - ETA: 0s - loss: -14.6405 - accuracy: 0.2609
Epoch 54: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -14.6854 - accuracy: 0.2617 - val_loss: -13.3574 - val_accuracy: 0.2609
Epoch 55/830
20/21 [===========================>..] - ETA: 0s - loss: -14.9220 - accuracy: 0.2625
Epoch 55: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -14.9410 - accuracy: 0.2617 - val_loss: -13.6020 - val_accuracy: 0.2609
Epoch 56/830
20/21 [===========================>..] - ETA: 0s - loss: -15.2083 - accuracy: 0.2609
Epoch 56: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -15.2116 - accuracy: 0.2617 - val_loss: -13.8429 - val_accuracy: 0.2609
Epoch 57/830
20/21 [===========================>..] - ETA: 0s - loss: -15.5198 - accuracy: 0.2625
Epoch 57: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -15.4903 - accuracy: 0.2617 - val_loss: -14.0935 - val_accuracy: 0.2609
Epoch 58/830
20/21 [===========================>..] - ETA: 0s - loss: -15.7418 - accuracy: 0.2625
Epoch 58: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -15.7646 - accuracy: 0.2617 - val_loss: -14.3491 - val_accuracy: 0.2609
Epoch 59/830
20/21 [===========================>..] - ETA: 0s - loss: -15.9498 - accuracy: 0.2625
Epoch 59: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -16.0411 - accuracy: 0.2617 - val_loss: -14.6020 - val_accuracy: 0.2609
Epoch 60/830
20/21 [===========================>..] - ETA: 0s - loss: -16.3600 - accuracy: 0.2625
Epoch 60: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -16.3190 - accuracy: 0.2617 - val_loss: -14.8286 - val_accuracy: 0.2609
Epoch 61/830
20/21 [===========================>..] - ETA: 0s - loss: -16.5308 - accuracy: 0.2609
Epoch 61: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -16.5750 - accuracy: 0.2617 - val_loss: -15.0826 - val_accuracy: 0.2609
Epoch 62/830
20/21 [===========================>..] - ETA: 0s - loss: -17.0405 - accuracy: 0.2625
Epoch 62: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -16.8617 - accuracy: 0.2617 - val_loss: -15.3016 - val_accuracy: 0.2609
Epoch 63/830
20/21 [===========================>..] - ETA: 0s - loss: -17.1026 - accuracy: 0.2609
Epoch 63: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -17.0964 - accuracy: 0.2617 - val_loss: -15.5397 - val_accuracy: 0.2609
Epoch 64/830
20/21 [===========================>..] - ETA: 0s - loss: -17.2697 - accuracy: 0.2625
Epoch 64: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -17.3758 - accuracy: 0.2617 - val_loss: -15.8116 - val_accuracy: 0.2609
Epoch 65/830
20/21 [===========================>..] - ETA: 0s - loss: -17.6065 - accuracy: 0.2625
Epoch 65: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -17.6513 - accuracy: 0.2617 - val_loss: -16.0416 - val_accuracy: 0.2609
Epoch 66/830
20/21 [===========================>..] - ETA: 0s - loss: -17.9748 - accuracy: 0.2625
Epoch 66: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -17.9184 - accuracy: 0.2617 - val_loss: -16.2725 - val_accuracy: 0.2609
Epoch 67/830
20/21 [===========================>..] - ETA: 0s - loss: -18.2283 - accuracy: 0.2625
Epoch 67: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -18.1787 - accuracy: 0.2617 - val_loss: -16.5072 - val_accuracy: 0.2609
Epoch 68/830
20/21 [===========================>..] - ETA: 0s - loss: -18.5085 - accuracy: 0.2594
Epoch 68: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -18.4508 - accuracy: 0.2617 - val_loss: -16.7577 - val_accuracy: 0.2609
Epoch 69/830
20/21 [===========================>..] - ETA: 0s - loss: -18.8698 - accuracy: 0.2625
Epoch 69: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -18.7225 - accuracy: 0.2617 - val_loss: -16.9869 - val_accuracy: 0.2609
Epoch 70/830
20/21 [===========================>..] - ETA: 0s - loss: -19.0816 - accuracy: 0.2609
Epoch 70: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -18.9688 - accuracy: 0.2617 - val_loss: -17.2112 - val_accuracy: 0.2609
Epoch 71/830
20/21 [===========================>..] - ETA: 0s - loss: -19.2783 - accuracy: 0.2625
Epoch 71: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -19.2318 - accuracy: 0.2617 - val_loss: -17.4658 - val_accuracy: 0.2609
Epoch 72/830
20/21 [===========================>..] - ETA: 0s - loss: -19.6196 - accuracy: 0.2609
Epoch 72: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -19.4977 - accuracy: 0.2617 - val_loss: -17.6785 - val_accuracy: 0.2609
Epoch 73/830
20/21 [===========================>..] - ETA: 0s - loss: -19.8033 - accuracy: 0.2625
Epoch 73: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -19.7435 - accuracy: 0.2617 - val_loss: -17.9214 - val_accuracy: 0.2609
Epoch 74/830
20/21 [===========================>..] - ETA: 0s - loss: -20.0104 - accuracy: 0.2625
Epoch 74: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -20.0235 - accuracy: 0.2617 - val_loss: -18.1865 - val_accuracy: 0.2609
Epoch 75/830
20/21 [===========================>..] - ETA: 0s - loss: -20.2811 - accuracy: 0.2625
Epoch 75: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -20.2943 - accuracy: 0.2617 - val_loss: -18.4210 - val_accuracy: 0.2609
Epoch 76/830
20/21 [===========================>..] - ETA: 0s - loss: -20.4139 - accuracy: 0.2625
Epoch 76: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -20.5639 - accuracy: 0.2617 - val_loss: -18.6834 - val_accuracy: 0.2609
Epoch 77/830
20/21 [===========================>..] - ETA: 0s - loss: -20.7533 - accuracy: 0.2625
Epoch 77: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -20.8415 - accuracy: 0.2617 - val_loss: -18.9117 - val_accuracy: 0.2609
Epoch 78/830
20/21 [===========================>..] - ETA: 0s - loss: -21.0356 - accuracy: 0.2609
Epoch 78: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -21.1026 - accuracy: 0.2617 - val_loss: -19.1529 - val_accuracy: 0.2609
Epoch 79/830
20/21 [===========================>..] - ETA: 0s - loss: -21.4828 - accuracy: 0.2609
Epoch 79: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -21.3677 - accuracy: 0.2617 - val_loss: -19.3683 - val_accuracy: 0.2609
Epoch 80/830
20/21 [===========================>..] - ETA: 0s - loss: -21.7391 - accuracy: 0.2609
Epoch 80: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -21.6222 - accuracy: 0.2617 - val_loss: -19.6052 - val_accuracy: 0.2609
Epoch 81/830
20/21 [===========================>..] - ETA: 0s - loss: -21.7452 - accuracy: 0.2625
Epoch 81: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -21.8774 - accuracy: 0.2617 - val_loss: -19.8679 - val_accuracy: 0.2609
Epoch 82/830
20/21 [===========================>..] - ETA: 0s - loss: -22.2317 - accuracy: 0.2594
Epoch 82: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 192ms/step - loss: -22.1624 - accuracy: 0.2617 - val_loss: -20.0891 - val_accuracy: 0.2609
Epoch 83/830
20/21 [===========================>..] - ETA: 0s - loss: -22.4077 - accuracy: 0.2609
Epoch 83: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -22.4158 - accuracy: 0.2617 - val_loss: -20.3395 - val_accuracy: 0.2609
Epoch 84/830
20/21 [===========================>..] - ETA: 0s - loss: -22.8852 - accuracy: 0.2625
Epoch 84: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -22.7007 - accuracy: 0.2617 - val_loss: -20.5714 - val_accuracy: 0.2609
Epoch 85/830
20/21 [===========================>..] - ETA: 0s - loss: -23.0717 - accuracy: 0.2609
Epoch 85: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -22.9433 - accuracy: 0.2617 - val_loss: -20.7917 - val_accuracy: 0.2609
Epoch 86/830
20/21 [===========================>..] - ETA: 0s - loss: -23.1616 - accuracy: 0.2625
Epoch 86: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -23.2030 - accuracy: 0.2617 - val_loss: -21.0545 - val_accuracy: 0.2609
Epoch 87/830
20/21 [===========================>..] - ETA: 0s - loss: -23.5550 - accuracy: 0.2594
Epoch 87: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -23.4816 - accuracy: 0.2617 - val_loss: -21.2791 - val_accuracy: 0.2609
Epoch 88/830
20/21 [===========================>..] - ETA: 0s - loss: -23.8187 - accuracy: 0.2594
Epoch 88: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -23.7445 - accuracy: 0.2617 - val_loss: -21.5278 - val_accuracy: 0.2609
Epoch 89/830
20/21 [===========================>..] - ETA: 0s - loss: -23.8994 - accuracy: 0.2625
Epoch 89: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -24.0191 - accuracy: 0.2617 - val_loss: -21.7963 - val_accuracy: 0.2609
Epoch 90/830
20/21 [===========================>..] - ETA: 0s - loss: -24.3806 - accuracy: 0.2594
Epoch 90: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -24.3046 - accuracy: 0.2617 - val_loss: -22.0211 - val_accuracy: 0.2609
Epoch 91/830
20/21 [===========================>..] - ETA: 0s - loss: -24.5660 - accuracy: 0.2609
Epoch 91: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -24.5698 - accuracy: 0.2617 - val_loss: -22.2783 - val_accuracy: 0.2609
Epoch 92/830
20/21 [===========================>..] - ETA: 0s - loss: -24.8669 - accuracy: 0.2609
Epoch 92: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -24.8550 - accuracy: 0.2617 - val_loss: -22.5319 - val_accuracy: 0.2609
Epoch 93/830
20/21 [===========================>..] - ETA: 0s - loss: -25.0630 - accuracy: 0.2609
Epoch 93: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -25.1355 - accuracy: 0.2617 - val_loss: -22.7916 - val_accuracy: 0.2609
Epoch 94/830
20/21 [===========================>..] - ETA: 0s - loss: -25.4673 - accuracy: 0.2625
Epoch 94: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -25.4167 - accuracy: 0.2617 - val_loss: -23.0285 - val_accuracy: 0.2609
Epoch 95/830
20/21 [===========================>..] - ETA: 0s - loss: -25.9075 - accuracy: 0.2625
Epoch 95: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -25.6888 - accuracy: 0.2617 - val_loss: -23.2619 - val_accuracy: 0.2609
Epoch 96/830
20/21 [===========================>..] - ETA: 0s - loss: -25.8481 - accuracy: 0.2625
Epoch 96: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -25.9377 - accuracy: 0.2617 - val_loss: -23.5163 - val_accuracy: 0.2609
Epoch 97/830
20/21 [===========================>..] - ETA: 0s - loss: -26.2321 - accuracy: 0.2625
Epoch 97: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -26.2164 - accuracy: 0.2617 - val_loss: -23.7522 - val_accuracy: 0.2609
Epoch 98/830
20/21 [===========================>..] - ETA: 0s - loss: -26.7095 - accuracy: 0.2625
Epoch 98: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -26.4783 - accuracy: 0.2617 - val_loss: -23.9670 - val_accuracy: 0.2609
Epoch 99/830
20/21 [===========================>..] - ETA: 0s - loss: -26.7150 - accuracy: 0.2609
Epoch 99: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -26.7168 - accuracy: 0.2617 - val_loss: -24.2076 - val_accuracy: 0.2609
Epoch 100/830
20/21 [===========================>..] - ETA: 0s - loss: -26.9003 - accuracy: 0.2609
Epoch 100: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -26.9918 - accuracy: 0.2617 - val_loss: -24.4734 - val_accuracy: 0.2609
Epoch 101/830
20/21 [===========================>..] - ETA: 0s - loss: -27.1606 - accuracy: 0.2625
Epoch 101: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -27.2873 - accuracy: 0.2617 - val_loss: -24.7341 - val_accuracy: 0.2609
Epoch 102/830
20/21 [===========================>..] - ETA: 0s - loss: -27.7052 - accuracy: 0.2609
Epoch 102: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -27.5557 - accuracy: 0.2617 - val_loss: -24.9353 - val_accuracy: 0.2609
Epoch 103/830
20/21 [===========================>..] - ETA: 0s - loss: -27.6080 - accuracy: 0.2625
Epoch 103: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -27.8085 - accuracy: 0.2617 - val_loss: -25.2141 - val_accuracy: 0.2609
Epoch 104/830
21/21 [==============================] - ETA: 0s - loss: -28.0926 - accuracy: 0.2617
Epoch 104: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -28.0926 - accuracy: 0.2617 - val_loss: -25.4411 - val_accuracy: 0.2609
Epoch 105/830
20/21 [===========================>..] - ETA: 0s - loss: -28.3538 - accuracy: 0.2625
Epoch 105: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -28.3538 - accuracy: 0.2617 - val_loss: -25.6784 - val_accuracy: 0.2609
Epoch 106/830
20/21 [===========================>..] - ETA: 0s - loss: -28.4328 - accuracy: 0.2625
Epoch 106: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -28.6275 - accuracy: 0.2617 - val_loss: -25.9436 - val_accuracy: 0.2609
Epoch 107/830
20/21 [===========================>..] - ETA: 0s - loss: -28.9311 - accuracy: 0.2609
Epoch 107: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 171ms/step - loss: -28.9057 - accuracy: 0.2617 - val_loss: -26.1672 - val_accuracy: 0.2609
Epoch 108/830
20/21 [===========================>..] - ETA: 0s - loss: -29.0139 - accuracy: 0.2625
Epoch 108: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -29.1774 - accuracy: 0.2617 - val_loss: -26.4383 - val_accuracy: 0.2609
Epoch 109/830
20/21 [===========================>..] - ETA: 0s - loss: -29.3722 - accuracy: 0.2625
Epoch 109: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -29.4584 - accuracy: 0.2617 - val_loss: -26.6769 - val_accuracy: 0.2609
Epoch 110/830
20/21 [===========================>..] - ETA: 0s - loss: -29.7436 - accuracy: 0.2609
Epoch 110: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -29.7285 - accuracy: 0.2617 - val_loss: -26.9131 - val_accuracy: 0.2609
Epoch 111/830
20/21 [===========================>..] - ETA: 0s - loss: -30.1116 - accuracy: 0.2625
Epoch 111: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -30.0099 - accuracy: 0.2617 - val_loss: -27.1648 - val_accuracy: 0.2609
Epoch 112/830
20/21 [===========================>..] - ETA: 0s - loss: -30.0937 - accuracy: 0.2625
Epoch 112: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -30.2820 - accuracy: 0.2617 - val_loss: -27.4347 - val_accuracy: 0.2609
Epoch 113/830
20/21 [===========================>..] - ETA: 0s - loss: -30.6002 - accuracy: 0.2609
Epoch 113: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -30.5680 - accuracy: 0.2617 - val_loss: -27.6637 - val_accuracy: 0.2609
Epoch 114/830
20/21 [===========================>..] - ETA: 0s - loss: -30.8349 - accuracy: 0.2609
Epoch 114: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -30.8363 - accuracy: 0.2617 - val_loss: -27.9154 - val_accuracy: 0.2609
Epoch 115/830
20/21 [===========================>..] - ETA: 0s - loss: -30.9224 - accuracy: 0.2625
Epoch 115: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -31.1185 - accuracy: 0.2617 - val_loss: -28.1794 - val_accuracy: 0.2609
Epoch 116/830
20/21 [===========================>..] - ETA: 0s - loss: -31.1982 - accuracy: 0.2625
Epoch 116: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -31.3954 - accuracy: 0.2617 - val_loss: -28.4195 - val_accuracy: 0.2609
Epoch 117/830
20/21 [===========================>..] - ETA: 0s - loss: -31.5637 - accuracy: 0.2609
Epoch 117: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -31.6632 - accuracy: 0.2617 - val_loss: -28.6507 - val_accuracy: 0.2609
Epoch 118/830
20/21 [===========================>..] - ETA: 0s - loss: -32.0297 - accuracy: 0.2594
Epoch 118: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -31.9299 - accuracy: 0.2617 - val_loss: -28.8813 - val_accuracy: 0.2609
Epoch 119/830
20/21 [===========================>..] - ETA: 0s - loss: -32.4415 - accuracy: 0.2625
Epoch 119: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -32.1963 - accuracy: 0.2617 - val_loss: -29.1123 - val_accuracy: 0.2609
Epoch 120/830
20/21 [===========================>..] - ETA: 0s - loss: -32.3302 - accuracy: 0.2609
Epoch 120: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -32.4463 - accuracy: 0.2617 - val_loss: -29.3696 - val_accuracy: 0.2609
Epoch 121/830
20/21 [===========================>..] - ETA: 0s - loss: -32.9359 - accuracy: 0.2609
Epoch 121: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -32.7264 - accuracy: 0.2617 - val_loss: -29.5880 - val_accuracy: 0.2609
Epoch 122/830
20/21 [===========================>..] - ETA: 0s - loss: -32.7720 - accuracy: 0.2625
Epoch 122: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -32.9791 - accuracy: 0.2617 - val_loss: -29.8507 - val_accuracy: 0.2609
Epoch 123/830
20/21 [===========================>..] - ETA: 0s - loss: -33.3881 - accuracy: 0.2625
Epoch 123: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -33.2514 - accuracy: 0.2617 - val_loss: -30.0634 - val_accuracy: 0.2609
Epoch 124/830
20/21 [===========================>..] - ETA: 0s - loss: -33.6037 - accuracy: 0.2594
Epoch 124: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -33.4990 - accuracy: 0.2617 - val_loss: -30.2994 - val_accuracy: 0.2609
Epoch 125/830
20/21 [===========================>..] - ETA: 0s - loss: -33.6847 - accuracy: 0.2625
Epoch 125: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -33.7740 - accuracy: 0.2617 - val_loss: -30.5637 - val_accuracy: 0.2609
Epoch 126/830
20/21 [===========================>..] - ETA: 0s - loss: -34.0811 - accuracy: 0.2625
Epoch 126: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -34.0528 - accuracy: 0.2617 - val_loss: -30.7965 - val_accuracy: 0.2609
Epoch 127/830
20/21 [===========================>..] - ETA: 0s - loss: -34.5898 - accuracy: 0.2625
Epoch 127: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -34.3157 - accuracy: 0.2617 - val_loss: -31.0150 - val_accuracy: 0.2609
Epoch 128/830
20/21 [===========================>..] - ETA: 0s - loss: -34.6727 - accuracy: 0.2594
Epoch 128: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -34.5647 - accuracy: 0.2617 - val_loss: -31.2565 - val_accuracy: 0.2609
Epoch 129/830
20/21 [===========================>..] - ETA: 0s - loss: -34.6380 - accuracy: 0.2625
Epoch 129: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -34.8345 - accuracy: 0.2617 - val_loss: -31.5259 - val_accuracy: 0.2609
Epoch 130/830
20/21 [===========================>..] - ETA: 0s - loss: -35.0639 - accuracy: 0.2625
Epoch 130: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -35.1210 - accuracy: 0.2617 - val_loss: -31.7651 - val_accuracy: 0.2609
Epoch 131/830
20/21 [===========================>..] - ETA: 0s - loss: -35.5760 - accuracy: 0.2609
Epoch 131: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -35.3893 - accuracy: 0.2617 - val_loss: -31.9855 - val_accuracy: 0.2609
Epoch 132/830
20/21 [===========================>..] - ETA: 0s - loss: -35.7656 - accuracy: 0.2625
Epoch 132: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -35.6441 - accuracy: 0.2617 - val_loss: -32.2301 - val_accuracy: 0.2609
Epoch 133/830
20/21 [===========================>..] - ETA: 0s - loss: -35.9488 - accuracy: 0.2609
Epoch 133: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -35.9173 - accuracy: 0.2617 - val_loss: -32.4876 - val_accuracy: 0.2609
Epoch 134/830
20/21 [===========================>..] - ETA: 0s - loss: -36.3096 - accuracy: 0.2594
Epoch 134: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -36.1965 - accuracy: 0.2617 - val_loss: -32.7289 - val_accuracy: 0.2609
Epoch 135/830
20/21 [===========================>..] - ETA: 0s - loss: -36.8111 - accuracy: 0.2625
Epoch 135: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -36.4741 - accuracy: 0.2617 - val_loss: -32.9610 - val_accuracy: 0.2609
Epoch 136/830
20/21 [===========================>..] - ETA: 0s - loss: -36.6080 - accuracy: 0.2625
Epoch 136: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -36.7191 - accuracy: 0.2617 - val_loss: -33.2102 - val_accuracy: 0.2609
Epoch 137/830
20/21 [===========================>..] - ETA: 0s - loss: -36.6908 - accuracy: 0.2625
Epoch 137: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -36.9884 - accuracy: 0.2617 - val_loss: -33.4636 - val_accuracy: 0.2609
Epoch 138/830
20/21 [===========================>..] - ETA: 0s - loss: -36.9839 - accuracy: 0.2625
Epoch 138: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -37.2675 - accuracy: 0.2617 - val_loss: -33.7036 - val_accuracy: 0.2609
Epoch 139/830
20/21 [===========================>..] - ETA: 0s - loss: -37.3797 - accuracy: 0.2625
Epoch 139: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -37.5325 - accuracy: 0.2617 - val_loss: -33.9337 - val_accuracy: 0.2609
Epoch 140/830
20/21 [===========================>..] - ETA: 0s - loss: -37.7614 - accuracy: 0.2609
Epoch 140: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -37.7888 - accuracy: 0.2617 - val_loss: -34.1621 - val_accuracy: 0.2609
Epoch 141/830
20/21 [===========================>..] - ETA: 0s - loss: -38.2823 - accuracy: 0.2609
Epoch 141: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -38.0566 - accuracy: 0.2617 - val_loss: -34.3901 - val_accuracy: 0.2609
Epoch 142/830
20/21 [===========================>..] - ETA: 0s - loss: -38.2019 - accuracy: 0.2625
Epoch 142: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -38.3132 - accuracy: 0.2617 - val_loss: -34.6496 - val_accuracy: 0.2609
Epoch 143/830
20/21 [===========================>..] - ETA: 0s - loss: -38.4349 - accuracy: 0.2609
Epoch 143: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -38.5945 - accuracy: 0.2617 - val_loss: -34.8999 - val_accuracy: 0.2609
Epoch 144/830
20/21 [===========================>..] - ETA: 0s - loss: -38.6971 - accuracy: 0.2609
Epoch 144: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -38.8730 - accuracy: 0.2617 - val_loss: -35.1495 - val_accuracy: 0.2609
Epoch 145/830
20/21 [===========================>..] - ETA: 0s - loss: -39.1978 - accuracy: 0.2625
Epoch 145: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -39.1414 - accuracy: 0.2617 - val_loss: -35.3707 - val_accuracy: 0.2609
Epoch 146/830
20/21 [===========================>..] - ETA: 0s - loss: -39.6038 - accuracy: 0.2609
Epoch 146: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -39.4034 - accuracy: 0.2617 - val_loss: -35.6043 - val_accuracy: 0.2609
Epoch 147/830
20/21 [===========================>..] - ETA: 0s - loss: -39.2143 - accuracy: 0.2625
Epoch 147: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -39.6687 - accuracy: 0.2617 - val_loss: -35.8838 - val_accuracy: 0.2609
Epoch 148/830
20/21 [===========================>..] - ETA: 0s - loss: -40.0602 - accuracy: 0.2594
Epoch 148: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -39.9354 - accuracy: 0.2617 - val_loss: -36.0691 - val_accuracy: 0.2609
Epoch 149/830
20/21 [===========================>..] - ETA: 0s - loss: -40.1903 - accuracy: 0.2609
Epoch 149: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -40.1835 - accuracy: 0.2617 - val_loss: -36.3276 - val_accuracy: 0.2609
Epoch 150/830
20/21 [===========================>..] - ETA: 0s - loss: -40.5365 - accuracy: 0.2625
Epoch 150: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -40.4672 - accuracy: 0.2617 - val_loss: -36.5777 - val_accuracy: 0.2609
Epoch 151/830
20/21 [===========================>..] - ETA: 0s - loss: -40.5422 - accuracy: 0.2625
Epoch 151: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -40.7453 - accuracy: 0.2617 - val_loss: -36.8420 - val_accuracy: 0.2609
Epoch 152/830
20/21 [===========================>..] - ETA: 0s - loss: -40.7390 - accuracy: 0.2625
Epoch 152: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -41.0267 - accuracy: 0.2617 - val_loss: -37.0898 - val_accuracy: 0.2609
Epoch 153/830
20/21 [===========================>..] - ETA: 0s - loss: -41.4448 - accuracy: 0.2625
Epoch 153: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -41.2920 - accuracy: 0.2617 - val_loss: -37.2974 - val_accuracy: 0.2609
Epoch 154/830
20/21 [===========================>..] - ETA: 0s - loss: -41.2890 - accuracy: 0.2625
Epoch 154: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -41.5413 - accuracy: 0.2617 - val_loss: -37.5581 - val_accuracy: 0.2609
Epoch 155/830
20/21 [===========================>..] - ETA: 0s - loss: -41.5855 - accuracy: 0.2625
Epoch 155: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -41.8128 - accuracy: 0.2617 - val_loss: -37.7886 - val_accuracy: 0.2609
Epoch 156/830
20/21 [===========================>..] - ETA: 0s - loss: -42.3259 - accuracy: 0.2609
Epoch 156: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -42.0794 - accuracy: 0.2617 - val_loss: -38.0021 - val_accuracy: 0.2609
Epoch 157/830
20/21 [===========================>..] - ETA: 0s - loss: -42.2129 - accuracy: 0.2609
Epoch 157: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -42.3225 - accuracy: 0.2617 - val_loss: -38.2551 - val_accuracy: 0.2609
Epoch 158/830
20/21 [===========================>..] - ETA: 0s - loss: -42.7073 - accuracy: 0.2625
Epoch 158: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -42.6069 - accuracy: 0.2617 - val_loss: -38.4984 - val_accuracy: 0.2609
Epoch 159/830
20/21 [===========================>..] - ETA: 0s - loss: -42.8202 - accuracy: 0.2609
Epoch 159: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -42.8794 - accuracy: 0.2617 - val_loss: -38.7544 - val_accuracy: 0.2609
Epoch 160/830
20/21 [===========================>..] - ETA: 0s - loss: -43.5222 - accuracy: 0.2625
Epoch 160: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -43.1531 - accuracy: 0.2617 - val_loss: -38.9680 - val_accuracy: 0.2609
Epoch 161/830
20/21 [===========================>..] - ETA: 0s - loss: -43.2135 - accuracy: 0.2625
Epoch 161: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -43.3922 - accuracy: 0.2617 - val_loss: -39.2198 - val_accuracy: 0.2609
Epoch 162/830
20/21 [===========================>..] - ETA: 0s - loss: -43.6568 - accuracy: 0.2609
Epoch 162: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -43.6645 - accuracy: 0.2617 - val_loss: -39.4511 - val_accuracy: 0.2609
Epoch 163/830
20/21 [===========================>..] - ETA: 0s - loss: -44.1513 - accuracy: 0.2609
Epoch 163: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -43.9353 - accuracy: 0.2617 - val_loss: -39.6863 - val_accuracy: 0.2609
Epoch 164/830
20/21 [===========================>..] - ETA: 0s - loss: -44.5634 - accuracy: 0.2625
Epoch 164: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -44.1961 - accuracy: 0.2617 - val_loss: -39.9116 - val_accuracy: 0.2609
Epoch 165/830
20/21 [===========================>..] - ETA: 0s - loss: -44.3798 - accuracy: 0.2625
Epoch 165: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -44.4479 - accuracy: 0.2617 - val_loss: -40.1665 - val_accuracy: 0.2609
Epoch 166/830
20/21 [===========================>..] - ETA: 0s - loss: -44.7315 - accuracy: 0.2609
Epoch 166: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -44.7298 - accuracy: 0.2617 - val_loss: -40.4170 - val_accuracy: 0.2609
Epoch 167/830
20/21 [===========================>..] - ETA: 0s - loss: -44.8799 - accuracy: 0.2625
Epoch 167: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -45.0098 - accuracy: 0.2617 - val_loss: -40.6764 - val_accuracy: 0.2609
Epoch 168/830
20/21 [===========================>..] - ETA: 0s - loss: -45.7394 - accuracy: 0.2625
Epoch 168: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -45.2844 - accuracy: 0.2617 - val_loss: -40.8854 - val_accuracy: 0.2609
Epoch 169/830
20/21 [===========================>..] - ETA: 0s - loss: -45.6632 - accuracy: 0.2594
Epoch 169: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -45.5209 - accuracy: 0.2617 - val_loss: -41.1118 - val_accuracy: 0.2609
Epoch 170/830
20/21 [===========================>..] - ETA: 0s - loss: -45.5619 - accuracy: 0.2625
Epoch 170: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -45.7763 - accuracy: 0.2617 - val_loss: -41.3714 - val_accuracy: 0.2609
Epoch 171/830
20/21 [===========================>..] - ETA: 0s - loss: -46.1040 - accuracy: 0.2625
Epoch 171: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -46.0582 - accuracy: 0.2617 - val_loss: -41.6070 - val_accuracy: 0.2609
Epoch 172/830
20/21 [===========================>..] - ETA: 0s - loss: -46.3228 - accuracy: 0.2625
Epoch 172: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -46.3299 - accuracy: 0.2617 - val_loss: -41.8596 - val_accuracy: 0.2609
Epoch 173/830
20/21 [===========================>..] - ETA: 0s - loss: -46.0854 - accuracy: 0.2625
Epoch 173: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -46.6027 - accuracy: 0.2617 - val_loss: -42.1188 - val_accuracy: 0.2609
Epoch 174/830
20/21 [===========================>..] - ETA: 0s - loss: -46.7436 - accuracy: 0.2609
Epoch 174: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -46.8702 - accuracy: 0.2617 - val_loss: -42.3310 - val_accuracy: 0.2609
Epoch 175/830
20/21 [===========================>..] - ETA: 0s - loss: -47.1789 - accuracy: 0.2625
Epoch 175: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -47.1208 - accuracy: 0.2617 - val_loss: -42.5620 - val_accuracy: 0.2609
Epoch 176/830
20/21 [===========================>..] - ETA: 0s - loss: -47.2629 - accuracy: 0.2625
Epoch 176: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -47.3912 - accuracy: 0.2617 - val_loss: -42.8239 - val_accuracy: 0.2609
Epoch 177/830
20/21 [===========================>..] - ETA: 0s - loss: -47.9755 - accuracy: 0.2609
Epoch 177: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 189ms/step - loss: -47.6741 - accuracy: 0.2617 - val_loss: -43.0453 - val_accuracy: 0.2609
Epoch 178/830
20/21 [===========================>..] - ETA: 0s - loss: -48.4128 - accuracy: 0.2625
Epoch 178: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -47.9230 - accuracy: 0.2617 - val_loss: -43.2624 - val_accuracy: 0.2609
Epoch 179/830
20/21 [===========================>..] - ETA: 0s - loss: -48.1756 - accuracy: 0.2609
Epoch 179: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -48.1673 - accuracy: 0.2617 - val_loss: -43.5093 - val_accuracy: 0.2609
Epoch 180/830
20/21 [===========================>..] - ETA: 0s - loss: -48.2287 - accuracy: 0.2625
Epoch 180: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -48.4354 - accuracy: 0.2617 - val_loss: -43.7584 - val_accuracy: 0.2609
Epoch 181/830
20/21 [===========================>..] - ETA: 0s - loss: -48.9754 - accuracy: 0.2609
Epoch 181: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -48.7165 - accuracy: 0.2617 - val_loss: -43.9804 - val_accuracy: 0.2609
Epoch 182/830
20/21 [===========================>..] - ETA: 0s - loss: -49.1476 - accuracy: 0.2625
Epoch 182: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -48.9720 - accuracy: 0.2617 - val_loss: -44.2253 - val_accuracy: 0.2609
Epoch 183/830
20/21 [===========================>..] - ETA: 0s - loss: -49.2914 - accuracy: 0.2625
Epoch 183: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -49.2328 - accuracy: 0.2617 - val_loss: -44.4630 - val_accuracy: 0.2609
Epoch 184/830
20/21 [===========================>..] - ETA: 0s - loss: -49.0580 - accuracy: 0.2625
Epoch 184: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -49.4993 - accuracy: 0.2617 - val_loss: -44.7275 - val_accuracy: 0.2609
Epoch 185/830
20/21 [===========================>..] - ETA: 0s - loss: -49.7275 - accuracy: 0.2625
Epoch 185: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -49.7741 - accuracy: 0.2617 - val_loss: -44.9503 - val_accuracy: 0.2609
Epoch 186/830
20/21 [===========================>..] - ETA: 0s - loss: -49.9076 - accuracy: 0.2625
Epoch 186: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -50.0300 - accuracy: 0.2617 - val_loss: -45.1910 - val_accuracy: 0.2609
Epoch 187/830
20/21 [===========================>..] - ETA: 0s - loss: -50.1444 - accuracy: 0.2609
Epoch 187: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -50.2985 - accuracy: 0.2617 - val_loss: -45.4370 - val_accuracy: 0.2609
Epoch 188/830
20/21 [===========================>..] - ETA: 0s - loss: -50.6547 - accuracy: 0.2625
Epoch 188: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -50.5664 - accuracy: 0.2617 - val_loss: -45.6653 - val_accuracy: 0.2609
Epoch 189/830
20/21 [===========================>..] - ETA: 0s - loss: -50.6757 - accuracy: 0.2625
Epoch 189: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -50.8410 - accuracy: 0.2617 - val_loss: -45.9371 - val_accuracy: 0.2609
Epoch 190/830
20/21 [===========================>..] - ETA: 0s - loss: -51.0338 - accuracy: 0.2609
Epoch 190: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -51.1265 - accuracy: 0.2617 - val_loss: -46.1793 - val_accuracy: 0.2609
Epoch 191/830
20/21 [===========================>..] - ETA: 0s - loss: -51.6765 - accuracy: 0.2609
Epoch 191: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -51.3979 - accuracy: 0.2617 - val_loss: -46.4043 - val_accuracy: 0.2609
Epoch 192/830
20/21 [===========================>..] - ETA: 0s - loss: -51.8116 - accuracy: 0.2594
Epoch 192: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -51.6502 - accuracy: 0.2617 - val_loss: -46.6412 - val_accuracy: 0.2609
Epoch 193/830
20/21 [===========================>..] - ETA: 0s - loss: -51.8855 - accuracy: 0.2609
Epoch 193: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -51.9205 - accuracy: 0.2617 - val_loss: -46.9002 - val_accuracy: 0.2609
Epoch 194/830
20/21 [===========================>..] - ETA: 0s - loss: -52.4793 - accuracy: 0.2609
Epoch 194: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -52.2039 - accuracy: 0.2617 - val_loss: -47.1313 - val_accuracy: 0.2609
Epoch 195/830
20/21 [===========================>..] - ETA: 0s - loss: -52.7954 - accuracy: 0.2609
Epoch 195: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -52.4663 - accuracy: 0.2617 - val_loss: -47.3679 - val_accuracy: 0.2609
Epoch 196/830
20/21 [===========================>..] - ETA: 0s - loss: -52.4539 - accuracy: 0.2625
Epoch 196: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -52.7247 - accuracy: 0.2617 - val_loss: -47.6295 - val_accuracy: 0.2609
Epoch 197/830
20/21 [===========================>..] - ETA: 0s - loss: -52.4004 - accuracy: 0.2625
Epoch 197: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -53.0108 - accuracy: 0.2617 - val_loss: -47.8881 - val_accuracy: 0.2609
Epoch 198/830
20/21 [===========================>..] - ETA: 0s - loss: -53.0928 - accuracy: 0.2625
Epoch 198: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -53.2748 - accuracy: 0.2617 - val_loss: -48.0973 - val_accuracy: 0.2609
Epoch 199/830
20/21 [===========================>..] - ETA: 0s - loss: -53.1713 - accuracy: 0.2625
Epoch 199: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -53.5228 - accuracy: 0.2617 - val_loss: -48.3408 - val_accuracy: 0.2609
Epoch 200/830
20/21 [===========================>..] - ETA: 0s - loss: -53.5915 - accuracy: 0.2625
Epoch 200: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -53.7874 - accuracy: 0.2617 - val_loss: -48.5678 - val_accuracy: 0.2609
Epoch 201/830
20/21 [===========================>..] - ETA: 0s - loss: -54.2180 - accuracy: 0.2625
Epoch 201: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -54.0542 - accuracy: 0.2617 - val_loss: -48.7993 - val_accuracy: 0.2609
Epoch 202/830
20/21 [===========================>..] - ETA: 0s - loss: -54.7149 - accuracy: 0.2625
Epoch 202: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -54.3095 - accuracy: 0.2617 - val_loss: -49.0215 - val_accuracy: 0.2609
Epoch 203/830
20/21 [===========================>..] - ETA: 0s - loss: -54.4013 - accuracy: 0.2625
Epoch 203: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -54.5632 - accuracy: 0.2617 - val_loss: -49.2785 - val_accuracy: 0.2609
Epoch 204/830
20/21 [===========================>..] - ETA: 0s - loss: -54.3505 - accuracy: 0.2625
Epoch 204: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -54.8473 - accuracy: 0.2617 - val_loss: -49.5449 - val_accuracy: 0.2609
Epoch 205/830
20/21 [===========================>..] - ETA: 0s - loss: -54.9431 - accuracy: 0.2625
Epoch 205: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -55.1218 - accuracy: 0.2617 - val_loss: -49.7675 - val_accuracy: 0.2609
Epoch 206/830
20/21 [===========================>..] - ETA: 0s - loss: -55.8280 - accuracy: 0.2625
Epoch 206: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -55.3804 - accuracy: 0.2617 - val_loss: -49.9763 - val_accuracy: 0.2609
Epoch 207/830
20/21 [===========================>..] - ETA: 0s - loss: -55.5322 - accuracy: 0.2625
Epoch 207: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -55.6212 - accuracy: 0.2617 - val_loss: -50.2296 - val_accuracy: 0.2609
Epoch 208/830
20/21 [===========================>..] - ETA: 0s - loss: -55.4832 - accuracy: 0.2625
Epoch 208: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -55.9001 - accuracy: 0.2617 - val_loss: -50.4931 - val_accuracy: 0.2609
Epoch 209/830
20/21 [===========================>..] - ETA: 0s - loss: -56.0806 - accuracy: 0.2625
Epoch 209: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -56.1794 - accuracy: 0.2617 - val_loss: -50.7210 - val_accuracy: 0.2609
Epoch 210/830
20/21 [===========================>..] - ETA: 0s - loss: -56.7980 - accuracy: 0.2609
Epoch 210: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -56.4429 - accuracy: 0.2617 - val_loss: -50.9430 - val_accuracy: 0.2609
Epoch 211/830
20/21 [===========================>..] - ETA: 0s - loss: -57.0640 - accuracy: 0.2609
Epoch 211: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -56.6880 - accuracy: 0.2617 - val_loss: -51.1624 - val_accuracy: 0.2609
Epoch 212/830
20/21 [===========================>..] - ETA: 0s - loss: -56.8325 - accuracy: 0.2609
Epoch 212: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -56.9414 - accuracy: 0.2617 - val_loss: -51.4226 - val_accuracy: 0.2609
Epoch 213/830
20/21 [===========================>..] - ETA: 0s - loss: -57.5721 - accuracy: 0.2609
Epoch 213: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -57.2275 - accuracy: 0.2617 - val_loss: -51.6449 - val_accuracy: 0.2609
Epoch 214/830
20/21 [===========================>..] - ETA: 0s - loss: -57.1376 - accuracy: 0.2625
Epoch 214: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -57.4763 - accuracy: 0.2617 - val_loss: -51.9061 - val_accuracy: 0.2609
Epoch 215/830
20/21 [===========================>..] - ETA: 0s - loss: -58.0078 - accuracy: 0.2625
Epoch 215: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -57.7447 - accuracy: 0.2617 - val_loss: -52.1131 - val_accuracy: 0.2609
Epoch 216/830
20/21 [===========================>..] - ETA: 0s - loss: -57.5482 - accuracy: 0.2625
Epoch 216: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -57.9925 - accuracy: 0.2617 - val_loss: -52.3763 - val_accuracy: 0.2609
Epoch 217/830
20/21 [===========================>..] - ETA: 0s - loss: -57.8126 - accuracy: 0.2625
Epoch 217: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -58.2712 - accuracy: 0.2617 - val_loss: -52.6183 - val_accuracy: 0.2609
Epoch 218/830
20/21 [===========================>..] - ETA: 0s - loss: -58.3336 - accuracy: 0.2609
Epoch 218: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -58.5321 - accuracy: 0.2617 - val_loss: -52.8427 - val_accuracy: 0.2609
Epoch 219/830
20/21 [===========================>..] - ETA: 0s - loss: -58.9425 - accuracy: 0.2625
Epoch 219: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -58.7883 - accuracy: 0.2617 - val_loss: -53.0662 - val_accuracy: 0.2609
Epoch 220/830
20/21 [===========================>..] - ETA: 0s - loss: -59.2050 - accuracy: 0.2625
Epoch 220: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -59.0543 - accuracy: 0.2617 - val_loss: -53.3145 - val_accuracy: 0.2609
Epoch 221/830
20/21 [===========================>..] - ETA: 0s - loss: -59.0083 - accuracy: 0.2609
Epoch 221: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -59.3268 - accuracy: 0.2617 - val_loss: -53.5750 - val_accuracy: 0.2609
Epoch 222/830
20/21 [===========================>..] - ETA: 0s - loss: -59.6342 - accuracy: 0.2625
Epoch 222: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -59.6057 - accuracy: 0.2617 - val_loss: -53.8119 - val_accuracy: 0.2609
Epoch 223/830
20/21 [===========================>..] - ETA: 0s - loss: -59.9221 - accuracy: 0.2625
Epoch 223: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -59.8703 - accuracy: 0.2617 - val_loss: -54.0542 - val_accuracy: 0.2609
Epoch 224/830
20/21 [===========================>..] - ETA: 0s - loss: -59.9873 - accuracy: 0.2625
Epoch 224: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -60.1410 - accuracy: 0.2617 - val_loss: -54.3055 - val_accuracy: 0.2609
Epoch 225/830
20/21 [===========================>..] - ETA: 0s - loss: -60.0416 - accuracy: 0.2625
Epoch 225: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -60.4268 - accuracy: 0.2617 - val_loss: -54.5734 - val_accuracy: 0.2609
Epoch 226/830
20/21 [===========================>..] - ETA: 0s - loss: -60.7182 - accuracy: 0.2609
Epoch 226: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -60.6998 - accuracy: 0.2617 - val_loss: -54.7914 - val_accuracy: 0.2609
Epoch 227/830
20/21 [===========================>..] - ETA: 0s - loss: -60.9918 - accuracy: 0.2625
Epoch 227: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -60.9612 - accuracy: 0.2617 - val_loss: -55.0350 - val_accuracy: 0.2609
Epoch 228/830
20/21 [===========================>..] - ETA: 0s - loss: -61.2056 - accuracy: 0.2609
Epoch 228: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -61.2294 - accuracy: 0.2617 - val_loss: -55.2760 - val_accuracy: 0.2609
Epoch 229/830
20/21 [===========================>..] - ETA: 0s - loss: -61.6960 - accuracy: 0.2594
Epoch 229: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -61.5038 - accuracy: 0.2617 - val_loss: -55.5172 - val_accuracy: 0.2609
Epoch 230/830
20/21 [===========================>..] - ETA: 0s - loss: -61.8431 - accuracy: 0.2609
Epoch 230: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -61.7754 - accuracy: 0.2617 - val_loss: -55.7755 - val_accuracy: 0.2609
Epoch 231/830
20/21 [===========================>..] - ETA: 0s - loss: -62.2765 - accuracy: 0.2625
Epoch 231: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -62.0689 - accuracy: 0.2617 - val_loss: -56.0302 - val_accuracy: 0.2609
Epoch 232/830
20/21 [===========================>..] - ETA: 0s - loss: -62.5641 - accuracy: 0.2625
Epoch 232: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -62.3477 - accuracy: 0.2617 - val_loss: -56.2763 - val_accuracy: 0.2609
Epoch 233/830
20/21 [===========================>..] - ETA: 0s - loss: -62.8958 - accuracy: 0.2625
Epoch 233: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -62.6221 - accuracy: 0.2617 - val_loss: -56.5171 - val_accuracy: 0.2609
Epoch 234/830
20/21 [===========================>..] - ETA: 0s - loss: -63.5159 - accuracy: 0.2625
Epoch 234: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -62.8922 - accuracy: 0.2617 - val_loss: -56.7461 - val_accuracy: 0.2609
Epoch 235/830
20/21 [===========================>..] - ETA: 0s - loss: -63.3323 - accuracy: 0.2625
Epoch 235: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -63.1248 - accuracy: 0.2617 - val_loss: -56.9699 - val_accuracy: 0.2609
Epoch 236/830
20/21 [===========================>..] - ETA: 0s - loss: -63.7574 - accuracy: 0.2609
Epoch 236: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -63.3936 - accuracy: 0.2617 - val_loss: -57.2101 - val_accuracy: 0.2609
Epoch 237/830
20/21 [===========================>..] - ETA: 0s - loss: -63.9277 - accuracy: 0.2625
Epoch 237: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -63.6554 - accuracy: 0.2617 - val_loss: -57.4513 - val_accuracy: 0.2609
Epoch 238/830
20/21 [===========================>..] - ETA: 0s - loss: -64.5127 - accuracy: 0.2625
Epoch 238: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -63.9180 - accuracy: 0.2617 - val_loss: -57.6757 - val_accuracy: 0.2609
Epoch 239/830
20/21 [===========================>..] - ETA: 0s - loss: -63.8388 - accuracy: 0.2609
Epoch 239: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -64.1569 - accuracy: 0.2617 - val_loss: -57.9204 - val_accuracy: 0.2609
Epoch 240/830
20/21 [===========================>..] - ETA: 0s - loss: -64.6348 - accuracy: 0.2625
Epoch 240: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -64.4254 - accuracy: 0.2617 - val_loss: -58.1439 - val_accuracy: 0.2609
Epoch 241/830
20/21 [===========================>..] - ETA: 0s - loss: -64.3264 - accuracy: 0.2625
Epoch 241: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -64.6861 - accuracy: 0.2617 - val_loss: -58.4140 - val_accuracy: 0.2609
Epoch 242/830
20/21 [===========================>..] - ETA: 0s - loss: -65.0026 - accuracy: 0.2609
Epoch 242: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -64.9765 - accuracy: 0.2617 - val_loss: -58.6516 - val_accuracy: 0.2609
Epoch 243/830
20/21 [===========================>..] - ETA: 0s - loss: -65.0468 - accuracy: 0.2609
Epoch 243: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -65.2462 - accuracy: 0.2617 - val_loss: -58.9086 - val_accuracy: 0.2609
Epoch 244/830
20/21 [===========================>..] - ETA: 0s - loss: -65.8649 - accuracy: 0.2609
Epoch 244: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -65.5277 - accuracy: 0.2617 - val_loss: -59.1350 - val_accuracy: 0.2609
Epoch 245/830
20/21 [===========================>..] - ETA: 0s - loss: -66.2036 - accuracy: 0.2609
Epoch 245: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -65.7867 - accuracy: 0.2617 - val_loss: -59.3677 - val_accuracy: 0.2609
Epoch 246/830
20/21 [===========================>..] - ETA: 0s - loss: -66.2540 - accuracy: 0.2594
Epoch 246: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -66.0476 - accuracy: 0.2617 - val_loss: -59.6134 - val_accuracy: 0.2609
Epoch 247/830
20/21 [===========================>..] - ETA: 0s - loss: -66.3926 - accuracy: 0.2609
Epoch 247: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -66.3200 - accuracy: 0.2617 - val_loss: -59.8693 - val_accuracy: 0.2609
Epoch 248/830
20/21 [===========================>..] - ETA: 0s - loss: -66.9639 - accuracy: 0.2609
Epoch 248: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -66.6050 - accuracy: 0.2617 - val_loss: -60.1055 - val_accuracy: 0.2609
Epoch 249/830
20/21 [===========================>..] - ETA: 0s - loss: -66.6595 - accuracy: 0.2625
Epoch 249: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -66.8677 - accuracy: 0.2617 - val_loss: -60.3692 - val_accuracy: 0.2609
Epoch 250/830
20/21 [===========================>..] - ETA: 0s - loss: -67.1688 - accuracy: 0.2609
Epoch 250: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -67.1535 - accuracy: 0.2617 - val_loss: -60.6122 - val_accuracy: 0.2609
Epoch 251/830
20/21 [===========================>..] - ETA: 0s - loss: -67.4466 - accuracy: 0.2609
Epoch 251: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -67.4260 - accuracy: 0.2617 - val_loss: -60.8608 - val_accuracy: 0.2609
Epoch 252/830
20/21 [===========================>..] - ETA: 0s - loss: -67.7033 - accuracy: 0.2609
Epoch 252: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -67.7019 - accuracy: 0.2617 - val_loss: -61.1090 - val_accuracy: 0.2609
Epoch 253/830
20/21 [===========================>..] - ETA: 0s - loss: -68.1574 - accuracy: 0.2625
Epoch 253: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -67.9845 - accuracy: 0.2617 - val_loss: -61.3595 - val_accuracy: 0.2609
Epoch 254/830
20/21 [===========================>..] - ETA: 0s - loss: -68.2347 - accuracy: 0.2625
Epoch 254: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -68.2592 - accuracy: 0.2617 - val_loss: -61.6118 - val_accuracy: 0.2609
Epoch 255/830
20/21 [===========================>..] - ETA: 0s - loss: -68.4871 - accuracy: 0.2609
Epoch 255: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -68.5276 - accuracy: 0.2617 - val_loss: -61.8529 - val_accuracy: 0.2609
Epoch 256/830
20/21 [===========================>..] - ETA: 0s - loss: -68.9361 - accuracy: 0.2625
Epoch 256: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -68.8080 - accuracy: 0.2617 - val_loss: -62.0969 - val_accuracy: 0.2609
Epoch 257/830
20/21 [===========================>..] - ETA: 0s - loss: -69.2503 - accuracy: 0.2625
Epoch 257: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -69.0808 - accuracy: 0.2617 - val_loss: -62.3454 - val_accuracy: 0.2609
Epoch 258/830
20/21 [===========================>..] - ETA: 0s - loss: -69.8055 - accuracy: 0.2609
Epoch 258: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -69.3531 - accuracy: 0.2617 - val_loss: -62.5750 - val_accuracy: 0.2609
Epoch 259/830
20/21 [===========================>..] - ETA: 0s - loss: -69.5901 - accuracy: 0.2609
Epoch 259: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -69.6112 - accuracy: 0.2617 - val_loss: -62.8324 - val_accuracy: 0.2609
Epoch 260/830
20/21 [===========================>..] - ETA: 0s - loss: -69.3927 - accuracy: 0.2625
Epoch 260: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -69.8874 - accuracy: 0.2617 - val_loss: -63.0897 - val_accuracy: 0.2609
Epoch 261/830
20/21 [===========================>..] - ETA: 0s - loss: -70.3862 - accuracy: 0.2594
Epoch 261: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -70.1669 - accuracy: 0.2617 - val_loss: -63.3126 - val_accuracy: 0.2609
Epoch 262/830
20/21 [===========================>..] - ETA: 0s - loss: -70.2993 - accuracy: 0.2609
Epoch 262: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -70.4207 - accuracy: 0.2617 - val_loss: -63.5631 - val_accuracy: 0.2609
Epoch 263/830
20/21 [===========================>..] - ETA: 0s - loss: -70.9571 - accuracy: 0.2625
Epoch 263: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -70.7106 - accuracy: 0.2617 - val_loss: -63.8092 - val_accuracy: 0.2609
Epoch 264/830
20/21 [===========================>..] - ETA: 0s - loss: -71.3566 - accuracy: 0.2609
Epoch 264: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -70.9822 - accuracy: 0.2617 - val_loss: -64.0457 - val_accuracy: 0.2609
Epoch 265/830
20/21 [===========================>..] - ETA: 0s - loss: -71.2134 - accuracy: 0.2625
Epoch 265: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -71.2414 - accuracy: 0.2617 - val_loss: -64.2954 - val_accuracy: 0.2609
Epoch 266/830
20/21 [===========================>..] - ETA: 0s - loss: -70.9946 - accuracy: 0.2625
Epoch 266: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -71.5201 - accuracy: 0.2617 - val_loss: -64.5585 - val_accuracy: 0.2609
Epoch 267/830
20/21 [===========================>..] - ETA: 0s - loss: -71.5221 - accuracy: 0.2609
Epoch 267: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -71.7977 - accuracy: 0.2617 - val_loss: -64.7957 - val_accuracy: 0.2609
Epoch 268/830
20/21 [===========================>..] - ETA: 0s - loss: -72.5168 - accuracy: 0.2609
Epoch 268: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -72.0650 - accuracy: 0.2617 - val_loss: -65.0097 - val_accuracy: 0.2609
Epoch 269/830
20/21 [===========================>..] - ETA: 0s - loss: -72.7467 - accuracy: 0.2609
Epoch 269: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 187ms/step - loss: -72.3111 - accuracy: 0.2617 - val_loss: -65.2346 - val_accuracy: 0.2609
Epoch 270/830
20/21 [===========================>..] - ETA: 0s - loss: -72.3367 - accuracy: 0.2625
Epoch 270: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -72.5630 - accuracy: 0.2617 - val_loss: -65.4894 - val_accuracy: 0.2609
Epoch 271/830
20/21 [===========================>..] - ETA: 0s - loss: -73.0696 - accuracy: 0.2594
Epoch 271: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -72.8420 - accuracy: 0.2617 - val_loss: -65.7176 - val_accuracy: 0.2609
Epoch 272/830
20/21 [===========================>..] - ETA: 0s - loss: -73.1406 - accuracy: 0.2609
Epoch 272: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -73.1032 - accuracy: 0.2617 - val_loss: -65.9708 - val_accuracy: 0.2609
Epoch 273/830
20/21 [===========================>..] - ETA: 0s - loss: -74.0299 - accuracy: 0.2625
Epoch 273: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -73.3917 - accuracy: 0.2617 - val_loss: -66.2065 - val_accuracy: 0.2609
Epoch 274/830
20/21 [===========================>..] - ETA: 0s - loss: -73.3818 - accuracy: 0.2609
Epoch 274: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -73.6382 - accuracy: 0.2617 - val_loss: -66.4575 - val_accuracy: 0.2609
Epoch 275/830
20/21 [===========================>..] - ETA: 0s - loss: -74.1463 - accuracy: 0.2594
Epoch 275: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -73.9154 - accuracy: 0.2617 - val_loss: -66.6876 - val_accuracy: 0.2609
Epoch 276/830
20/21 [===========================>..] - ETA: 0s - loss: -73.9764 - accuracy: 0.2609
Epoch 276: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -74.1875 - accuracy: 0.2617 - val_loss: -66.9534 - val_accuracy: 0.2609
Epoch 277/830
20/21 [===========================>..] - ETA: 0s - loss: -74.8618 - accuracy: 0.2609
Epoch 277: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -74.4673 - accuracy: 0.2617 - val_loss: -67.1768 - val_accuracy: 0.2609
Epoch 278/830
20/21 [===========================>..] - ETA: 0s - loss: -74.7081 - accuracy: 0.2609
Epoch 278: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -74.7243 - accuracy: 0.2617 - val_loss: -67.4278 - val_accuracy: 0.2609
Epoch 279/830
20/21 [===========================>..] - ETA: 0s - loss: -75.6148 - accuracy: 0.2625
Epoch 279: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -75.0023 - accuracy: 0.2617 - val_loss: -67.6539 - val_accuracy: 0.2609
Epoch 280/830
20/21 [===========================>..] - ETA: 0s - loss: -75.1484 - accuracy: 0.2625
Epoch 280: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -75.2469 - accuracy: 0.2617 - val_loss: -67.8961 - val_accuracy: 0.2609
Epoch 281/830
20/21 [===========================>..] - ETA: 0s - loss: -76.1486 - accuracy: 0.2625
Epoch 281: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -75.5117 - accuracy: 0.2617 - val_loss: -68.1096 - val_accuracy: 0.2609
Epoch 282/830
20/21 [===========================>..] - ETA: 0s - loss: -75.7494 - accuracy: 0.2609
Epoch 282: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -75.7520 - accuracy: 0.2617 - val_loss: -68.3483 - val_accuracy: 0.2609
Epoch 283/830
20/21 [===========================>..] - ETA: 0s - loss: -75.7781 - accuracy: 0.2609
Epoch 283: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -76.0239 - accuracy: 0.2617 - val_loss: -68.6038 - val_accuracy: 0.2609
Epoch 284/830
20/21 [===========================>..] - ETA: 0s - loss: -76.4952 - accuracy: 0.2625
Epoch 284: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -76.2951 - accuracy: 0.2617 - val_loss: -68.8295 - val_accuracy: 0.2609
Epoch 285/830
20/21 [===========================>..] - ETA: 0s - loss: -76.2788 - accuracy: 0.2609
Epoch 285: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -76.5490 - accuracy: 0.2617 - val_loss: -69.0776 - val_accuracy: 0.2609
Epoch 286/830
20/21 [===========================>..] - ETA: 0s - loss: -76.9565 - accuracy: 0.2625
Epoch 286: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -76.8198 - accuracy: 0.2617 - val_loss: -69.3078 - val_accuracy: 0.2609
Epoch 287/830
20/21 [===========================>..] - ETA: 0s - loss: -76.5196 - accuracy: 0.2625
Epoch 287: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -77.0921 - accuracy: 0.2617 - val_loss: -69.5786 - val_accuracy: 0.2609
Epoch 288/830
20/21 [===========================>..] - ETA: 0s - loss: -76.8004 - accuracy: 0.2625
Epoch 288: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -77.3727 - accuracy: 0.2617 - val_loss: -69.8164 - val_accuracy: 0.2609
Epoch 289/830
20/21 [===========================>..] - ETA: 0s - loss: -76.8308 - accuracy: 0.2625
Epoch 289: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -77.6404 - accuracy: 0.2617 - val_loss: -70.0573 - val_accuracy: 0.2609
Epoch 290/830
20/21 [===========================>..] - ETA: 0s - loss: -77.8439 - accuracy: 0.2625
Epoch 290: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 160ms/step - loss: -77.8951 - accuracy: 0.2617 - val_loss: -70.2593 - val_accuracy: 0.2609
Epoch 291/830
20/21 [===========================>..] - ETA: 0s - loss: -78.3277 - accuracy: 0.2625
Epoch 291: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -78.1445 - accuracy: 0.2617 - val_loss: -70.4944 - val_accuracy: 0.2609
Epoch 292/830
20/21 [===========================>..] - ETA: 0s - loss: -78.4392 - accuracy: 0.2609
Epoch 292: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -78.4116 - accuracy: 0.2617 - val_loss: -70.7443 - val_accuracy: 0.2609
Epoch 293/830
20/21 [===========================>..] - ETA: 0s - loss: -79.4105 - accuracy: 0.2625
Epoch 293: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -78.6905 - accuracy: 0.2617 - val_loss: -70.9682 - val_accuracy: 0.2609
Epoch 294/830
20/21 [===========================>..] - ETA: 0s - loss: -78.7498 - accuracy: 0.2625
Epoch 294: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -78.9272 - accuracy: 0.2617 - val_loss: -71.2063 - val_accuracy: 0.2609
Epoch 295/830
20/21 [===========================>..] - ETA: 0s - loss: -79.2543 - accuracy: 0.2609
Epoch 295: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -79.1995 - accuracy: 0.2617 - val_loss: -71.4505 - val_accuracy: 0.2609
Epoch 296/830
20/21 [===========================>..] - ETA: 0s - loss: -80.0917 - accuracy: 0.2625
Epoch 296: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -79.4702 - accuracy: 0.2617 - val_loss: -71.6738 - val_accuracy: 0.2609
Epoch 297/830
20/21 [===========================>..] - ETA: 0s - loss: -79.9600 - accuracy: 0.2594
Epoch 297: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -79.7109 - accuracy: 0.2617 - val_loss: -71.9029 - val_accuracy: 0.2609
Epoch 298/830
21/21 [==============================] - ETA: 0s - loss: -79.9778 - accuracy: 0.2617
Epoch 298: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -79.9778 - accuracy: 0.2617 - val_loss: -72.1572 - val_accuracy: 0.2609
Epoch 299/830
20/21 [===========================>..] - ETA: 0s - loss: -80.7734 - accuracy: 0.2609
Epoch 299: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -80.2650 - accuracy: 0.2617 - val_loss: -72.3959 - val_accuracy: 0.2609
Epoch 300/830
20/21 [===========================>..] - ETA: 0s - loss: -81.2088 - accuracy: 0.2625
Epoch 300: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -80.5334 - accuracy: 0.2617 - val_loss: -72.6355 - val_accuracy: 0.2609
Epoch 301/830
20/21 [===========================>..] - ETA: 0s - loss: -81.2722 - accuracy: 0.2609
Epoch 301: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -80.7836 - accuracy: 0.2617 - val_loss: -72.8600 - val_accuracy: 0.2609
Epoch 302/830
20/21 [===========================>..] - ETA: 0s - loss: -81.4824 - accuracy: 0.2609
Epoch 302: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -81.0338 - accuracy: 0.2617 - val_loss: -73.0877 - val_accuracy: 0.2609
Epoch 303/830
20/21 [===========================>..] - ETA: 0s - loss: -80.9803 - accuracy: 0.2609
Epoch 303: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -81.2964 - accuracy: 0.2617 - val_loss: -73.3547 - val_accuracy: 0.2609
Epoch 304/830
20/21 [===========================>..] - ETA: 0s - loss: -81.8280 - accuracy: 0.2594
Epoch 304: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -81.5730 - accuracy: 0.2617 - val_loss: -73.5731 - val_accuracy: 0.2609
Epoch 305/830
20/21 [===========================>..] - ETA: 0s - loss: -82.3023 - accuracy: 0.2609
Epoch 305: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -81.8335 - accuracy: 0.2617 - val_loss: -73.8123 - val_accuracy: 0.2609
Epoch 306/830
20/21 [===========================>..] - ETA: 0s - loss: -81.4884 - accuracy: 0.2625
Epoch 306: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -82.1078 - accuracy: 0.2617 - val_loss: -74.0956 - val_accuracy: 0.2609
Epoch 307/830
20/21 [===========================>..] - ETA: 0s - loss: -83.1611 - accuracy: 0.2625
Epoch 307: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -82.3901 - accuracy: 0.2617 - val_loss: -74.2898 - val_accuracy: 0.2609
Epoch 308/830
20/21 [===========================>..] - ETA: 0s - loss: -83.2657 - accuracy: 0.2609
Epoch 308: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -82.6128 - accuracy: 0.2617 - val_loss: -74.5032 - val_accuracy: 0.2609
Epoch 309/830
20/21 [===========================>..] - ETA: 0s - loss: -82.5186 - accuracy: 0.2625
Epoch 309: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -82.8533 - accuracy: 0.2617 - val_loss: -74.7498 - val_accuracy: 0.2609
Epoch 310/830
20/21 [===========================>..] - ETA: 0s - loss: -83.3699 - accuracy: 0.2625
Epoch 310: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -83.1287 - accuracy: 0.2617 - val_loss: -74.9818 - val_accuracy: 0.2609
Epoch 311/830
20/21 [===========================>..] - ETA: 0s - loss: -83.0151 - accuracy: 0.2609
Epoch 311: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -83.3920 - accuracy: 0.2617 - val_loss: -75.2443 - val_accuracy: 0.2609
Epoch 312/830
20/21 [===========================>..] - ETA: 0s - loss: -82.9877 - accuracy: 0.2625
Epoch 312: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -83.6750 - accuracy: 0.2617 - val_loss: -75.4950 - val_accuracy: 0.2609
Epoch 313/830
20/21 [===========================>..] - ETA: 0s - loss: -83.0723 - accuracy: 0.2625
Epoch 313: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -83.9439 - accuracy: 0.2617 - val_loss: -75.7307 - val_accuracy: 0.2609
Epoch 314/830
20/21 [===========================>..] - ETA: 0s - loss: -84.7072 - accuracy: 0.2609
Epoch 314: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -84.2002 - accuracy: 0.2617 - val_loss: -75.9257 - val_accuracy: 0.2609
Epoch 315/830
20/21 [===========================>..] - ETA: 0s - loss: -84.6829 - accuracy: 0.2625
Epoch 315: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -84.4306 - accuracy: 0.2617 - val_loss: -76.1521 - val_accuracy: 0.2609
Epoch 316/830
20/21 [===========================>..] - ETA: 0s - loss: -85.2219 - accuracy: 0.2609
Epoch 316: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -84.6964 - accuracy: 0.2617 - val_loss: -76.3904 - val_accuracy: 0.2609
Epoch 317/830
20/21 [===========================>..] - ETA: 0s - loss: -84.7135 - accuracy: 0.2625
Epoch 317: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -84.9614 - accuracy: 0.2617 - val_loss: -76.6586 - val_accuracy: 0.2609
Epoch 318/830
20/21 [===========================>..] - ETA: 0s - loss: -85.4875 - accuracy: 0.2625
Epoch 318: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -85.2443 - accuracy: 0.2617 - val_loss: -76.8829 - val_accuracy: 0.2609
Epoch 319/830
20/21 [===========================>..] - ETA: 0s - loss: -85.2871 - accuracy: 0.2625
Epoch 319: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -85.5153 - accuracy: 0.2617 - val_loss: -77.1510 - val_accuracy: 0.2609
Epoch 320/830
20/21 [===========================>..] - ETA: 0s - loss: -85.3375 - accuracy: 0.2609
Epoch 320: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -85.7969 - accuracy: 0.2617 - val_loss: -77.4009 - val_accuracy: 0.2609
Epoch 321/830
20/21 [===========================>..] - ETA: 0s - loss: -85.6709 - accuracy: 0.2625
Epoch 321: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -86.0685 - accuracy: 0.2617 - val_loss: -77.6469 - val_accuracy: 0.2609
Epoch 322/830
20/21 [===========================>..] - ETA: 0s - loss: -86.1080 - accuracy: 0.2609
Epoch 322: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -86.3383 - accuracy: 0.2617 - val_loss: -77.8863 - val_accuracy: 0.2609
Epoch 323/830
20/21 [===========================>..] - ETA: 0s - loss: -86.0393 - accuracy: 0.2625
Epoch 323: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -86.6101 - accuracy: 0.2617 - val_loss: -78.1383 - val_accuracy: 0.2609
Epoch 324/830
20/21 [===========================>..] - ETA: 0s - loss: -86.3378 - accuracy: 0.2625
Epoch 324: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -86.8816 - accuracy: 0.2617 - val_loss: -78.3778 - val_accuracy: 0.2609
Epoch 325/830
20/21 [===========================>..] - ETA: 0s - loss: -87.6125 - accuracy: 0.2609
Epoch 325: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -87.1498 - accuracy: 0.2617 - val_loss: -78.5886 - val_accuracy: 0.2609
Epoch 326/830
20/21 [===========================>..] - ETA: 0s - loss: -87.3657 - accuracy: 0.2609
Epoch 326: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -87.3956 - accuracy: 0.2617 - val_loss: -78.8358 - val_accuracy: 0.2609
Epoch 327/830
20/21 [===========================>..] - ETA: 0s - loss: -87.5303 - accuracy: 0.2625
Epoch 327: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -87.6735 - accuracy: 0.2617 - val_loss: -79.0903 - val_accuracy: 0.2609
Epoch 328/830
20/21 [===========================>..] - ETA: 0s - loss: -88.1389 - accuracy: 0.2625
Epoch 328: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -87.9487 - accuracy: 0.2617 - val_loss: -79.3260 - val_accuracy: 0.2609
Epoch 329/830
20/21 [===========================>..] - ETA: 0s - loss: -88.1998 - accuracy: 0.2609
Epoch 329: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -88.2255 - accuracy: 0.2617 - val_loss: -79.5893 - val_accuracy: 0.2609
Epoch 330/830
20/21 [===========================>..] - ETA: 0s - loss: -88.7868 - accuracy: 0.2594
Epoch 330: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -88.5102 - accuracy: 0.2617 - val_loss: -79.8319 - val_accuracy: 0.2609
Epoch 331/830
20/21 [===========================>..] - ETA: 0s - loss: -88.5206 - accuracy: 0.2625
Epoch 331: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -88.7838 - accuracy: 0.2617 - val_loss: -80.0999 - val_accuracy: 0.2609
Epoch 332/830
20/21 [===========================>..] - ETA: 0s - loss: -89.2228 - accuracy: 0.2625
Epoch 332: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -89.0701 - accuracy: 0.2617 - val_loss: -80.3344 - val_accuracy: 0.2609
Epoch 333/830
20/21 [===========================>..] - ETA: 0s - loss: -89.0561 - accuracy: 0.2609
Epoch 333: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -89.3457 - accuracy: 0.2617 - val_loss: -80.6012 - val_accuracy: 0.2609
Epoch 334/830
20/21 [===========================>..] - ETA: 0s - loss: -90.1357 - accuracy: 0.2609
Epoch 334: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -89.6217 - accuracy: 0.2617 - val_loss: -80.8109 - val_accuracy: 0.2609
Epoch 335/830
20/21 [===========================>..] - ETA: 0s - loss: -89.5474 - accuracy: 0.2609
Epoch 335: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -89.8691 - accuracy: 0.2617 - val_loss: -81.0714 - val_accuracy: 0.2609
Epoch 336/830
20/21 [===========================>..] - ETA: 0s - loss: -89.9683 - accuracy: 0.2625
Epoch 336: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -90.1480 - accuracy: 0.2617 - val_loss: -81.3112 - val_accuracy: 0.2609
Epoch 337/830
20/21 [===========================>..] - ETA: 0s - loss: -90.4476 - accuracy: 0.2609
Epoch 337: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -90.4179 - accuracy: 0.2617 - val_loss: -81.5517 - val_accuracy: 0.2609
Epoch 338/830
20/21 [===========================>..] - ETA: 0s - loss: -91.1482 - accuracy: 0.2609
Epoch 338: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -90.6894 - accuracy: 0.2617 - val_loss: -81.7844 - val_accuracy: 0.2609
Epoch 339/830
20/21 [===========================>..] - ETA: 0s - loss: -91.4450 - accuracy: 0.2609
Epoch 339: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -90.9490 - accuracy: 0.2617 - val_loss: -82.0193 - val_accuracy: 0.2609
Epoch 340/830
20/21 [===========================>..] - ETA: 0s - loss: -90.9326 - accuracy: 0.2625
Epoch 340: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -91.2113 - accuracy: 0.2617 - val_loss: -82.2797 - val_accuracy: 0.2609
Epoch 341/830
20/21 [===========================>..] - ETA: 0s - loss: -91.5442 - accuracy: 0.2625
Epoch 341: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -91.5012 - accuracy: 0.2617 - val_loss: -82.5290 - val_accuracy: 0.2609
Epoch 342/830
20/21 [===========================>..] - ETA: 0s - loss: -91.7284 - accuracy: 0.2609
Epoch 342: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -91.7655 - accuracy: 0.2617 - val_loss: -82.7645 - val_accuracy: 0.2609
Epoch 343/830
20/21 [===========================>..] - ETA: 0s - loss: -92.2695 - accuracy: 0.2625
Epoch 343: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -92.0379 - accuracy: 0.2617 - val_loss: -83.0114 - val_accuracy: 0.2609
Epoch 344/830
20/21 [===========================>..] - ETA: 0s - loss: -92.0618 - accuracy: 0.2609
Epoch 344: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -92.3111 - accuracy: 0.2617 - val_loss: -83.2696 - val_accuracy: 0.2609
Epoch 345/830
20/21 [===========================>..] - ETA: 0s - loss: -92.1231 - accuracy: 0.2609
Epoch 345: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -92.5844 - accuracy: 0.2617 - val_loss: -83.5121 - val_accuracy: 0.2609
Epoch 346/830
20/21 [===========================>..] - ETA: 0s - loss: -91.9851 - accuracy: 0.2625
Epoch 346: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -92.8655 - accuracy: 0.2617 - val_loss: -83.7721 - val_accuracy: 0.2609
Epoch 347/830
20/21 [===========================>..] - ETA: 0s - loss: -92.1528 - accuracy: 0.2625
Epoch 347: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -93.1205 - accuracy: 0.2617 - val_loss: -83.9903 - val_accuracy: 0.2609
Epoch 348/830
20/21 [===========================>..] - ETA: 0s - loss: -93.5020 - accuracy: 0.2625
Epoch 348: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -93.3729 - accuracy: 0.2617 - val_loss: -84.2013 - val_accuracy: 0.2609
Epoch 349/830
20/21 [===========================>..] - ETA: 0s - loss: -92.8723 - accuracy: 0.2625
Epoch 349: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -93.6236 - accuracy: 0.2617 - val_loss: -84.4564 - val_accuracy: 0.2609
Epoch 350/830
20/21 [===========================>..] - ETA: 0s - loss: -93.2196 - accuracy: 0.2625
Epoch 350: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -93.8950 - accuracy: 0.2617 - val_loss: -84.6943 - val_accuracy: 0.2609
Epoch 351/830
20/21 [===========================>..] - ETA: 0s - loss: -94.1958 - accuracy: 0.2609
Epoch 351: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -94.1597 - accuracy: 0.2617 - val_loss: -84.9155 - val_accuracy: 0.2609
Epoch 352/830
20/21 [===========================>..] - ETA: 0s - loss: -93.8061 - accuracy: 0.2625
Epoch 352: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -94.4205 - accuracy: 0.2617 - val_loss: -85.1721 - val_accuracy: 0.2609
Epoch 353/830
20/21 [===========================>..] - ETA: 0s - loss: -95.4982 - accuracy: 0.2625
Epoch 353: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -94.6900 - accuracy: 0.2617 - val_loss: -85.3725 - val_accuracy: 0.2609
Epoch 354/830
20/21 [===========================>..] - ETA: 0s - loss: -94.8937 - accuracy: 0.2609
Epoch 354: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -94.9262 - accuracy: 0.2617 - val_loss: -85.6164 - val_accuracy: 0.2609
Epoch 355/830
20/21 [===========================>..] - ETA: 0s - loss: -95.8359 - accuracy: 0.2609
Epoch 355: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -95.2006 - accuracy: 0.2617 - val_loss: -85.8481 - val_accuracy: 0.2609
Epoch 356/830
20/21 [===========================>..] - ETA: 0s - loss: -95.6738 - accuracy: 0.2625
Epoch 356: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -95.4534 - accuracy: 0.2617 - val_loss: -86.0850 - val_accuracy: 0.2609
Epoch 357/830
20/21 [===========================>..] - ETA: 0s - loss: -95.7537 - accuracy: 0.2625
Epoch 357: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -95.7224 - accuracy: 0.2617 - val_loss: -86.3404 - val_accuracy: 0.2609
Epoch 358/830
20/21 [===========================>..] - ETA: 0s - loss: -95.6706 - accuracy: 0.2609
Epoch 358: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -95.9956 - accuracy: 0.2617 - val_loss: -86.5900 - val_accuracy: 0.2609
Epoch 359/830
20/21 [===========================>..] - ETA: 0s - loss: -95.7171 - accuracy: 0.2625
Epoch 359: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -96.2794 - accuracy: 0.2617 - val_loss: -86.8517 - val_accuracy: 0.2609
Epoch 360/830
20/21 [===========================>..] - ETA: 0s - loss: -97.0751 - accuracy: 0.2609
Epoch 360: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -96.5525 - accuracy: 0.2617 - val_loss: -87.0571 - val_accuracy: 0.2609
Epoch 361/830
20/21 [===========================>..] - ETA: 0s - loss: -97.4057 - accuracy: 0.2609
Epoch 361: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -96.7952 - accuracy: 0.2617 - val_loss: -87.2811 - val_accuracy: 0.2609
Epoch 362/830
20/21 [===========================>..] - ETA: 0s - loss: -97.3543 - accuracy: 0.2594
Epoch 362: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 191ms/step - loss: -97.0510 - accuracy: 0.2617 - val_loss: -87.5253 - val_accuracy: 0.2609
Epoch 363/830
20/21 [===========================>..] - ETA: 0s - loss: -97.3020 - accuracy: 0.2609
Epoch 363: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -97.3192 - accuracy: 0.2617 - val_loss: -87.7822 - val_accuracy: 0.2609
Epoch 364/830
20/21 [===========================>..] - ETA: 0s - loss: -97.8211 - accuracy: 0.2625
Epoch 364: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -97.6057 - accuracy: 0.2617 - val_loss: -88.0325 - val_accuracy: 0.2609
Epoch 365/830
20/21 [===========================>..] - ETA: 0s - loss: -98.1899 - accuracy: 0.2594
Epoch 365: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -97.8840 - accuracy: 0.2617 - val_loss: -88.2799 - val_accuracy: 0.2609
Epoch 366/830
20/21 [===========================>..] - ETA: 0s - loss: -98.6840 - accuracy: 0.2609
Epoch 366: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -98.1629 - accuracy: 0.2617 - val_loss: -88.5238 - val_accuracy: 0.2609
Epoch 367/830
20/21 [===========================>..] - ETA: 0s - loss: -98.8051 - accuracy: 0.2625
Epoch 367: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -98.4301 - accuracy: 0.2617 - val_loss: -88.7648 - val_accuracy: 0.2609
Epoch 368/830
20/21 [===========================>..] - ETA: 0s - loss: -99.4692 - accuracy: 0.2625
Epoch 368: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -98.7001 - accuracy: 0.2617 - val_loss: -89.0006 - val_accuracy: 0.2609
Epoch 369/830
20/21 [===========================>..] - ETA: 0s - loss: -99.4492 - accuracy: 0.2609
Epoch 369: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -98.9536 - accuracy: 0.2617 - val_loss: -89.2320 - val_accuracy: 0.2609
Epoch 370/830
20/21 [===========================>..] - ETA: 0s - loss: -99.7275 - accuracy: 0.2609
Epoch 370: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -99.2103 - accuracy: 0.2617 - val_loss: -89.4679 - val_accuracy: 0.2609
Epoch 371/830
20/21 [===========================>..] - ETA: 0s - loss: -99.7845 - accuracy: 0.2594
Epoch 371: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -99.4737 - accuracy: 0.2617 - val_loss: -89.7097 - val_accuracy: 0.2609
Epoch 372/830
20/21 [===========================>..] - ETA: 0s - loss: -99.6007 - accuracy: 0.2625
Epoch 372: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -99.7451 - accuracy: 0.2617 - val_loss: -89.9680 - val_accuracy: 0.2609
Epoch 373/830
20/21 [===========================>..] - ETA: 0s - loss: -100.3405 - accuracy: 0.2594
Epoch 373: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -100.0279 - accuracy: 0.2617 - val_loss: -90.2064 - val_accuracy: 0.2609
Epoch 374/830
20/21 [===========================>..] - ETA: 0s - loss: -100.4651 - accuracy: 0.2625
Epoch 374: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -100.2992 - accuracy: 0.2617 - val_loss: -90.4588 - val_accuracy: 0.2609
Epoch 375/830
20/21 [===========================>..] - ETA: 0s - loss: -99.9594 - accuracy: 0.2625
Epoch 375: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -100.5648 - accuracy: 0.2617 - val_loss: -90.7071 - val_accuracy: 0.2609
Epoch 376/830
20/21 [===========================>..] - ETA: 0s - loss: -101.1587 - accuracy: 0.2594
Epoch 376: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -100.8435 - accuracy: 0.2617 - val_loss: -90.9315 - val_accuracy: 0.2609
Epoch 377/830
20/21 [===========================>..] - ETA: 0s - loss: -101.7181 - accuracy: 0.2609
Epoch 377: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -101.1024 - accuracy: 0.2617 - val_loss: -91.1618 - val_accuracy: 0.2609
Epoch 378/830
20/21 [===========================>..] - ETA: 0s - loss: -101.3966 - accuracy: 0.2625
Epoch 378: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -101.3656 - accuracy: 0.2617 - val_loss: -91.4170 - val_accuracy: 0.2609
Epoch 379/830
20/21 [===========================>..] - ETA: 0s - loss: -101.9052 - accuracy: 0.2625
Epoch 379: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -101.6370 - accuracy: 0.2617 - val_loss: -91.6539 - val_accuracy: 0.2609
Epoch 380/830
20/21 [===========================>..] - ETA: 0s - loss: -101.1082 - accuracy: 0.2625
Epoch 380: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -101.8995 - accuracy: 0.2617 - val_loss: -91.9166 - val_accuracy: 0.2609
Epoch 381/830
20/21 [===========================>..] - ETA: 0s - loss: -101.8033 - accuracy: 0.2609
Epoch 381: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -102.1760 - accuracy: 0.2617 - val_loss: -92.1464 - val_accuracy: 0.2609
Epoch 382/830
20/21 [===========================>..] - ETA: 0s - loss: -102.7704 - accuracy: 0.2625
Epoch 382: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -102.4423 - accuracy: 0.2617 - val_loss: -92.3752 - val_accuracy: 0.2609
Epoch 383/830
20/21 [===========================>..] - ETA: 0s - loss: -101.7315 - accuracy: 0.2625
Epoch 383: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -102.6991 - accuracy: 0.2617 - val_loss: -92.6343 - val_accuracy: 0.2609
Epoch 384/830
20/21 [===========================>..] - ETA: 0s - loss: -102.1033 - accuracy: 0.2625
Epoch 384: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -102.9656 - accuracy: 0.2617 - val_loss: -92.8613 - val_accuracy: 0.2609
Epoch 385/830
20/21 [===========================>..] - ETA: 0s - loss: -103.2408 - accuracy: 0.2609
Epoch 385: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -103.2205 - accuracy: 0.2617 - val_loss: -93.0777 - val_accuracy: 0.2609
Epoch 386/830
20/21 [===========================>..] - ETA: 0s - loss: -103.1869 - accuracy: 0.2609
Epoch 386: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -103.4774 - accuracy: 0.2617 - val_loss: -93.3324 - val_accuracy: 0.2609
Epoch 387/830
20/21 [===========================>..] - ETA: 0s - loss: -103.6852 - accuracy: 0.2609
Epoch 387: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -103.7529 - accuracy: 0.2617 - val_loss: -93.5663 - val_accuracy: 0.2609
Epoch 388/830
20/21 [===========================>..] - ETA: 0s - loss: -104.6437 - accuracy: 0.2609
Epoch 388: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -104.0306 - accuracy: 0.2617 - val_loss: -93.8015 - val_accuracy: 0.2609
Epoch 389/830
20/21 [===========================>..] - ETA: 0s - loss: -104.9074 - accuracy: 0.2609
Epoch 389: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -104.2821 - accuracy: 0.2617 - val_loss: -94.0244 - val_accuracy: 0.2609
Epoch 390/830
20/21 [===========================>..] - ETA: 0s - loss: -105.0709 - accuracy: 0.2609
Epoch 390: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -104.5333 - accuracy: 0.2617 - val_loss: -94.2582 - val_accuracy: 0.2609
Epoch 391/830
20/21 [===========================>..] - ETA: 0s - loss: -104.1204 - accuracy: 0.2625
Epoch 391: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -104.7943 - accuracy: 0.2617 - val_loss: -94.5276 - val_accuracy: 0.2609
Epoch 392/830
20/21 [===========================>..] - ETA: 0s - loss: -105.6368 - accuracy: 0.2609
Epoch 392: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -105.0809 - accuracy: 0.2617 - val_loss: -94.7475 - val_accuracy: 0.2609
Epoch 393/830
20/21 [===========================>..] - ETA: 0s - loss: -105.2927 - accuracy: 0.2609
Epoch 393: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -105.3314 - accuracy: 0.2617 - val_loss: -94.9967 - val_accuracy: 0.2609
Epoch 394/830
20/21 [===========================>..] - ETA: 0s - loss: -105.6284 - accuracy: 0.2609
Epoch 394: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -105.6158 - accuracy: 0.2617 - val_loss: -95.2542 - val_accuracy: 0.2609
Epoch 395/830
20/21 [===========================>..] - ETA: 0s - loss: -106.1304 - accuracy: 0.2625
Epoch 395: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -105.8972 - accuracy: 0.2617 - val_loss: -95.5014 - val_accuracy: 0.2609
Epoch 396/830
20/21 [===========================>..] - ETA: 0s - loss: -105.8444 - accuracy: 0.2609
Epoch 396: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -106.1759 - accuracy: 0.2617 - val_loss: -95.7659 - val_accuracy: 0.2609
Epoch 397/830
20/21 [===========================>..] - ETA: 0s - loss: -106.5778 - accuracy: 0.2609
Epoch 397: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -106.4535 - accuracy: 0.2617 - val_loss: -95.9997 - val_accuracy: 0.2609
Epoch 398/830
20/21 [===========================>..] - ETA: 0s - loss: -107.3542 - accuracy: 0.2609
Epoch 398: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -106.7274 - accuracy: 0.2617 - val_loss: -96.2344 - val_accuracy: 0.2609
Epoch 399/830
20/21 [===========================>..] - ETA: 0s - loss: -107.2227 - accuracy: 0.2625
Epoch 399: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -106.9924 - accuracy: 0.2617 - val_loss: -96.4862 - val_accuracy: 0.2609
Epoch 400/830
20/21 [===========================>..] - ETA: 0s - loss: -107.7104 - accuracy: 0.2625
Epoch 400: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -107.2676 - accuracy: 0.2617 - val_loss: -96.7254 - val_accuracy: 0.2609
Epoch 401/830
20/21 [===========================>..] - ETA: 0s - loss: -108.1535 - accuracy: 0.2609
Epoch 401: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -107.5325 - accuracy: 0.2617 - val_loss: -96.9573 - val_accuracy: 0.2609
Epoch 402/830
20/21 [===========================>..] - ETA: 0s - loss: -106.6579 - accuracy: 0.2625
Epoch 402: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -107.7865 - accuracy: 0.2617 - val_loss: -97.2261 - val_accuracy: 0.2609
Epoch 403/830
20/21 [===========================>..] - ETA: 0s - loss: -106.8282 - accuracy: 0.2625
Epoch 403: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -108.0617 - accuracy: 0.2617 - val_loss: -97.4528 - val_accuracy: 0.2609
Epoch 404/830
20/21 [===========================>..] - ETA: 0s - loss: -108.3087 - accuracy: 0.2609
Epoch 404: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -108.3026 - accuracy: 0.2617 - val_loss: -97.6480 - val_accuracy: 0.2609
Epoch 405/830
20/21 [===========================>..] - ETA: 0s - loss: -108.5137 - accuracy: 0.2609
Epoch 405: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -108.5518 - accuracy: 0.2617 - val_loss: -97.8951 - val_accuracy: 0.2609
Epoch 406/830
20/21 [===========================>..] - ETA: 0s - loss: -108.8290 - accuracy: 0.2609
Epoch 406: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -108.8249 - accuracy: 0.2617 - val_loss: -98.1405 - val_accuracy: 0.2609
Epoch 407/830
20/21 [===========================>..] - ETA: 0s - loss: -109.3819 - accuracy: 0.2625
Epoch 407: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -109.1030 - accuracy: 0.2617 - val_loss: -98.3854 - val_accuracy: 0.2609
Epoch 408/830
20/21 [===========================>..] - ETA: 0s - loss: -110.0320 - accuracy: 0.2609
Epoch 408: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -109.3768 - accuracy: 0.2617 - val_loss: -98.6153 - val_accuracy: 0.2609
Epoch 409/830
20/21 [===========================>..] - ETA: 0s - loss: -109.9668 - accuracy: 0.2594
Epoch 409: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -109.6243 - accuracy: 0.2617 - val_loss: -98.8537 - val_accuracy: 0.2609
Epoch 410/830
20/21 [===========================>..] - ETA: 0s - loss: -110.5316 - accuracy: 0.2609
Epoch 410: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -109.8951 - accuracy: 0.2617 - val_loss: -99.0947 - val_accuracy: 0.2609
Epoch 411/830
20/21 [===========================>..] - ETA: 0s - loss: -109.9386 - accuracy: 0.2609
Epoch 411: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -110.1656 - accuracy: 0.2617 - val_loss: -99.3568 - val_accuracy: 0.2609
Epoch 412/830
20/21 [===========================>..] - ETA: 0s - loss: -110.8183 - accuracy: 0.2625
Epoch 412: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -110.4489 - accuracy: 0.2617 - val_loss: -99.5896 - val_accuracy: 0.2609
Epoch 413/830
20/21 [===========================>..] - ETA: 0s - loss: -110.4525 - accuracy: 0.2625
Epoch 413: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -110.7120 - accuracy: 0.2617 - val_loss: -99.8416 - val_accuracy: 0.2609
Epoch 414/830
20/21 [===========================>..] - ETA: 0s - loss: -109.9106 - accuracy: 0.2625
Epoch 414: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -110.9866 - accuracy: 0.2617 - val_loss: -100.0990 - val_accuracy: 0.2609
Epoch 415/830
20/21 [===========================>..] - ETA: 0s - loss: -110.4086 - accuracy: 0.2625
Epoch 415: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -111.2553 - accuracy: 0.2617 - val_loss: -100.3271 - val_accuracy: 0.2609
Epoch 416/830
20/21 [===========================>..] - ETA: 0s - loss: -112.6480 - accuracy: 0.2625
Epoch 416: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -111.5076 - accuracy: 0.2617 - val_loss: -100.5133 - val_accuracy: 0.2609
Epoch 417/830
20/21 [===========================>..] - ETA: 0s - loss: -111.5575 - accuracy: 0.2625
Epoch 417: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -111.7214 - accuracy: 0.2617 - val_loss: -100.7475 - val_accuracy: 0.2609
Epoch 418/830
20/21 [===========================>..] - ETA: 0s - loss: -111.6604 - accuracy: 0.2609
Epoch 418: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -111.9870 - accuracy: 0.2617 - val_loss: -100.9926 - val_accuracy: 0.2609
Epoch 419/830
20/21 [===========================>..] - ETA: 0s - loss: -112.0547 - accuracy: 0.2609
Epoch 419: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -112.2594 - accuracy: 0.2617 - val_loss: -101.2363 - val_accuracy: 0.2609
Epoch 420/830
20/21 [===========================>..] - ETA: 0s - loss: -112.5426 - accuracy: 0.2609
Epoch 420: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -112.5300 - accuracy: 0.2617 - val_loss: -101.4767 - val_accuracy: 0.2609
Epoch 421/830
20/21 [===========================>..] - ETA: 0s - loss: -113.0582 - accuracy: 0.2625
Epoch 421: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -112.8026 - accuracy: 0.2617 - val_loss: -101.7168 - val_accuracy: 0.2609
Epoch 422/830
20/21 [===========================>..] - ETA: 0s - loss: -113.6740 - accuracy: 0.2609
Epoch 422: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -113.0725 - accuracy: 0.2617 - val_loss: -101.9530 - val_accuracy: 0.2609
Epoch 423/830
20/21 [===========================>..] - ETA: 0s - loss: -113.7061 - accuracy: 0.2625
Epoch 423: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -113.3334 - accuracy: 0.2617 - val_loss: -102.1977 - val_accuracy: 0.2609
Epoch 424/830
20/21 [===========================>..] - ETA: 0s - loss: -113.2780 - accuracy: 0.2609
Epoch 424: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -113.6101 - accuracy: 0.2617 - val_loss: -102.4618 - val_accuracy: 0.2609
Epoch 425/830
20/21 [===========================>..] - ETA: 0s - loss: -112.9502 - accuracy: 0.2625
Epoch 425: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -113.8921 - accuracy: 0.2617 - val_loss: -102.7185 - val_accuracy: 0.2609
Epoch 426/830
20/21 [===========================>..] - ETA: 0s - loss: -114.2650 - accuracy: 0.2609
Epoch 426: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -114.1642 - accuracy: 0.2617 - val_loss: -102.9335 - val_accuracy: 0.2609
Epoch 427/830
20/21 [===========================>..] - ETA: 0s - loss: -114.7465 - accuracy: 0.2625
Epoch 427: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -114.4247 - accuracy: 0.2617 - val_loss: -103.1796 - val_accuracy: 0.2609
Epoch 428/830
20/21 [===========================>..] - ETA: 0s - loss: -115.0547 - accuracy: 0.2594
Epoch 428: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -114.6963 - accuracy: 0.2617 - val_loss: -103.4213 - val_accuracy: 0.2609
Epoch 429/830
20/21 [===========================>..] - ETA: 0s - loss: -113.8363 - accuracy: 0.2625
Epoch 429: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -114.9698 - accuracy: 0.2617 - val_loss: -103.6972 - val_accuracy: 0.2609
Epoch 430/830
20/21 [===========================>..] - ETA: 0s - loss: -116.2079 - accuracy: 0.2625
Epoch 430: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -115.2522 - accuracy: 0.2617 - val_loss: -103.8881 - val_accuracy: 0.2609
Epoch 431/830
20/21 [===========================>..] - ETA: 0s - loss: -116.3231 - accuracy: 0.2625
Epoch 431: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -115.4715 - accuracy: 0.2617 - val_loss: -104.1018 - val_accuracy: 0.2609
Epoch 432/830
20/21 [===========================>..] - ETA: 0s - loss: -115.8003 - accuracy: 0.2609
Epoch 432: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -115.7165 - accuracy: 0.2617 - val_loss: -104.3493 - val_accuracy: 0.2609
Epoch 433/830
20/21 [===========================>..] - ETA: 0s - loss: -116.3792 - accuracy: 0.2625
Epoch 433: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -115.9951 - accuracy: 0.2617 - val_loss: -104.5958 - val_accuracy: 0.2609
Epoch 434/830
20/21 [===========================>..] - ETA: 0s - loss: -115.9659 - accuracy: 0.2625
Epoch 434: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -116.2687 - accuracy: 0.2617 - val_loss: -104.8598 - val_accuracy: 0.2609
Epoch 435/830
20/21 [===========================>..] - ETA: 0s - loss: -117.2465 - accuracy: 0.2609
Epoch 435: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -116.5526 - accuracy: 0.2617 - val_loss: -105.0820 - val_accuracy: 0.2609
Epoch 436/830
20/21 [===========================>..] - ETA: 0s - loss: -116.8384 - accuracy: 0.2625
Epoch 436: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -116.8088 - accuracy: 0.2617 - val_loss: -105.3351 - val_accuracy: 0.2609
Epoch 437/830
20/21 [===========================>..] - ETA: 0s - loss: -117.4765 - accuracy: 0.2625
Epoch 437: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -117.0778 - accuracy: 0.2617 - val_loss: -105.5662 - val_accuracy: 0.2609
Epoch 438/830
20/21 [===========================>..] - ETA: 0s - loss: -117.2578 - accuracy: 0.2609
Epoch 438: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -117.3492 - accuracy: 0.2617 - val_loss: -105.8283 - val_accuracy: 0.2609
Epoch 439/830
20/21 [===========================>..] - ETA: 0s - loss: -117.6729 - accuracy: 0.2609
Epoch 439: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -117.6325 - accuracy: 0.2617 - val_loss: -106.0792 - val_accuracy: 0.2609
Epoch 440/830
20/21 [===========================>..] - ETA: 0s - loss: -117.5729 - accuracy: 0.2609
Epoch 440: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -117.9174 - accuracy: 0.2617 - val_loss: -106.3416 - val_accuracy: 0.2609
Epoch 441/830
20/21 [===========================>..] - ETA: 0s - loss: -117.8996 - accuracy: 0.2625
Epoch 441: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -118.1953 - accuracy: 0.2617 - val_loss: -106.5864 - val_accuracy: 0.2609
Epoch 442/830
20/21 [===========================>..] - ETA: 0s - loss: -118.4104 - accuracy: 0.2609
Epoch 442: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -118.4721 - accuracy: 0.2617 - val_loss: -106.8293 - val_accuracy: 0.2609
Epoch 443/830
20/21 [===========================>..] - ETA: 0s - loss: -117.9635 - accuracy: 0.2625
Epoch 443: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -118.7495 - accuracy: 0.2617 - val_loss: -107.0952 - val_accuracy: 0.2609
Epoch 444/830
20/21 [===========================>..] - ETA: 0s - loss: -119.4075 - accuracy: 0.2594
Epoch 444: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -119.0355 - accuracy: 0.2617 - val_loss: -107.3202 - val_accuracy: 0.2609
Epoch 445/830
20/21 [===========================>..] - ETA: 0s - loss: -120.0023 - accuracy: 0.2609
Epoch 445: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -119.2972 - accuracy: 0.2617 - val_loss: -107.5515 - val_accuracy: 0.2609
Epoch 446/830
20/21 [===========================>..] - ETA: 0s - loss: -119.5379 - accuracy: 0.2609
Epoch 446: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -119.5524 - accuracy: 0.2617 - val_loss: -107.8022 - val_accuracy: 0.2609
Epoch 447/830
20/21 [===========================>..] - ETA: 0s - loss: -120.2940 - accuracy: 0.2625
Epoch 447: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -119.8343 - accuracy: 0.2617 - val_loss: -108.0440 - val_accuracy: 0.2609
Epoch 448/830
20/21 [===========================>..] - ETA: 0s - loss: -120.8097 - accuracy: 0.2609
Epoch 448: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -120.1044 - accuracy: 0.2617 - val_loss: -108.2829 - val_accuracy: 0.2609
Epoch 449/830
20/21 [===========================>..] - ETA: 0s - loss: -120.4829 - accuracy: 0.2609
Epoch 449: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -120.3651 - accuracy: 0.2617 - val_loss: -108.5330 - val_accuracy: 0.2609
Epoch 450/830
20/21 [===========================>..] - ETA: 0s - loss: -121.5657 - accuracy: 0.2625
Epoch 450: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -120.6476 - accuracy: 0.2617 - val_loss: -108.7671 - val_accuracy: 0.2609
Epoch 451/830
20/21 [===========================>..] - ETA: 0s - loss: -120.9482 - accuracy: 0.2609
Epoch 451: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -120.8975 - accuracy: 0.2617 - val_loss: -109.0101 - val_accuracy: 0.2609
Epoch 452/830
20/21 [===========================>..] - ETA: 0s - loss: -119.8856 - accuracy: 0.2625
Epoch 452: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -121.1739 - accuracy: 0.2617 - val_loss: -109.2823 - val_accuracy: 0.2609
Epoch 453/830
20/21 [===========================>..] - ETA: 0s - loss: -121.6435 - accuracy: 0.2625
Epoch 453: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -121.4493 - accuracy: 0.2617 - val_loss: -109.4870 - val_accuracy: 0.2609
Epoch 454/830
20/21 [===========================>..] - ETA: 0s - loss: -122.0319 - accuracy: 0.2625
Epoch 454: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -121.6967 - accuracy: 0.2617 - val_loss: -109.7227 - val_accuracy: 0.2609
Epoch 455/830
20/21 [===========================>..] - ETA: 0s - loss: -122.3468 - accuracy: 0.2625
Epoch 455: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 188ms/step - loss: -121.9705 - accuracy: 0.2617 - val_loss: -109.9741 - val_accuracy: 0.2609
Epoch 456/830
20/21 [===========================>..] - ETA: 0s - loss: -123.3125 - accuracy: 0.2625
Epoch 456: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -122.2412 - accuracy: 0.2617 - val_loss: -110.1935 - val_accuracy: 0.2609
Epoch 457/830
20/21 [===========================>..] - ETA: 0s - loss: -122.1027 - accuracy: 0.2625
Epoch 457: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -122.4840 - accuracy: 0.2617 - val_loss: -110.4504 - val_accuracy: 0.2609
Epoch 458/830
20/21 [===========================>..] - ETA: 0s - loss: -123.7647 - accuracy: 0.2625
Epoch 458: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -122.7700 - accuracy: 0.2617 - val_loss: -110.6760 - val_accuracy: 0.2609
Epoch 459/830
20/21 [===========================>..] - ETA: 0s - loss: -122.7271 - accuracy: 0.2609
Epoch 459: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -123.0165 - accuracy: 0.2617 - val_loss: -110.9267 - val_accuracy: 0.2609
Epoch 460/830
20/21 [===========================>..] - ETA: 0s - loss: -123.3308 - accuracy: 0.2609
Epoch 460: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -123.2847 - accuracy: 0.2617 - val_loss: -111.1674 - val_accuracy: 0.2609
Epoch 461/830
20/21 [===========================>..] - ETA: 0s - loss: -123.5706 - accuracy: 0.2609
Epoch 461: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -123.5646 - accuracy: 0.2617 - val_loss: -111.4218 - val_accuracy: 0.2609
Epoch 462/830
20/21 [===========================>..] - ETA: 0s - loss: -124.4777 - accuracy: 0.2609
Epoch 462: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -123.8369 - accuracy: 0.2617 - val_loss: -111.6441 - val_accuracy: 0.2609
Epoch 463/830
20/21 [===========================>..] - ETA: 0s - loss: -124.4756 - accuracy: 0.2594
Epoch 463: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -124.0878 - accuracy: 0.2617 - val_loss: -111.8838 - val_accuracy: 0.2609
Epoch 464/830
20/21 [===========================>..] - ETA: 0s - loss: -123.5429 - accuracy: 0.2625
Epoch 464: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -124.3694 - accuracy: 0.2617 - val_loss: -112.1647 - val_accuracy: 0.2609
Epoch 465/830
20/21 [===========================>..] - ETA: 0s - loss: -125.3952 - accuracy: 0.2609
Epoch 465: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -124.6521 - accuracy: 0.2617 - val_loss: -112.3707 - val_accuracy: 0.2609
Epoch 466/830
20/21 [===========================>..] - ETA: 0s - loss: -125.7110 - accuracy: 0.2609
Epoch 466: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -124.9011 - accuracy: 0.2617 - val_loss: -112.6055 - val_accuracy: 0.2609
Epoch 467/830
21/21 [==============================] - ETA: 0s - loss: -125.1577 - accuracy: 0.2617
Epoch 467: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -125.1577 - accuracy: 0.2617 - val_loss: -112.8616 - val_accuracy: 0.2609
Epoch 468/830
20/21 [===========================>..] - ETA: 0s - loss: -125.8258 - accuracy: 0.2594
Epoch 468: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -125.4338 - accuracy: 0.2617 - val_loss: -113.0920 - val_accuracy: 0.2609
Epoch 469/830
20/21 [===========================>..] - ETA: 0s - loss: -124.9753 - accuracy: 0.2625
Epoch 469: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -125.7079 - accuracy: 0.2617 - val_loss: -113.3618 - val_accuracy: 0.2609
Epoch 470/830
20/21 [===========================>..] - ETA: 0s - loss: -126.2177 - accuracy: 0.2625
Epoch 470: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -125.9842 - accuracy: 0.2617 - val_loss: -113.5836 - val_accuracy: 0.2609
Epoch 471/830
20/21 [===========================>..] - ETA: 0s - loss: -126.3678 - accuracy: 0.2625
Epoch 471: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -126.2487 - accuracy: 0.2617 - val_loss: -113.8295 - val_accuracy: 0.2609
Epoch 472/830
20/21 [===========================>..] - ETA: 0s - loss: -127.1950 - accuracy: 0.2609
Epoch 472: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -126.5227 - accuracy: 0.2617 - val_loss: -114.0650 - val_accuracy: 0.2609
Epoch 473/830
20/21 [===========================>..] - ETA: 0s - loss: -126.4511 - accuracy: 0.2609
Epoch 473: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -126.7826 - accuracy: 0.2617 - val_loss: -114.3275 - val_accuracy: 0.2609
Epoch 474/830
20/21 [===========================>..] - ETA: 0s - loss: -127.7334 - accuracy: 0.2609
Epoch 474: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -127.0679 - accuracy: 0.2617 - val_loss: -114.5546 - val_accuracy: 0.2609
Epoch 475/830
20/21 [===========================>..] - ETA: 0s - loss: -127.3533 - accuracy: 0.2625
Epoch 475: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -127.3195 - accuracy: 0.2617 - val_loss: -114.7995 - val_accuracy: 0.2609
Epoch 476/830
20/21 [===========================>..] - ETA: 0s - loss: -127.9268 - accuracy: 0.2625
Epoch 476: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -127.5931 - accuracy: 0.2617 - val_loss: -115.0348 - val_accuracy: 0.2609
Epoch 477/830
20/21 [===========================>..] - ETA: 0s - loss: -128.8504 - accuracy: 0.2625
Epoch 477: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -127.8596 - accuracy: 0.2617 - val_loss: -115.2657 - val_accuracy: 0.2609
Epoch 478/830
20/21 [===========================>..] - ETA: 0s - loss: -128.1922 - accuracy: 0.2609
Epoch 478: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -128.1056 - accuracy: 0.2617 - val_loss: -115.5065 - val_accuracy: 0.2609
Epoch 479/830
20/21 [===========================>..] - ETA: 0s - loss: -128.7595 - accuracy: 0.2625
Epoch 479: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -128.3792 - accuracy: 0.2617 - val_loss: -115.7455 - val_accuracy: 0.2609
Epoch 480/830
20/21 [===========================>..] - ETA: 0s - loss: -127.7042 - accuracy: 0.2625
Epoch 480: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 160ms/step - loss: -128.6453 - accuracy: 0.2617 - val_loss: -116.0106 - val_accuracy: 0.2609
Epoch 481/830
20/21 [===========================>..] - ETA: 0s - loss: -128.6894 - accuracy: 0.2609
Epoch 481: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -128.9268 - accuracy: 0.2617 - val_loss: -116.2457 - val_accuracy: 0.2609
Epoch 482/830
20/21 [===========================>..] - ETA: 0s - loss: -129.5923 - accuracy: 0.2594
Epoch 482: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -129.1886 - accuracy: 0.2617 - val_loss: -116.4734 - val_accuracy: 0.2609
Epoch 483/830
20/21 [===========================>..] - ETA: 0s - loss: -129.8562 - accuracy: 0.2625
Epoch 483: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -129.4545 - accuracy: 0.2617 - val_loss: -116.7182 - val_accuracy: 0.2609
Epoch 484/830
20/21 [===========================>..] - ETA: 0s - loss: -130.4596 - accuracy: 0.2609
Epoch 484: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -129.7262 - accuracy: 0.2617 - val_loss: -116.9536 - val_accuracy: 0.2609
Epoch 485/830
20/21 [===========================>..] - ETA: 0s - loss: -130.0192 - accuracy: 0.2609
Epoch 485: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -129.9901 - accuracy: 0.2617 - val_loss: -117.2114 - val_accuracy: 0.2609
Epoch 486/830
20/21 [===========================>..] - ETA: 0s - loss: -129.9165 - accuracy: 0.2609
Epoch 486: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -130.2771 - accuracy: 0.2617 - val_loss: -117.4737 - val_accuracy: 0.2609
Epoch 487/830
20/21 [===========================>..] - ETA: 0s - loss: -130.4185 - accuracy: 0.2625
Epoch 487: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -130.5534 - accuracy: 0.2617 - val_loss: -117.7115 - val_accuracy: 0.2609
Epoch 488/830
20/21 [===========================>..] - ETA: 0s - loss: -130.8212 - accuracy: 0.2609
Epoch 488: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -130.8246 - accuracy: 0.2617 - val_loss: -117.9571 - val_accuracy: 0.2609
Epoch 489/830
20/21 [===========================>..] - ETA: 0s - loss: -131.1416 - accuracy: 0.2609
Epoch 489: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -131.0939 - accuracy: 0.2617 - val_loss: -118.1966 - val_accuracy: 0.2609
Epoch 490/830
20/21 [===========================>..] - ETA: 0s - loss: -130.8313 - accuracy: 0.2609
Epoch 490: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -131.3750 - accuracy: 0.2617 - val_loss: -118.4664 - val_accuracy: 0.2609
Epoch 491/830
20/21 [===========================>..] - ETA: 0s - loss: -132.0676 - accuracy: 0.2594
Epoch 491: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -131.6562 - accuracy: 0.2617 - val_loss: -118.6880 - val_accuracy: 0.2609
Epoch 492/830
20/21 [===========================>..] - ETA: 0s - loss: -133.0362 - accuracy: 0.2625
Epoch 492: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -131.9178 - accuracy: 0.2617 - val_loss: -118.9201 - val_accuracy: 0.2609
Epoch 493/830
20/21 [===========================>..] - ETA: 0s - loss: -132.2073 - accuracy: 0.2609
Epoch 493: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -132.1626 - accuracy: 0.2617 - val_loss: -119.1555 - val_accuracy: 0.2609
Epoch 494/830
20/21 [===========================>..] - ETA: 0s - loss: -132.1958 - accuracy: 0.2609
Epoch 494: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -132.4265 - accuracy: 0.2617 - val_loss: -119.4034 - val_accuracy: 0.2609
Epoch 495/830
20/21 [===========================>..] - ETA: 0s - loss: -132.4445 - accuracy: 0.2609
Epoch 495: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -132.7018 - accuracy: 0.2617 - val_loss: -119.6506 - val_accuracy: 0.2609
Epoch 496/830
20/21 [===========================>..] - ETA: 0s - loss: -132.0631 - accuracy: 0.2625
Epoch 496: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -132.9815 - accuracy: 0.2617 - val_loss: -119.9148 - val_accuracy: 0.2609
Epoch 497/830
20/21 [===========================>..] - ETA: 0s - loss: -133.6732 - accuracy: 0.2594
Epoch 497: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -133.2567 - accuracy: 0.2617 - val_loss: -120.1253 - val_accuracy: 0.2609
Epoch 498/830
20/21 [===========================>..] - ETA: 0s - loss: -132.3491 - accuracy: 0.2625
Epoch 498: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -133.5158 - accuracy: 0.2617 - val_loss: -120.3988 - val_accuracy: 0.2609
Epoch 499/830
20/21 [===========================>..] - ETA: 0s - loss: -133.7317 - accuracy: 0.2609
Epoch 499: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -133.7931 - accuracy: 0.2617 - val_loss: -120.6156 - val_accuracy: 0.2609
Epoch 500/830
20/21 [===========================>..] - ETA: 0s - loss: -134.4742 - accuracy: 0.2594
Epoch 500: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -134.0553 - accuracy: 0.2617 - val_loss: -120.8524 - val_accuracy: 0.2609
Epoch 501/830
20/21 [===========================>..] - ETA: 0s - loss: -134.2675 - accuracy: 0.2609
Epoch 501: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -134.3219 - accuracy: 0.2617 - val_loss: -121.1063 - val_accuracy: 0.2609
Epoch 502/830
20/21 [===========================>..] - ETA: 0s - loss: -135.2980 - accuracy: 0.2609
Epoch 502: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -134.6056 - accuracy: 0.2617 - val_loss: -121.3400 - val_accuracy: 0.2609
Epoch 503/830
20/21 [===========================>..] - ETA: 0s - loss: -135.6053 - accuracy: 0.2609
Epoch 503: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -134.8615 - accuracy: 0.2617 - val_loss: -121.5706 - val_accuracy: 0.2609
Epoch 504/830
20/21 [===========================>..] - ETA: 0s - loss: -134.8329 - accuracy: 0.2609
Epoch 504: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -135.1161 - accuracy: 0.2617 - val_loss: -121.8234 - val_accuracy: 0.2609
Epoch 505/830
20/21 [===========================>..] - ETA: 0s - loss: -134.9841 - accuracy: 0.2625
Epoch 505: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -135.3952 - accuracy: 0.2617 - val_loss: -122.0752 - val_accuracy: 0.2609
Epoch 506/830
20/21 [===========================>..] - ETA: 0s - loss: -136.5336 - accuracy: 0.2609
Epoch 506: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -135.6735 - accuracy: 0.2617 - val_loss: -122.2902 - val_accuracy: 0.2609
Epoch 507/830
20/21 [===========================>..] - ETA: 0s - loss: -135.4271 - accuracy: 0.2609
Epoch 507: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -135.9140 - accuracy: 0.2617 - val_loss: -122.5454 - val_accuracy: 0.2609
Epoch 508/830
20/21 [===========================>..] - ETA: 0s - loss: -135.8339 - accuracy: 0.2609
Epoch 508: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -136.1964 - accuracy: 0.2617 - val_loss: -122.7926 - val_accuracy: 0.2609
Epoch 509/830
20/21 [===========================>..] - ETA: 0s - loss: -137.3542 - accuracy: 0.2609
Epoch 509: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -136.4757 - accuracy: 0.2617 - val_loss: -123.0207 - val_accuracy: 0.2609
Epoch 510/830
20/21 [===========================>..] - ETA: 0s - loss: -136.2791 - accuracy: 0.2609
Epoch 510: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -136.7233 - accuracy: 0.2617 - val_loss: -123.2685 - val_accuracy: 0.2609
Epoch 511/830
20/21 [===========================>..] - ETA: 0s - loss: -137.4363 - accuracy: 0.2594
Epoch 511: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -137.0082 - accuracy: 0.2617 - val_loss: -123.5068 - val_accuracy: 0.2609
Epoch 512/830
20/21 [===========================>..] - ETA: 0s - loss: -137.6958 - accuracy: 0.2594
Epoch 512: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -137.2668 - accuracy: 0.2617 - val_loss: -123.7416 - val_accuracy: 0.2609
Epoch 513/830
20/21 [===========================>..] - ETA: 0s - loss: -136.9786 - accuracy: 0.2609
Epoch 513: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -137.5475 - accuracy: 0.2617 - val_loss: -124.0215 - val_accuracy: 0.2609
Epoch 514/830
20/21 [===========================>..] - ETA: 0s - loss: -137.5666 - accuracy: 0.2609
Epoch 514: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -137.8403 - accuracy: 0.2617 - val_loss: -124.2661 - val_accuracy: 0.2609
Epoch 515/830
20/21 [===========================>..] - ETA: 0s - loss: -137.7267 - accuracy: 0.2609
Epoch 515: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -138.1129 - accuracy: 0.2617 - val_loss: -124.5170 - val_accuracy: 0.2609
Epoch 516/830
20/21 [===========================>..] - ETA: 0s - loss: -138.3293 - accuracy: 0.2609
Epoch 516: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -138.3944 - accuracy: 0.2617 - val_loss: -124.7635 - val_accuracy: 0.2609
Epoch 517/830
20/21 [===========================>..] - ETA: 0s - loss: -138.2124 - accuracy: 0.2609
Epoch 517: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -138.6683 - accuracy: 0.2617 - val_loss: -125.0149 - val_accuracy: 0.2609
Epoch 518/830
20/21 [===========================>..] - ETA: 0s - loss: -137.5630 - accuracy: 0.2625
Epoch 518: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -138.9442 - accuracy: 0.2617 - val_loss: -125.2743 - val_accuracy: 0.2609
Epoch 519/830
20/21 [===========================>..] - ETA: 0s - loss: -139.1834 - accuracy: 0.2609
Epoch 519: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -139.2114 - accuracy: 0.2617 - val_loss: -125.4820 - val_accuracy: 0.2609
Epoch 520/830
20/21 [===========================>..] - ETA: 0s - loss: -140.2475 - accuracy: 0.2609
Epoch 520: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -139.4717 - accuracy: 0.2617 - val_loss: -125.7127 - val_accuracy: 0.2609
Epoch 521/830
20/21 [===========================>..] - ETA: 0s - loss: -138.9416 - accuracy: 0.2625
Epoch 521: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -139.7258 - accuracy: 0.2617 - val_loss: -125.9730 - val_accuracy: 0.2609
Epoch 522/830
20/21 [===========================>..] - ETA: 0s - loss: -140.5076 - accuracy: 0.2625
Epoch 522: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -140.0072 - accuracy: 0.2617 - val_loss: -126.1989 - val_accuracy: 0.2609
Epoch 523/830
20/21 [===========================>..] - ETA: 0s - loss: -141.1285 - accuracy: 0.2609
Epoch 523: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -140.2586 - accuracy: 0.2617 - val_loss: -126.4199 - val_accuracy: 0.2609
Epoch 524/830
20/21 [===========================>..] - ETA: 0s - loss: -140.7253 - accuracy: 0.2625
Epoch 524: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -140.5097 - accuracy: 0.2617 - val_loss: -126.6614 - val_accuracy: 0.2609
Epoch 525/830
20/21 [===========================>..] - ETA: 0s - loss: -141.6138 - accuracy: 0.2609
Epoch 525: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -140.7779 - accuracy: 0.2617 - val_loss: -126.8932 - val_accuracy: 0.2609
Epoch 526/830
20/21 [===========================>..] - ETA: 0s - loss: -140.6001 - accuracy: 0.2609
Epoch 526: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -141.0339 - accuracy: 0.2617 - val_loss: -127.1479 - val_accuracy: 0.2609
Epoch 527/830
20/21 [===========================>..] - ETA: 0s - loss: -142.1191 - accuracy: 0.2609
Epoch 527: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -141.3100 - accuracy: 0.2617 - val_loss: -127.3637 - val_accuracy: 0.2609
Epoch 528/830
20/21 [===========================>..] - ETA: 0s - loss: -142.0019 - accuracy: 0.2594
Epoch 528: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -141.5595 - accuracy: 0.2617 - val_loss: -127.6088 - val_accuracy: 0.2609
Epoch 529/830
20/21 [===========================>..] - ETA: 0s - loss: -140.3768 - accuracy: 0.2625
Epoch 529: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -141.8396 - accuracy: 0.2617 - val_loss: -127.8915 - val_accuracy: 0.2609
Epoch 530/830
20/21 [===========================>..] - ETA: 0s - loss: -142.9775 - accuracy: 0.2609
Epoch 530: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -142.1237 - accuracy: 0.2617 - val_loss: -128.0874 - val_accuracy: 0.2609
Epoch 531/830
20/21 [===========================>..] - ETA: 0s - loss: -142.1219 - accuracy: 0.2609
Epoch 531: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -142.3562 - accuracy: 0.2617 - val_loss: -128.3350 - val_accuracy: 0.2609
Epoch 532/830
20/21 [===========================>..] - ETA: 0s - loss: -142.8619 - accuracy: 0.2625
Epoch 532: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -142.6327 - accuracy: 0.2617 - val_loss: -128.5735 - val_accuracy: 0.2609
Epoch 533/830
20/21 [===========================>..] - ETA: 0s - loss: -141.9983 - accuracy: 0.2625
Epoch 533: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -142.8985 - accuracy: 0.2617 - val_loss: -128.8311 - val_accuracy: 0.2609
Epoch 534/830
20/21 [===========================>..] - ETA: 0s - loss: -144.3882 - accuracy: 0.2625
Epoch 534: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -143.1724 - accuracy: 0.2617 - val_loss: -129.0330 - val_accuracy: 0.2609
Epoch 535/830
20/21 [===========================>..] - ETA: 0s - loss: -143.2160 - accuracy: 0.2625
Epoch 535: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -143.4056 - accuracy: 0.2617 - val_loss: -129.2778 - val_accuracy: 0.2609
Epoch 536/830
20/21 [===========================>..] - ETA: 0s - loss: -143.7516 - accuracy: 0.2609
Epoch 536: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -143.6831 - accuracy: 0.2617 - val_loss: -129.5261 - val_accuracy: 0.2609
Epoch 537/830
20/21 [===========================>..] - ETA: 0s - loss: -142.9238 - accuracy: 0.2625
Epoch 537: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -143.9635 - accuracy: 0.2617 - val_loss: -129.7975 - val_accuracy: 0.2609
Epoch 538/830
20/21 [===========================>..] - ETA: 0s - loss: -143.0390 - accuracy: 0.2625
Epoch 538: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -144.2451 - accuracy: 0.2617 - val_loss: -130.0391 - val_accuracy: 0.2609
Epoch 539/830
20/21 [===========================>..] - ETA: 0s - loss: -145.9566 - accuracy: 0.2625
Epoch 539: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -144.5100 - accuracy: 0.2617 - val_loss: -130.2311 - val_accuracy: 0.2609
Epoch 540/830
20/21 [===========================>..] - ETA: 0s - loss: -144.7186 - accuracy: 0.2625
Epoch 540: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -144.7317 - accuracy: 0.2617 - val_loss: -130.4678 - val_accuracy: 0.2609
Epoch 541/830
20/21 [===========================>..] - ETA: 0s - loss: -145.2860 - accuracy: 0.2625
Epoch 541: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -145.0002 - accuracy: 0.2617 - val_loss: -130.7054 - val_accuracy: 0.2609
Epoch 542/830
20/21 [===========================>..] - ETA: 0s - loss: -145.0749 - accuracy: 0.2609
Epoch 542: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -145.2633 - accuracy: 0.2617 - val_loss: -130.9529 - val_accuracy: 0.2609
Epoch 543/830
20/21 [===========================>..] - ETA: 0s - loss: -145.1827 - accuracy: 0.2625
Epoch 543: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -145.5458 - accuracy: 0.2617 - val_loss: -131.2116 - val_accuracy: 0.2609
Epoch 544/830
20/21 [===========================>..] - ETA: 0s - loss: -145.3077 - accuracy: 0.2609
Epoch 544: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -145.8296 - accuracy: 0.2617 - val_loss: -131.4624 - val_accuracy: 0.2609
Epoch 545/830
20/21 [===========================>..] - ETA: 0s - loss: -146.4745 - accuracy: 0.2625
Epoch 545: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -146.0974 - accuracy: 0.2617 - val_loss: -131.6869 - val_accuracy: 0.2609
Epoch 546/830
20/21 [===========================>..] - ETA: 0s - loss: -147.1754 - accuracy: 0.2609
Epoch 546: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -146.3663 - accuracy: 0.2617 - val_loss: -131.9255 - val_accuracy: 0.2609
Epoch 547/830
20/21 [===========================>..] - ETA: 0s - loss: -145.5377 - accuracy: 0.2625
Epoch 547: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -146.6250 - accuracy: 0.2617 - val_loss: -132.1956 - val_accuracy: 0.2609
Epoch 548/830
20/21 [===========================>..] - ETA: 0s - loss: -147.3175 - accuracy: 0.2625
Epoch 548: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 191ms/step - loss: -146.9114 - accuracy: 0.2617 - val_loss: -132.4159 - val_accuracy: 0.2609
Epoch 549/830
20/21 [===========================>..] - ETA: 0s - loss: -147.1620 - accuracy: 0.2609
Epoch 549: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -147.1669 - accuracy: 0.2617 - val_loss: -132.6646 - val_accuracy: 0.2609
Epoch 550/830
20/21 [===========================>..] - ETA: 0s - loss: -147.1633 - accuracy: 0.2625
Epoch 550: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -147.4532 - accuracy: 0.2617 - val_loss: -132.9328 - val_accuracy: 0.2609
Epoch 551/830
20/21 [===========================>..] - ETA: 0s - loss: -148.7299 - accuracy: 0.2609
Epoch 551: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -147.7341 - accuracy: 0.2617 - val_loss: -133.1508 - val_accuracy: 0.2609
Epoch 552/830
20/21 [===========================>..] - ETA: 0s - loss: -147.4486 - accuracy: 0.2609
Epoch 552: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -147.9882 - accuracy: 0.2617 - val_loss: -133.4159 - val_accuracy: 0.2609
Epoch 553/830
20/21 [===========================>..] - ETA: 0s - loss: -147.9299 - accuracy: 0.2609
Epoch 553: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -148.2742 - accuracy: 0.2617 - val_loss: -133.6623 - val_accuracy: 0.2609
Epoch 554/830
20/21 [===========================>..] - ETA: 0s - loss: -148.5990 - accuracy: 0.2609
Epoch 554: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -148.5480 - accuracy: 0.2617 - val_loss: -133.9069 - val_accuracy: 0.2609
Epoch 555/830
20/21 [===========================>..] - ETA: 0s - loss: -148.2544 - accuracy: 0.2625
Epoch 555: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -148.8221 - accuracy: 0.2617 - val_loss: -134.1656 - val_accuracy: 0.2609
Epoch 556/830
20/21 [===========================>..] - ETA: 0s - loss: -148.3678 - accuracy: 0.2625
Epoch 556: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -149.1033 - accuracy: 0.2617 - val_loss: -134.4167 - val_accuracy: 0.2609
Epoch 557/830
20/21 [===========================>..] - ETA: 0s - loss: -149.0130 - accuracy: 0.2625
Epoch 557: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -149.3818 - accuracy: 0.2617 - val_loss: -134.6598 - val_accuracy: 0.2609
Epoch 558/830
20/21 [===========================>..] - ETA: 0s - loss: -149.3167 - accuracy: 0.2625
Epoch 558: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -149.6510 - accuracy: 0.2617 - val_loss: -134.9026 - val_accuracy: 0.2609
Epoch 559/830
20/21 [===========================>..] - ETA: 0s - loss: -150.6925 - accuracy: 0.2609
Epoch 559: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -149.9341 - accuracy: 0.2617 - val_loss: -135.1383 - val_accuracy: 0.2609
Epoch 560/830
20/21 [===========================>..] - ETA: 0s - loss: -150.2993 - accuracy: 0.2625
Epoch 560: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -150.1937 - accuracy: 0.2617 - val_loss: -135.3861 - val_accuracy: 0.2609
Epoch 561/830
20/21 [===========================>..] - ETA: 0s - loss: -151.4367 - accuracy: 0.2609
Epoch 561: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -150.4682 - accuracy: 0.2617 - val_loss: -135.6089 - val_accuracy: 0.2609
Epoch 562/830
20/21 [===========================>..] - ETA: 0s - loss: -149.1975 - accuracy: 0.2625
Epoch 562: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -150.7211 - accuracy: 0.2617 - val_loss: -135.8813 - val_accuracy: 0.2609
Epoch 563/830
20/21 [===========================>..] - ETA: 0s - loss: -151.4706 - accuracy: 0.2594
Epoch 563: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -150.9987 - accuracy: 0.2617 - val_loss: -136.0826 - val_accuracy: 0.2609
Epoch 564/830
20/21 [===========================>..] - ETA: 0s - loss: -149.9904 - accuracy: 0.2625
Epoch 564: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -151.2515 - accuracy: 0.2617 - val_loss: -136.3532 - val_accuracy: 0.2609
Epoch 565/830
20/21 [===========================>..] - ETA: 0s - loss: -150.3776 - accuracy: 0.2625
Epoch 565: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -151.5242 - accuracy: 0.2617 - val_loss: -136.5795 - val_accuracy: 0.2609
Epoch 566/830
20/21 [===========================>..] - ETA: 0s - loss: -151.3785 - accuracy: 0.2609
Epoch 566: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -151.7775 - accuracy: 0.2617 - val_loss: -136.8025 - val_accuracy: 0.2609
Epoch 567/830
21/21 [==============================] - ETA: 0s - loss: -152.0390 - accuracy: 0.2617
Epoch 567: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -152.0390 - accuracy: 0.2617 - val_loss: -137.0249 - val_accuracy: 0.2609
Epoch 568/830
20/21 [===========================>..] - ETA: 0s - loss: -151.5503 - accuracy: 0.2625
Epoch 568: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -152.2933 - accuracy: 0.2617 - val_loss: -137.2866 - val_accuracy: 0.2609
Epoch 569/830
20/21 [===========================>..] - ETA: 0s - loss: -152.0163 - accuracy: 0.2609
Epoch 569: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -152.5725 - accuracy: 0.2617 - val_loss: -137.5312 - val_accuracy: 0.2609
Epoch 570/830
20/21 [===========================>..] - ETA: 0s - loss: -153.2523 - accuracy: 0.2625
Epoch 570: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -152.8470 - accuracy: 0.2617 - val_loss: -137.7615 - val_accuracy: 0.2609
Epoch 571/830
20/21 [===========================>..] - ETA: 0s - loss: -153.8981 - accuracy: 0.2609
Epoch 571: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -153.1104 - accuracy: 0.2617 - val_loss: -137.9916 - val_accuracy: 0.2609
Epoch 572/830
20/21 [===========================>..] - ETA: 0s - loss: -152.7391 - accuracy: 0.2625
Epoch 572: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -153.3681 - accuracy: 0.2617 - val_loss: -138.2542 - val_accuracy: 0.2609
Epoch 573/830
20/21 [===========================>..] - ETA: 0s - loss: -154.1281 - accuracy: 0.2594
Epoch 573: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -153.6480 - accuracy: 0.2617 - val_loss: -138.4845 - val_accuracy: 0.2609
Epoch 574/830
20/21 [===========================>..] - ETA: 0s - loss: -153.6429 - accuracy: 0.2625
Epoch 574: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -153.9106 - accuracy: 0.2617 - val_loss: -138.7360 - val_accuracy: 0.2609
Epoch 575/830
20/21 [===========================>..] - ETA: 0s - loss: -153.1773 - accuracy: 0.2625
Epoch 575: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -154.1855 - accuracy: 0.2617 - val_loss: -138.9904 - val_accuracy: 0.2609
Epoch 576/830
20/21 [===========================>..] - ETA: 0s - loss: -155.0594 - accuracy: 0.2625
Epoch 576: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -154.4582 - accuracy: 0.2617 - val_loss: -139.2060 - val_accuracy: 0.2609
Epoch 577/830
20/21 [===========================>..] - ETA: 0s - loss: -156.1743 - accuracy: 0.2625
Epoch 577: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -154.7159 - accuracy: 0.2617 - val_loss: -139.4324 - val_accuracy: 0.2609
Epoch 578/830
20/21 [===========================>..] - ETA: 0s - loss: -153.8607 - accuracy: 0.2625
Epoch 578: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -154.9557 - accuracy: 0.2617 - val_loss: -139.6853 - val_accuracy: 0.2609
Epoch 579/830
20/21 [===========================>..] - ETA: 0s - loss: -154.9720 - accuracy: 0.2609
Epoch 579: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -155.2216 - accuracy: 0.2617 - val_loss: -139.9074 - val_accuracy: 0.2609
Epoch 580/830
20/21 [===========================>..] - ETA: 0s - loss: -154.5453 - accuracy: 0.2625
Epoch 580: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -155.4877 - accuracy: 0.2617 - val_loss: -140.1602 - val_accuracy: 0.2609
Epoch 581/830
20/21 [===========================>..] - ETA: 0s - loss: -156.0501 - accuracy: 0.2625
Epoch 581: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -155.7542 - accuracy: 0.2617 - val_loss: -140.3810 - val_accuracy: 0.2609
Epoch 582/830
20/21 [===========================>..] - ETA: 0s - loss: -156.9313 - accuracy: 0.2609
Epoch 582: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -156.0143 - accuracy: 0.2617 - val_loss: -140.6108 - val_accuracy: 0.2609
Epoch 583/830
20/21 [===========================>..] - ETA: 0s - loss: -157.0485 - accuracy: 0.2609
Epoch 583: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -156.2641 - accuracy: 0.2617 - val_loss: -140.8359 - val_accuracy: 0.2609
Epoch 584/830
20/21 [===========================>..] - ETA: 0s - loss: -156.4903 - accuracy: 0.2609
Epoch 584: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -156.5206 - accuracy: 0.2617 - val_loss: -141.0871 - val_accuracy: 0.2609
Epoch 585/830
20/21 [===========================>..] - ETA: 0s - loss: -157.1629 - accuracy: 0.2625
Epoch 585: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -156.8100 - accuracy: 0.2617 - val_loss: -141.3413 - val_accuracy: 0.2609
Epoch 586/830
20/21 [===========================>..] - ETA: 0s - loss: -157.0545 - accuracy: 0.2625
Epoch 586: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -157.0890 - accuracy: 0.2617 - val_loss: -141.5982 - val_accuracy: 0.2609
Epoch 587/830
20/21 [===========================>..] - ETA: 0s - loss: -157.4165 - accuracy: 0.2609
Epoch 587: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -157.3636 - accuracy: 0.2617 - val_loss: -141.8383 - val_accuracy: 0.2609
Epoch 588/830
20/21 [===========================>..] - ETA: 0s - loss: -157.5856 - accuracy: 0.2609
Epoch 588: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -157.6359 - accuracy: 0.2617 - val_loss: -142.0886 - val_accuracy: 0.2609
Epoch 589/830
20/21 [===========================>..] - ETA: 0s - loss: -157.8699 - accuracy: 0.2609
Epoch 589: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -157.9209 - accuracy: 0.2617 - val_loss: -142.3469 - val_accuracy: 0.2609
Epoch 590/830
20/21 [===========================>..] - ETA: 0s - loss: -158.1003 - accuracy: 0.2609
Epoch 590: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -158.2043 - accuracy: 0.2617 - val_loss: -142.6013 - val_accuracy: 0.2609
Epoch 591/830
20/21 [===========================>..] - ETA: 0s - loss: -158.1342 - accuracy: 0.2625
Epoch 591: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -158.4917 - accuracy: 0.2617 - val_loss: -142.8679 - val_accuracy: 0.2609
Epoch 592/830
20/21 [===========================>..] - ETA: 0s - loss: -159.2863 - accuracy: 0.2625
Epoch 592: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -158.7820 - accuracy: 0.2617 - val_loss: -143.1075 - val_accuracy: 0.2609
Epoch 593/830
20/21 [===========================>..] - ETA: 0s - loss: -158.4424 - accuracy: 0.2609
Epoch 593: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -159.0462 - accuracy: 0.2617 - val_loss: -143.3643 - val_accuracy: 0.2609
Epoch 594/830
20/21 [===========================>..] - ETA: 0s - loss: -158.7932 - accuracy: 0.2609
Epoch 594: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -159.3278 - accuracy: 0.2617 - val_loss: -143.6107 - val_accuracy: 0.2609
Epoch 595/830
20/21 [===========================>..] - ETA: 0s - loss: -159.3637 - accuracy: 0.2609
Epoch 595: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -159.5941 - accuracy: 0.2617 - val_loss: -143.8498 - val_accuracy: 0.2609
Epoch 596/830
20/21 [===========================>..] - ETA: 0s - loss: -159.5463 - accuracy: 0.2609
Epoch 596: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -159.8718 - accuracy: 0.2617 - val_loss: -144.1012 - val_accuracy: 0.2609
Epoch 597/830
20/21 [===========================>..] - ETA: 0s - loss: -160.1195 - accuracy: 0.2625
Epoch 597: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -160.1489 - accuracy: 0.2617 - val_loss: -144.3396 - val_accuracy: 0.2609
Epoch 598/830
20/21 [===========================>..] - ETA: 0s - loss: -160.9073 - accuracy: 0.2594
Epoch 598: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -160.4061 - accuracy: 0.2617 - val_loss: -144.5629 - val_accuracy: 0.2609
Epoch 599/830
20/21 [===========================>..] - ETA: 0s - loss: -161.7416 - accuracy: 0.2609
Epoch 599: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -160.6689 - accuracy: 0.2617 - val_loss: -144.7965 - val_accuracy: 0.2609
Epoch 600/830
20/21 [===========================>..] - ETA: 0s - loss: -159.1810 - accuracy: 0.2625
Epoch 600: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -160.9275 - accuracy: 0.2617 - val_loss: -145.0679 - val_accuracy: 0.2609
Epoch 601/830
20/21 [===========================>..] - ETA: 0s - loss: -160.6210 - accuracy: 0.2609
Epoch 601: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -161.1997 - accuracy: 0.2617 - val_loss: -145.2832 - val_accuracy: 0.2609
Epoch 602/830
20/21 [===========================>..] - ETA: 0s - loss: -160.7765 - accuracy: 0.2625
Epoch 602: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -161.4550 - accuracy: 0.2617 - val_loss: -145.5287 - val_accuracy: 0.2609
Epoch 603/830
20/21 [===========================>..] - ETA: 0s - loss: -161.8018 - accuracy: 0.2625
Epoch 603: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -161.7331 - accuracy: 0.2617 - val_loss: -145.7674 - val_accuracy: 0.2609
Epoch 604/830
20/21 [===========================>..] - ETA: 0s - loss: -160.7020 - accuracy: 0.2625
Epoch 604: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -161.9988 - accuracy: 0.2617 - val_loss: -146.0256 - val_accuracy: 0.2609
Epoch 605/830
20/21 [===========================>..] - ETA: 0s - loss: -163.6214 - accuracy: 0.2625
Epoch 605: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -162.2672 - accuracy: 0.2617 - val_loss: -146.2183 - val_accuracy: 0.2609
Epoch 606/830
20/21 [===========================>..] - ETA: 0s - loss: -163.1929 - accuracy: 0.2625
Epoch 606: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -162.4958 - accuracy: 0.2617 - val_loss: -146.4418 - val_accuracy: 0.2609
Epoch 607/830
20/21 [===========================>..] - ETA: 0s - loss: -162.8114 - accuracy: 0.2609
Epoch 607: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -162.7562 - accuracy: 0.2617 - val_loss: -146.6948 - val_accuracy: 0.2609
Epoch 608/830
20/21 [===========================>..] - ETA: 0s - loss: -163.4627 - accuracy: 0.2625
Epoch 608: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -163.0308 - accuracy: 0.2617 - val_loss: -146.9352 - val_accuracy: 0.2609
Epoch 609/830
20/21 [===========================>..] - ETA: 0s - loss: -163.7747 - accuracy: 0.2625
Epoch 609: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -163.3044 - accuracy: 0.2617 - val_loss: -147.1860 - val_accuracy: 0.2609
Epoch 610/830
20/21 [===========================>..] - ETA: 0s - loss: -164.3624 - accuracy: 0.2609
Epoch 610: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -163.5837 - accuracy: 0.2617 - val_loss: -147.4269 - val_accuracy: 0.2609
Epoch 611/830
20/21 [===========================>..] - ETA: 0s - loss: -165.1013 - accuracy: 0.2625
Epoch 611: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -163.8455 - accuracy: 0.2617 - val_loss: -147.6516 - val_accuracy: 0.2609
Epoch 612/830
20/21 [===========================>..] - ETA: 0s - loss: -164.3489 - accuracy: 0.2625
Epoch 612: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -164.0864 - accuracy: 0.2617 - val_loss: -147.8914 - val_accuracy: 0.2609
Epoch 613/830
20/21 [===========================>..] - ETA: 0s - loss: -162.8022 - accuracy: 0.2625
Epoch 613: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -164.3644 - accuracy: 0.2617 - val_loss: -148.1665 - val_accuracy: 0.2609
Epoch 614/830
20/21 [===========================>..] - ETA: 0s - loss: -165.1540 - accuracy: 0.2594
Epoch 614: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -164.6395 - accuracy: 0.2617 - val_loss: -148.3710 - val_accuracy: 0.2609
Epoch 615/830
20/21 [===========================>..] - ETA: 0s - loss: -164.3145 - accuracy: 0.2609
Epoch 615: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -164.8880 - accuracy: 0.2617 - val_loss: -148.6304 - val_accuracy: 0.2609
Epoch 616/830
20/21 [===========================>..] - ETA: 0s - loss: -164.6494 - accuracy: 0.2625
Epoch 616: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -165.1725 - accuracy: 0.2617 - val_loss: -148.8793 - val_accuracy: 0.2609
Epoch 617/830
20/21 [===========================>..] - ETA: 0s - loss: -164.9902 - accuracy: 0.2609
Epoch 617: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -165.4424 - accuracy: 0.2617 - val_loss: -149.1178 - val_accuracy: 0.2609
Epoch 618/830
20/21 [===========================>..] - ETA: 0s - loss: -164.6732 - accuracy: 0.2625
Epoch 618: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -165.7159 - accuracy: 0.2617 - val_loss: -149.3766 - val_accuracy: 0.2609
Epoch 619/830
20/21 [===========================>..] - ETA: 0s - loss: -164.5129 - accuracy: 0.2625
Epoch 619: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -165.9947 - accuracy: 0.2617 - val_loss: -149.6260 - val_accuracy: 0.2609
Epoch 620/830
20/21 [===========================>..] - ETA: 0s - loss: -166.2912 - accuracy: 0.2609
Epoch 620: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -166.2645 - accuracy: 0.2617 - val_loss: -149.8427 - val_accuracy: 0.2609
Epoch 621/830
20/21 [===========================>..] - ETA: 0s - loss: -166.5401 - accuracy: 0.2609
Epoch 621: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -166.5256 - accuracy: 0.2617 - val_loss: -150.0927 - val_accuracy: 0.2609
Epoch 622/830
20/21 [===========================>..] - ETA: 0s - loss: -166.4296 - accuracy: 0.2609
Epoch 622: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -166.8012 - accuracy: 0.2617 - val_loss: -150.3445 - val_accuracy: 0.2609
Epoch 623/830
20/21 [===========================>..] - ETA: 0s - loss: -167.7056 - accuracy: 0.2625
Epoch 623: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -167.0788 - accuracy: 0.2617 - val_loss: -150.5774 - val_accuracy: 0.2609
Epoch 624/830
20/21 [===========================>..] - ETA: 0s - loss: -165.7682 - accuracy: 0.2625
Epoch 624: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -167.3434 - accuracy: 0.2617 - val_loss: -150.8464 - val_accuracy: 0.2609
Epoch 625/830
20/21 [===========================>..] - ETA: 0s - loss: -167.7523 - accuracy: 0.2609
Epoch 625: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -167.6203 - accuracy: 0.2617 - val_loss: -151.0619 - val_accuracy: 0.2609
Epoch 626/830
20/21 [===========================>..] - ETA: 0s - loss: -167.4469 - accuracy: 0.2609
Epoch 626: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -167.8849 - accuracy: 0.2617 - val_loss: -151.3228 - val_accuracy: 0.2609
Epoch 627/830
20/21 [===========================>..] - ETA: 0s - loss: -168.6192 - accuracy: 0.2625
Epoch 627: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -168.1691 - accuracy: 0.2617 - val_loss: -151.5591 - val_accuracy: 0.2609
Epoch 628/830
20/21 [===========================>..] - ETA: 0s - loss: -167.9232 - accuracy: 0.2609
Epoch 628: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -168.4354 - accuracy: 0.2617 - val_loss: -151.8151 - val_accuracy: 0.2609
Epoch 629/830
20/21 [===========================>..] - ETA: 0s - loss: -169.2665 - accuracy: 0.2625
Epoch 629: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -168.7149 - accuracy: 0.2617 - val_loss: -152.0448 - val_accuracy: 0.2609
Epoch 630/830
20/21 [===========================>..] - ETA: 0s - loss: -169.2887 - accuracy: 0.2625
Epoch 630: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -168.9846 - accuracy: 0.2617 - val_loss: -152.2955 - val_accuracy: 0.2609
Epoch 631/830
20/21 [===========================>..] - ETA: 0s - loss: -168.0519 - accuracy: 0.2625
Epoch 631: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -169.2592 - accuracy: 0.2617 - val_loss: -152.5607 - val_accuracy: 0.2609
Epoch 632/830
20/21 [===========================>..] - ETA: 0s - loss: -169.1443 - accuracy: 0.2625
Epoch 632: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -169.5398 - accuracy: 0.2617 - val_loss: -152.7969 - val_accuracy: 0.2609
Epoch 633/830
20/21 [===========================>..] - ETA: 0s - loss: -170.0053 - accuracy: 0.2625
Epoch 633: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -169.8012 - accuracy: 0.2617 - val_loss: -153.0269 - val_accuracy: 0.2609
Epoch 634/830
20/21 [===========================>..] - ETA: 0s - loss: -168.6914 - accuracy: 0.2625
Epoch 634: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -170.0619 - accuracy: 0.2617 - val_loss: -153.2836 - val_accuracy: 0.2609
Epoch 635/830
20/21 [===========================>..] - ETA: 0s - loss: -169.5268 - accuracy: 0.2625
Epoch 635: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -170.3331 - accuracy: 0.2617 - val_loss: -153.5170 - val_accuracy: 0.2609
Epoch 636/830
20/21 [===========================>..] - ETA: 0s - loss: -170.4298 - accuracy: 0.2609
Epoch 636: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -170.5992 - accuracy: 0.2617 - val_loss: -153.7538 - val_accuracy: 0.2609
Epoch 637/830
20/21 [===========================>..] - ETA: 0s - loss: -169.8022 - accuracy: 0.2625
Epoch 637: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -170.8714 - accuracy: 0.2617 - val_loss: -154.0132 - val_accuracy: 0.2609
Epoch 638/830
20/21 [===========================>..] - ETA: 0s - loss: -170.6990 - accuracy: 0.2609
Epoch 638: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -171.1488 - accuracy: 0.2617 - val_loss: -154.2493 - val_accuracy: 0.2609
Epoch 639/830
20/21 [===========================>..] - ETA: 0s - loss: -172.1678 - accuracy: 0.2625
Epoch 639: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -171.4209 - accuracy: 0.2617 - val_loss: -154.4768 - val_accuracy: 0.2609
Epoch 640/830
20/21 [===========================>..] - ETA: 0s - loss: -171.3170 - accuracy: 0.2609
Epoch 640: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -171.6845 - accuracy: 0.2617 - val_loss: -154.7409 - val_accuracy: 0.2609
Epoch 641/830
20/21 [===========================>..] - ETA: 0s - loss: -171.3061 - accuracy: 0.2625
Epoch 641: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 187ms/step - loss: -171.9733 - accuracy: 0.2617 - val_loss: -154.9987 - val_accuracy: 0.2609
Epoch 642/830
20/21 [===========================>..] - ETA: 0s - loss: -171.9367 - accuracy: 0.2609
Epoch 642: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -172.2511 - accuracy: 0.2617 - val_loss: -155.2393 - val_accuracy: 0.2609
Epoch 643/830
20/21 [===========================>..] - ETA: 0s - loss: -172.0741 - accuracy: 0.2625
Epoch 643: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -172.5249 - accuracy: 0.2617 - val_loss: -155.4907 - val_accuracy: 0.2609
Epoch 644/830
20/21 [===========================>..] - ETA: 0s - loss: -173.9261 - accuracy: 0.2609
Epoch 644: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -172.8013 - accuracy: 0.2617 - val_loss: -155.7075 - val_accuracy: 0.2609
Epoch 645/830
20/21 [===========================>..] - ETA: 0s - loss: -173.4093 - accuracy: 0.2625
Epoch 645: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -173.0524 - accuracy: 0.2617 - val_loss: -155.9544 - val_accuracy: 0.2609
Epoch 646/830
20/21 [===========================>..] - ETA: 0s - loss: -174.7727 - accuracy: 0.2625
Epoch 646: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -173.3253 - accuracy: 0.2617 - val_loss: -156.1804 - val_accuracy: 0.2609
Epoch 647/830
20/21 [===========================>..] - ETA: 0s - loss: -172.0727 - accuracy: 0.2625
Epoch 647: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -173.5701 - accuracy: 0.2617 - val_loss: -156.4412 - val_accuracy: 0.2609
Epoch 648/830
20/21 [===========================>..] - ETA: 0s - loss: -174.3722 - accuracy: 0.2625
Epoch 648: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -173.8437 - accuracy: 0.2617 - val_loss: -156.6485 - val_accuracy: 0.2609
Epoch 649/830
20/21 [===========================>..] - ETA: 0s - loss: -175.5454 - accuracy: 0.2625
Epoch 649: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -174.0989 - accuracy: 0.2617 - val_loss: -156.8772 - val_accuracy: 0.2609
Epoch 650/830
20/21 [===========================>..] - ETA: 0s - loss: -175.5157 - accuracy: 0.2609
Epoch 650: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -174.3410 - accuracy: 0.2617 - val_loss: -157.0937 - val_accuracy: 0.2609
Epoch 651/830
20/21 [===========================>..] - ETA: 0s - loss: -174.2895 - accuracy: 0.2625
Epoch 651: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -174.5918 - accuracy: 0.2617 - val_loss: -157.3489 - val_accuracy: 0.2609
Epoch 652/830
20/21 [===========================>..] - ETA: 0s - loss: -175.8537 - accuracy: 0.2609
Epoch 652: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -174.8649 - accuracy: 0.2617 - val_loss: -157.5687 - val_accuracy: 0.2609
Epoch 653/830
20/21 [===========================>..] - ETA: 0s - loss: -173.6102 - accuracy: 0.2625
Epoch 653: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -175.1128 - accuracy: 0.2617 - val_loss: -157.8285 - val_accuracy: 0.2609
Epoch 654/830
20/21 [===========================>..] - ETA: 0s - loss: -176.2911 - accuracy: 0.2609
Epoch 654: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -175.3837 - accuracy: 0.2617 - val_loss: -158.0345 - val_accuracy: 0.2609
Epoch 655/830
20/21 [===========================>..] - ETA: 0s - loss: -174.6301 - accuracy: 0.2625
Epoch 655: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -175.6293 - accuracy: 0.2617 - val_loss: -158.2961 - val_accuracy: 0.2609
Epoch 656/830
20/21 [===========================>..] - ETA: 0s - loss: -175.7328 - accuracy: 0.2609
Epoch 656: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -175.9078 - accuracy: 0.2617 - val_loss: -158.5309 - val_accuracy: 0.2609
Epoch 657/830
20/21 [===========================>..] - ETA: 0s - loss: -176.7326 - accuracy: 0.2594
Epoch 657: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -176.1820 - accuracy: 0.2617 - val_loss: -158.7719 - val_accuracy: 0.2609
Epoch 658/830
20/21 [===========================>..] - ETA: 0s - loss: -177.0111 - accuracy: 0.2594
Epoch 658: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -176.4597 - accuracy: 0.2617 - val_loss: -159.0251 - val_accuracy: 0.2609
Epoch 659/830
20/21 [===========================>..] - ETA: 0s - loss: -175.2441 - accuracy: 0.2625
Epoch 659: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -176.7369 - accuracy: 0.2617 - val_loss: -159.2959 - val_accuracy: 0.2609
Epoch 660/830
20/21 [===========================>..] - ETA: 0s - loss: -177.1822 - accuracy: 0.2625
Epoch 660: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -177.0165 - accuracy: 0.2617 - val_loss: -159.5170 - val_accuracy: 0.2609
Epoch 661/830
20/21 [===========================>..] - ETA: 0s - loss: -178.3487 - accuracy: 0.2609
Epoch 661: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -177.2725 - accuracy: 0.2617 - val_loss: -159.7435 - val_accuracy: 0.2609
Epoch 662/830
20/21 [===========================>..] - ETA: 0s - loss: -178.5407 - accuracy: 0.2609
Epoch 662: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -177.5276 - accuracy: 0.2617 - val_loss: -159.9784 - val_accuracy: 0.2609
Epoch 663/830
20/21 [===========================>..] - ETA: 0s - loss: -178.4662 - accuracy: 0.2625
Epoch 663: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -177.7823 - accuracy: 0.2617 - val_loss: -160.2134 - val_accuracy: 0.2609
Epoch 664/830
20/21 [===========================>..] - ETA: 0s - loss: -178.1174 - accuracy: 0.2625
Epoch 664: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -178.0491 - accuracy: 0.2617 - val_loss: -160.4702 - val_accuracy: 0.2609
Epoch 665/830
20/21 [===========================>..] - ETA: 0s - loss: -179.3483 - accuracy: 0.2609
Epoch 665: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -178.3272 - accuracy: 0.2617 - val_loss: -160.6953 - val_accuracy: 0.2609
Epoch 666/830
20/21 [===========================>..] - ETA: 0s - loss: -178.7206 - accuracy: 0.2625
Epoch 666: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -178.5853 - accuracy: 0.2617 - val_loss: -160.9503 - val_accuracy: 0.2609
Epoch 667/830
20/21 [===========================>..] - ETA: 0s - loss: -178.6678 - accuracy: 0.2625
Epoch 667: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -178.8701 - accuracy: 0.2617 - val_loss: -161.2129 - val_accuracy: 0.2609
Epoch 668/830
20/21 [===========================>..] - ETA: 0s - loss: -178.5742 - accuracy: 0.2609
Epoch 668: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -179.1579 - accuracy: 0.2617 - val_loss: -161.4742 - val_accuracy: 0.2609
Epoch 669/830
20/21 [===========================>..] - ETA: 0s - loss: -180.6819 - accuracy: 0.2625
Epoch 669: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -179.4376 - accuracy: 0.2617 - val_loss: -161.6873 - val_accuracy: 0.2609
Epoch 670/830
20/21 [===========================>..] - ETA: 0s - loss: -181.2469 - accuracy: 0.2625
Epoch 670: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -179.6761 - accuracy: 0.2617 - val_loss: -161.9026 - val_accuracy: 0.2609
Epoch 671/830
20/21 [===========================>..] - ETA: 0s - loss: -179.0209 - accuracy: 0.2609
Epoch 671: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -179.9171 - accuracy: 0.2617 - val_loss: -162.1620 - val_accuracy: 0.2609
Epoch 672/830
20/21 [===========================>..] - ETA: 0s - loss: -180.8151 - accuracy: 0.2625
Epoch 672: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -180.1985 - accuracy: 0.2617 - val_loss: -162.3853 - val_accuracy: 0.2609
Epoch 673/830
20/21 [===========================>..] - ETA: 0s - loss: -179.8184 - accuracy: 0.2609
Epoch 673: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -180.4584 - accuracy: 0.2617 - val_loss: -162.6435 - val_accuracy: 0.2609
Epoch 674/830
20/21 [===========================>..] - ETA: 0s - loss: -181.3045 - accuracy: 0.2594
Epoch 674: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -180.7397 - accuracy: 0.2617 - val_loss: -162.8730 - val_accuracy: 0.2609
Epoch 675/830
20/21 [===========================>..] - ETA: 0s - loss: -181.4336 - accuracy: 0.2625
Epoch 675: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -181.0070 - accuracy: 0.2617 - val_loss: -163.1255 - val_accuracy: 0.2609
Epoch 676/830
20/21 [===========================>..] - ETA: 0s - loss: -180.0542 - accuracy: 0.2625
Epoch 676: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -181.2872 - accuracy: 0.2617 - val_loss: -163.4044 - val_accuracy: 0.2609
Epoch 677/830
20/21 [===========================>..] - ETA: 0s - loss: -181.4305 - accuracy: 0.2625
Epoch 677: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -181.5695 - accuracy: 0.2617 - val_loss: -163.6245 - val_accuracy: 0.2609
Epoch 678/830
20/21 [===========================>..] - ETA: 0s - loss: -182.3527 - accuracy: 0.2625
Epoch 678: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -181.8246 - accuracy: 0.2617 - val_loss: -163.8479 - val_accuracy: 0.2609
Epoch 679/830
20/21 [===========================>..] - ETA: 0s - loss: -182.6543 - accuracy: 0.2594
Epoch 679: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -182.0853 - accuracy: 0.2617 - val_loss: -164.0909 - val_accuracy: 0.2609
Epoch 680/830
20/21 [===========================>..] - ETA: 0s - loss: -182.3290 - accuracy: 0.2609
Epoch 680: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -182.3611 - accuracy: 0.2617 - val_loss: -164.3510 - val_accuracy: 0.2609
Epoch 681/830
20/21 [===========================>..] - ETA: 0s - loss: -184.3686 - accuracy: 0.2625
Epoch 681: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -182.6482 - accuracy: 0.2617 - val_loss: -164.5800 - val_accuracy: 0.2609
Epoch 682/830
20/21 [===========================>..] - ETA: 0s - loss: -182.9892 - accuracy: 0.2625
Epoch 682: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -182.8913 - accuracy: 0.2617 - val_loss: -164.8157 - val_accuracy: 0.2609
Epoch 683/830
20/21 [===========================>..] - ETA: 0s - loss: -182.4146 - accuracy: 0.2609
Epoch 683: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -183.1497 - accuracy: 0.2617 - val_loss: -165.0578 - val_accuracy: 0.2609
Epoch 684/830
20/21 [===========================>..] - ETA: 0s - loss: -182.5217 - accuracy: 0.2625
Epoch 684: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -183.4283 - accuracy: 0.2617 - val_loss: -165.3167 - val_accuracy: 0.2609
Epoch 685/830
20/21 [===========================>..] - ETA: 0s - loss: -182.8819 - accuracy: 0.2625
Epoch 685: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -183.7097 - accuracy: 0.2617 - val_loss: -165.5605 - val_accuracy: 0.2609
Epoch 686/830
20/21 [===========================>..] - ETA: 0s - loss: -183.6100 - accuracy: 0.2609
Epoch 686: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -183.9803 - accuracy: 0.2617 - val_loss: -165.7993 - val_accuracy: 0.2609
Epoch 687/830
20/21 [===========================>..] - ETA: 0s - loss: -184.1345 - accuracy: 0.2609
Epoch 687: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -184.2486 - accuracy: 0.2617 - val_loss: -166.0439 - val_accuracy: 0.2609
Epoch 688/830
20/21 [===========================>..] - ETA: 0s - loss: -182.7502 - accuracy: 0.2625
Epoch 688: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -184.5294 - accuracy: 0.2617 - val_loss: -166.3139 - val_accuracy: 0.2609
Epoch 689/830
20/21 [===========================>..] - ETA: 0s - loss: -185.2090 - accuracy: 0.2625
Epoch 689: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -184.8007 - accuracy: 0.2617 - val_loss: -166.5152 - val_accuracy: 0.2609
Epoch 690/830
20/21 [===========================>..] - ETA: 0s - loss: -185.6210 - accuracy: 0.2594
Epoch 690: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -185.0427 - accuracy: 0.2617 - val_loss: -166.7431 - val_accuracy: 0.2609
Epoch 691/830
20/21 [===========================>..] - ETA: 0s - loss: -183.8554 - accuracy: 0.2625
Epoch 691: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -185.3140 - accuracy: 0.2617 - val_loss: -167.0232 - val_accuracy: 0.2609
Epoch 692/830
20/21 [===========================>..] - ETA: 0s - loss: -184.7730 - accuracy: 0.2625
Epoch 692: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -185.5973 - accuracy: 0.2617 - val_loss: -167.2545 - val_accuracy: 0.2609
Epoch 693/830
20/21 [===========================>..] - ETA: 0s - loss: -186.8339 - accuracy: 0.2609
Epoch 693: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -185.8650 - accuracy: 0.2617 - val_loss: -167.4721 - val_accuracy: 0.2609
Epoch 694/830
20/21 [===========================>..] - ETA: 0s - loss: -187.2146 - accuracy: 0.2609
Epoch 694: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -186.1207 - accuracy: 0.2617 - val_loss: -167.7085 - val_accuracy: 0.2609
Epoch 695/830
20/21 [===========================>..] - ETA: 0s - loss: -186.0634 - accuracy: 0.2625
Epoch 695: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -186.3813 - accuracy: 0.2617 - val_loss: -167.9628 - val_accuracy: 0.2609
Epoch 696/830
20/21 [===========================>..] - ETA: 0s - loss: -186.3583 - accuracy: 0.2609
Epoch 696: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -186.6584 - accuracy: 0.2617 - val_loss: -168.2072 - val_accuracy: 0.2609
Epoch 697/830
20/21 [===========================>..] - ETA: 0s - loss: -187.9384 - accuracy: 0.2609
Epoch 697: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -186.9331 - accuracy: 0.2617 - val_loss: -168.4364 - val_accuracy: 0.2609
Epoch 698/830
20/21 [===========================>..] - ETA: 0s - loss: -188.8467 - accuracy: 0.2625
Epoch 698: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -187.1895 - accuracy: 0.2617 - val_loss: -168.6576 - val_accuracy: 0.2609
Epoch 699/830
20/21 [===========================>..] - ETA: 0s - loss: -188.6279 - accuracy: 0.2609
Epoch 699: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -187.4317 - accuracy: 0.2617 - val_loss: -168.8785 - val_accuracy: 0.2609
Epoch 700/830
20/21 [===========================>..] - ETA: 0s - loss: -185.7564 - accuracy: 0.2625
Epoch 700: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -187.6868 - accuracy: 0.2617 - val_loss: -169.1519 - val_accuracy: 0.2609
Epoch 701/830
20/21 [===========================>..] - ETA: 0s - loss: -187.6164 - accuracy: 0.2609
Epoch 701: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -187.9593 - accuracy: 0.2617 - val_loss: -169.3628 - val_accuracy: 0.2609
Epoch 702/830
20/21 [===========================>..] - ETA: 0s - loss: -187.7515 - accuracy: 0.2625
Epoch 702: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -188.2180 - accuracy: 0.2617 - val_loss: -169.6122 - val_accuracy: 0.2609
Epoch 703/830
20/21 [===========================>..] - ETA: 0s - loss: -188.4655 - accuracy: 0.2625
Epoch 703: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -188.4931 - accuracy: 0.2617 - val_loss: -169.8517 - val_accuracy: 0.2609
Epoch 704/830
20/21 [===========================>..] - ETA: 0s - loss: -186.9203 - accuracy: 0.2625
Epoch 704: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -188.7567 - accuracy: 0.2617 - val_loss: -170.1060 - val_accuracy: 0.2609
Epoch 705/830
20/21 [===========================>..] - ETA: 0s - loss: -187.0935 - accuracy: 0.2625
Epoch 705: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -189.0258 - accuracy: 0.2617 - val_loss: -170.3378 - val_accuracy: 0.2609
Epoch 706/830
20/21 [===========================>..] - ETA: 0s - loss: -190.9463 - accuracy: 0.2625
Epoch 706: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -189.2793 - accuracy: 0.2617 - val_loss: -170.5227 - val_accuracy: 0.2609
Epoch 707/830
20/21 [===========================>..] - ETA: 0s - loss: -189.5849 - accuracy: 0.2609
Epoch 707: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -189.4945 - accuracy: 0.2617 - val_loss: -170.7479 - val_accuracy: 0.2609
Epoch 708/830
20/21 [===========================>..] - ETA: 0s - loss: -189.8883 - accuracy: 0.2625
Epoch 708: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -189.7610 - accuracy: 0.2617 - val_loss: -170.9967 - val_accuracy: 0.2609
Epoch 709/830
20/21 [===========================>..] - ETA: 0s - loss: -190.0614 - accuracy: 0.2609
Epoch 709: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -190.0366 - accuracy: 0.2617 - val_loss: -171.2460 - val_accuracy: 0.2609
Epoch 710/830
20/21 [===========================>..] - ETA: 0s - loss: -191.6341 - accuracy: 0.2609
Epoch 710: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -190.3144 - accuracy: 0.2617 - val_loss: -171.4735 - val_accuracy: 0.2609
Epoch 711/830
20/21 [===========================>..] - ETA: 0s - loss: -188.6413 - accuracy: 0.2625
Epoch 711: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -190.5683 - accuracy: 0.2617 - val_loss: -171.7458 - val_accuracy: 0.2609
Epoch 712/830
20/21 [===========================>..] - ETA: 0s - loss: -190.7997 - accuracy: 0.2625
Epoch 712: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -190.8463 - accuracy: 0.2617 - val_loss: -171.9605 - val_accuracy: 0.2609
Epoch 713/830
20/21 [===========================>..] - ETA: 0s - loss: -191.2368 - accuracy: 0.2609
Epoch 713: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -191.0976 - accuracy: 0.2617 - val_loss: -172.1984 - val_accuracy: 0.2609
Epoch 714/830
20/21 [===========================>..] - ETA: 0s - loss: -192.0476 - accuracy: 0.2625
Epoch 714: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -191.3727 - accuracy: 0.2617 - val_loss: -172.4426 - val_accuracy: 0.2609
Epoch 715/830
20/21 [===========================>..] - ETA: 0s - loss: -193.2702 - accuracy: 0.2625
Epoch 715: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -191.6362 - accuracy: 0.2617 - val_loss: -172.6622 - val_accuracy: 0.2609
Epoch 716/830
20/21 [===========================>..] - ETA: 0s - loss: -193.6703 - accuracy: 0.2625
Epoch 716: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 170ms/step - loss: -191.8824 - accuracy: 0.2617 - val_loss: -172.8887 - val_accuracy: 0.2609
Epoch 717/830
20/21 [===========================>..] - ETA: 0s - loss: -193.2759 - accuracy: 0.2609
Epoch 717: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -192.1256 - accuracy: 0.2617 - val_loss: -173.1108 - val_accuracy: 0.2609
Epoch 718/830
20/21 [===========================>..] - ETA: 0s - loss: -192.4085 - accuracy: 0.2609
Epoch 718: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -192.3833 - accuracy: 0.2617 - val_loss: -173.3689 - val_accuracy: 0.2609
Epoch 719/830
20/21 [===========================>..] - ETA: 0s - loss: -191.7446 - accuracy: 0.2625
Epoch 719: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -192.6725 - accuracy: 0.2617 - val_loss: -173.6398 - val_accuracy: 0.2609
Epoch 720/830
20/21 [===========================>..] - ETA: 0s - loss: -192.4391 - accuracy: 0.2609
Epoch 720: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -192.9558 - accuracy: 0.2617 - val_loss: -173.8789 - val_accuracy: 0.2609
Epoch 721/830
20/21 [===========================>..] - ETA: 0s - loss: -192.8248 - accuracy: 0.2609
Epoch 721: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -193.2345 - accuracy: 0.2617 - val_loss: -174.1332 - val_accuracy: 0.2609
Epoch 722/830
20/21 [===========================>..] - ETA: 0s - loss: -193.6281 - accuracy: 0.2609
Epoch 722: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -193.5161 - accuracy: 0.2617 - val_loss: -174.3779 - val_accuracy: 0.2609
Epoch 723/830
20/21 [===========================>..] - ETA: 0s - loss: -194.6524 - accuracy: 0.2625
Epoch 723: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -193.7875 - accuracy: 0.2617 - val_loss: -174.6137 - val_accuracy: 0.2609
Epoch 724/830
20/21 [===========================>..] - ETA: 0s - loss: -194.5513 - accuracy: 0.2625
Epoch 724: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -194.0475 - accuracy: 0.2617 - val_loss: -174.8503 - val_accuracy: 0.2609
Epoch 725/830
20/21 [===========================>..] - ETA: 0s - loss: -193.2749 - accuracy: 0.2625
Epoch 725: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -194.3214 - accuracy: 0.2617 - val_loss: -175.1229 - val_accuracy: 0.2609
Epoch 726/830
20/21 [===========================>..] - ETA: 0s - loss: -194.4656 - accuracy: 0.2609
Epoch 726: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -194.5991 - accuracy: 0.2617 - val_loss: -175.3525 - val_accuracy: 0.2609
Epoch 727/830
20/21 [===========================>..] - ETA: 0s - loss: -195.1065 - accuracy: 0.2609
Epoch 727: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -194.8707 - accuracy: 0.2617 - val_loss: -175.5947 - val_accuracy: 0.2609
Epoch 728/830
20/21 [===========================>..] - ETA: 0s - loss: -194.8604 - accuracy: 0.2625
Epoch 728: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -195.1363 - accuracy: 0.2617 - val_loss: -175.8421 - val_accuracy: 0.2609
Epoch 729/830
20/21 [===========================>..] - ETA: 0s - loss: -195.3138 - accuracy: 0.2609
Epoch 729: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -195.4146 - accuracy: 0.2617 - val_loss: -176.0904 - val_accuracy: 0.2609
Epoch 730/830
20/21 [===========================>..] - ETA: 0s - loss: -194.8251 - accuracy: 0.2625
Epoch 730: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -195.6950 - accuracy: 0.2617 - val_loss: -176.3525 - val_accuracy: 0.2609
Epoch 731/830
20/21 [===========================>..] - ETA: 0s - loss: -195.2433 - accuracy: 0.2625
Epoch 731: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -195.9760 - accuracy: 0.2617 - val_loss: -176.5999 - val_accuracy: 0.2609
Epoch 732/830
20/21 [===========================>..] - ETA: 0s - loss: -197.2165 - accuracy: 0.2609
Epoch 732: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -196.2536 - accuracy: 0.2617 - val_loss: -176.8271 - val_accuracy: 0.2609
Epoch 733/830
20/21 [===========================>..] - ETA: 0s - loss: -197.6019 - accuracy: 0.2609
Epoch 733: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 161ms/step - loss: -196.5205 - accuracy: 0.2617 - val_loss: -177.0708 - val_accuracy: 0.2609
Epoch 734/830
20/21 [===========================>..] - ETA: 0s - loss: -197.3994 - accuracy: 0.2594
Epoch 734: saving model to training_1/cp.ckpt
21/21 [==============================] - 5s 189ms/step - loss: -196.7844 - accuracy: 0.2617 - val_loss: -177.3133 - val_accuracy: 0.2609
Epoch 735/830
20/21 [===========================>..] - ETA: 0s - loss: -196.6522 - accuracy: 0.2609
Epoch 735: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -197.0590 - accuracy: 0.2617 - val_loss: -177.5819 - val_accuracy: 0.2609
Epoch 736/830
20/21 [===========================>..] - ETA: 0s - loss: -196.7898 - accuracy: 0.2625
Epoch 736: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -197.3460 - accuracy: 0.2617 - val_loss: -177.8318 - val_accuracy: 0.2609
Epoch 737/830
20/21 [===========================>..] - ETA: 0s - loss: -197.0563 - accuracy: 0.2625
Epoch 737: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -197.6268 - accuracy: 0.2617 - val_loss: -178.0872 - val_accuracy: 0.2609
Epoch 738/830
20/21 [===========================>..] - ETA: 0s - loss: -196.8588 - accuracy: 0.2609
Epoch 738: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -197.9106 - accuracy: 0.2617 - val_loss: -178.3444 - val_accuracy: 0.2609
Epoch 739/830
20/21 [===========================>..] - ETA: 0s - loss: -198.2240 - accuracy: 0.2609
Epoch 739: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -198.1846 - accuracy: 0.2617 - val_loss: -178.5707 - val_accuracy: 0.2609
Epoch 740/830
20/21 [===========================>..] - ETA: 0s - loss: -199.3474 - accuracy: 0.2625
Epoch 740: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -198.4500 - accuracy: 0.2617 - val_loss: -178.8067 - val_accuracy: 0.2609
Epoch 741/830
20/21 [===========================>..] - ETA: 0s - loss: -200.3244 - accuracy: 0.2625
Epoch 741: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -198.7091 - accuracy: 0.2617 - val_loss: -179.0303 - val_accuracy: 0.2609
Epoch 742/830
20/21 [===========================>..] - ETA: 0s - loss: -198.0306 - accuracy: 0.2625
Epoch 742: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -198.9606 - accuracy: 0.2617 - val_loss: -179.2896 - val_accuracy: 0.2609
Epoch 743/830
20/21 [===========================>..] - ETA: 0s - loss: -199.1089 - accuracy: 0.2609
Epoch 743: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -199.2349 - accuracy: 0.2617 - val_loss: -179.5244 - val_accuracy: 0.2609
Epoch 744/830
20/21 [===========================>..] - ETA: 0s - loss: -201.4845 - accuracy: 0.2625
Epoch 744: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -199.5038 - accuracy: 0.2617 - val_loss: -179.7370 - val_accuracy: 0.2609
Epoch 745/830
20/21 [===========================>..] - ETA: 0s - loss: -198.8255 - accuracy: 0.2625
Epoch 745: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -199.7360 - accuracy: 0.2617 - val_loss: -179.9893 - val_accuracy: 0.2609
Epoch 746/830
20/21 [===========================>..] - ETA: 0s - loss: -201.0742 - accuracy: 0.2609
Epoch 746: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -200.0120 - accuracy: 0.2617 - val_loss: -180.2053 - val_accuracy: 0.2609
Epoch 747/830
20/21 [===========================>..] - ETA: 0s - loss: -198.3948 - accuracy: 0.2625
Epoch 747: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -200.2567 - accuracy: 0.2617 - val_loss: -180.4663 - val_accuracy: 0.2609
Epoch 748/830
20/21 [===========================>..] - ETA: 0s - loss: -200.1078 - accuracy: 0.2625
Epoch 748: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -200.5278 - accuracy: 0.2617 - val_loss: -180.6863 - val_accuracy: 0.2609
Epoch 749/830
20/21 [===========================>..] - ETA: 0s - loss: -201.4158 - accuracy: 0.2594
Epoch 749: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -200.7883 - accuracy: 0.2617 - val_loss: -180.9174 - val_accuracy: 0.2609
Epoch 750/830
20/21 [===========================>..] - ETA: 0s - loss: -202.1389 - accuracy: 0.2609
Epoch 750: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -201.0562 - accuracy: 0.2617 - val_loss: -181.1544 - val_accuracy: 0.2609
Epoch 751/830
20/21 [===========================>..] - ETA: 0s - loss: -201.6844 - accuracy: 0.2625
Epoch 751: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -201.3232 - accuracy: 0.2617 - val_loss: -181.4074 - val_accuracy: 0.2609
Epoch 752/830
20/21 [===========================>..] - ETA: 0s - loss: -201.1473 - accuracy: 0.2609
Epoch 752: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -201.5960 - accuracy: 0.2617 - val_loss: -181.6610 - val_accuracy: 0.2609
Epoch 753/830
20/21 [===========================>..] - ETA: 0s - loss: -203.4251 - accuracy: 0.2625
Epoch 753: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -201.8889 - accuracy: 0.2617 - val_loss: -181.8960 - val_accuracy: 0.2609
Epoch 754/830
20/21 [===========================>..] - ETA: 0s - loss: -201.8475 - accuracy: 0.2609
Epoch 754: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -202.1389 - accuracy: 0.2617 - val_loss: -182.1489 - val_accuracy: 0.2609
Epoch 755/830
20/21 [===========================>..] - ETA: 0s - loss: -201.8234 - accuracy: 0.2625
Epoch 755: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -202.4193 - accuracy: 0.2617 - val_loss: -182.4026 - val_accuracy: 0.2609
Epoch 756/830
20/21 [===========================>..] - ETA: 0s - loss: -202.7267 - accuracy: 0.2609
Epoch 756: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -202.6940 - accuracy: 0.2617 - val_loss: -182.6357 - val_accuracy: 0.2609
Epoch 757/830
20/21 [===========================>..] - ETA: 0s - loss: -203.6637 - accuracy: 0.2625
Epoch 757: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -202.9693 - accuracy: 0.2617 - val_loss: -182.8856 - val_accuracy: 0.2609
Epoch 758/830
20/21 [===========================>..] - ETA: 0s - loss: -202.6696 - accuracy: 0.2625
Epoch 758: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -203.2500 - accuracy: 0.2617 - val_loss: -183.1542 - val_accuracy: 0.2609
Epoch 759/830
20/21 [===========================>..] - ETA: 0s - loss: -203.3650 - accuracy: 0.2625
Epoch 759: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -203.5336 - accuracy: 0.2617 - val_loss: -183.3958 - val_accuracy: 0.2609
Epoch 760/830
20/21 [===========================>..] - ETA: 0s - loss: -201.9102 - accuracy: 0.2625
Epoch 760: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -203.8054 - accuracy: 0.2617 - val_loss: -183.6588 - val_accuracy: 0.2609
Epoch 761/830
20/21 [===========================>..] - ETA: 0s - loss: -203.7203 - accuracy: 0.2625
Epoch 761: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -204.0772 - accuracy: 0.2617 - val_loss: -183.8715 - val_accuracy: 0.2609
Epoch 762/830
20/21 [===========================>..] - ETA: 0s - loss: -206.0629 - accuracy: 0.2625
Epoch 762: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -204.3355 - accuracy: 0.2617 - val_loss: -184.0912 - val_accuracy: 0.2609
Epoch 763/830
20/21 [===========================>..] - ETA: 0s - loss: -203.6975 - accuracy: 0.2625
Epoch 763: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -204.5720 - accuracy: 0.2617 - val_loss: -184.3408 - val_accuracy: 0.2609
Epoch 764/830
20/21 [===========================>..] - ETA: 0s - loss: -202.6287 - accuracy: 0.2625
Epoch 764: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -204.8496 - accuracy: 0.2617 - val_loss: -184.5998 - val_accuracy: 0.2609
Epoch 765/830
20/21 [===========================>..] - ETA: 0s - loss: -205.0432 - accuracy: 0.2609
Epoch 765: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -205.1144 - accuracy: 0.2617 - val_loss: -184.8085 - val_accuracy: 0.2609
Epoch 766/830
20/21 [===========================>..] - ETA: 0s - loss: -204.4708 - accuracy: 0.2625
Epoch 766: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -205.3719 - accuracy: 0.2617 - val_loss: -185.0625 - val_accuracy: 0.2609
Epoch 767/830
20/21 [===========================>..] - ETA: 0s - loss: -206.2957 - accuracy: 0.2594
Epoch 767: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -205.6531 - accuracy: 0.2617 - val_loss: -185.2964 - val_accuracy: 0.2609
Epoch 768/830
20/21 [===========================>..] - ETA: 0s - loss: -206.4778 - accuracy: 0.2625
Epoch 768: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -205.9176 - accuracy: 0.2617 - val_loss: -185.5369 - val_accuracy: 0.2609
Epoch 769/830
20/21 [===========================>..] - ETA: 0s - loss: -205.3415 - accuracy: 0.2625
Epoch 769: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -206.1923 - accuracy: 0.2617 - val_loss: -185.8082 - val_accuracy: 0.2609
Epoch 770/830
20/21 [===========================>..] - ETA: 0s - loss: -208.5428 - accuracy: 0.2625
Epoch 770: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -206.4707 - accuracy: 0.2617 - val_loss: -186.0049 - val_accuracy: 0.2609
Epoch 771/830
20/21 [===========================>..] - ETA: 0s - loss: -207.7421 - accuracy: 0.2609
Epoch 771: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -206.6982 - accuracy: 0.2617 - val_loss: -186.2268 - val_accuracy: 0.2609
Epoch 772/830
20/21 [===========================>..] - ETA: 0s - loss: -206.9444 - accuracy: 0.2625
Epoch 772: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -206.9554 - accuracy: 0.2617 - val_loss: -186.4810 - val_accuracy: 0.2609
Epoch 773/830
20/21 [===========================>..] - ETA: 0s - loss: -207.1852 - accuracy: 0.2609
Epoch 773: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -207.2304 - accuracy: 0.2617 - val_loss: -186.7274 - val_accuracy: 0.2609
Epoch 774/830
20/21 [===========================>..] - ETA: 0s - loss: -208.2666 - accuracy: 0.2625
Epoch 774: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -207.5178 - accuracy: 0.2617 - val_loss: -186.9762 - val_accuracy: 0.2609
Epoch 775/830
20/21 [===========================>..] - ETA: 0s - loss: -208.4359 - accuracy: 0.2594
Epoch 775: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -207.7865 - accuracy: 0.2617 - val_loss: -187.2169 - val_accuracy: 0.2609
Epoch 776/830
20/21 [===========================>..] - ETA: 0s - loss: -207.0258 - accuracy: 0.2609
Epoch 776: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -208.0639 - accuracy: 0.2617 - val_loss: -187.4906 - val_accuracy: 0.2609
Epoch 777/830
20/21 [===========================>..] - ETA: 0s - loss: -209.3513 - accuracy: 0.2609
Epoch 777: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -208.3497 - accuracy: 0.2617 - val_loss: -187.7093 - val_accuracy: 0.2609
Epoch 778/830
21/21 [==============================] - ETA: 0s - loss: -208.5966 - accuracy: 0.2617
Epoch 778: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -208.5966 - accuracy: 0.2617 - val_loss: -187.9601 - val_accuracy: 0.2609
Epoch 779/830
20/21 [===========================>..] - ETA: 0s - loss: -207.1281 - accuracy: 0.2625
Epoch 779: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -208.8781 - accuracy: 0.2617 - val_loss: -188.2244 - val_accuracy: 0.2609
Epoch 780/830
20/21 [===========================>..] - ETA: 0s - loss: -209.0852 - accuracy: 0.2609
Epoch 780: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -209.1599 - accuracy: 0.2617 - val_loss: -188.4495 - val_accuracy: 0.2609
Epoch 781/830
20/21 [===========================>..] - ETA: 0s - loss: -208.7401 - accuracy: 0.2625
Epoch 781: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -209.4156 - accuracy: 0.2617 - val_loss: -188.6977 - val_accuracy: 0.2609
Epoch 782/830
20/21 [===========================>..] - ETA: 0s - loss: -209.3573 - accuracy: 0.2609
Epoch 782: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -209.6945 - accuracy: 0.2617 - val_loss: -188.9439 - val_accuracy: 0.2609
Epoch 783/830
20/21 [===========================>..] - ETA: 0s - loss: -211.9240 - accuracy: 0.2625
Epoch 783: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -209.9679 - accuracy: 0.2617 - val_loss: -189.1634 - val_accuracy: 0.2609
Epoch 784/830
20/21 [===========================>..] - ETA: 0s - loss: -210.3574 - accuracy: 0.2609
Epoch 784: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -210.2118 - accuracy: 0.2617 - val_loss: -189.4029 - val_accuracy: 0.2609
Epoch 785/830
20/21 [===========================>..] - ETA: 0s - loss: -209.7376 - accuracy: 0.2625
Epoch 785: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 169ms/step - loss: -210.4871 - accuracy: 0.2617 - val_loss: -189.6665 - val_accuracy: 0.2609
Epoch 786/830
20/21 [===========================>..] - ETA: 0s - loss: -212.5997 - accuracy: 0.2625
Epoch 786: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -210.7673 - accuracy: 0.2617 - val_loss: -189.8780 - val_accuracy: 0.2609
Epoch 787/830
20/21 [===========================>..] - ETA: 0s - loss: -211.5712 - accuracy: 0.2625
Epoch 787: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -211.0046 - accuracy: 0.2617 - val_loss: -190.1142 - val_accuracy: 0.2609
Epoch 788/830
20/21 [===========================>..] - ETA: 0s - loss: -212.2718 - accuracy: 0.2609
Epoch 788: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -211.2661 - accuracy: 0.2617 - val_loss: -190.3430 - val_accuracy: 0.2609
Epoch 789/830
20/21 [===========================>..] - ETA: 0s - loss: -209.9189 - accuracy: 0.2625
Epoch 789: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -211.5332 - accuracy: 0.2617 - val_loss: -190.6224 - val_accuracy: 0.2609
Epoch 790/830
20/21 [===========================>..] - ETA: 0s - loss: -210.5626 - accuracy: 0.2625
Epoch 790: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -211.8114 - accuracy: 0.2617 - val_loss: -190.8562 - val_accuracy: 0.2609
Epoch 791/830
20/21 [===========================>..] - ETA: 0s - loss: -211.5083 - accuracy: 0.2609
Epoch 791: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -212.0788 - accuracy: 0.2617 - val_loss: -191.0929 - val_accuracy: 0.2609
Epoch 792/830
20/21 [===========================>..] - ETA: 0s - loss: -211.4058 - accuracy: 0.2609
Epoch 792: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -212.3416 - accuracy: 0.2617 - val_loss: -191.3347 - val_accuracy: 0.2609
Epoch 793/830
20/21 [===========================>..] - ETA: 0s - loss: -212.0207 - accuracy: 0.2609
Epoch 793: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -212.6179 - accuracy: 0.2617 - val_loss: -191.5802 - val_accuracy: 0.2609
Epoch 794/830
20/21 [===========================>..] - ETA: 0s - loss: -212.9740 - accuracy: 0.2609
Epoch 794: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -212.8831 - accuracy: 0.2617 - val_loss: -191.8129 - val_accuracy: 0.2609
Epoch 795/830
20/21 [===========================>..] - ETA: 0s - loss: -213.9379 - accuracy: 0.2625
Epoch 795: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -213.1587 - accuracy: 0.2617 - val_loss: -192.0549 - val_accuracy: 0.2609
Epoch 796/830
20/21 [===========================>..] - ETA: 0s - loss: -212.8625 - accuracy: 0.2625
Epoch 796: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -213.4214 - accuracy: 0.2617 - val_loss: -192.3096 - val_accuracy: 0.2609
Epoch 797/830
20/21 [===========================>..] - ETA: 0s - loss: -214.3723 - accuracy: 0.2594
Epoch 797: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -213.7045 - accuracy: 0.2617 - val_loss: -192.5458 - val_accuracy: 0.2609
Epoch 798/830
20/21 [===========================>..] - ETA: 0s - loss: -213.0779 - accuracy: 0.2625
Epoch 798: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -213.9721 - accuracy: 0.2617 - val_loss: -192.8109 - val_accuracy: 0.2609
Epoch 799/830
20/21 [===========================>..] - ETA: 0s - loss: -214.8743 - accuracy: 0.2625
Epoch 799: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -214.2585 - accuracy: 0.2617 - val_loss: -193.0390 - val_accuracy: 0.2609
Epoch 800/830
20/21 [===========================>..] - ETA: 0s - loss: -213.8537 - accuracy: 0.2625
Epoch 800: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -214.5243 - accuracy: 0.2617 - val_loss: -193.3044 - val_accuracy: 0.2609
Epoch 801/830
20/21 [===========================>..] - ETA: 0s - loss: -215.1069 - accuracy: 0.2625
Epoch 801: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -214.8128 - accuracy: 0.2617 - val_loss: -193.5449 - val_accuracy: 0.2609
Epoch 802/830
20/21 [===========================>..] - ETA: 0s - loss: -213.0086 - accuracy: 0.2625
Epoch 802: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -215.0746 - accuracy: 0.2617 - val_loss: -193.8011 - val_accuracy: 0.2609
Epoch 803/830
20/21 [===========================>..] - ETA: 0s - loss: -215.9345 - accuracy: 0.2625
Epoch 803: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -215.3459 - accuracy: 0.2617 - val_loss: -194.0076 - val_accuracy: 0.2609
Epoch 804/830
20/21 [===========================>..] - ETA: 0s - loss: -215.3094 - accuracy: 0.2609
Epoch 804: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -215.5884 - accuracy: 0.2617 - val_loss: -194.2450 - val_accuracy: 0.2609
Epoch 805/830
20/21 [===========================>..] - ETA: 0s - loss: -217.9029 - accuracy: 0.2625
Epoch 805: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -215.8627 - accuracy: 0.2617 - val_loss: -194.4705 - val_accuracy: 0.2609
Epoch 806/830
20/21 [===========================>..] - ETA: 0s - loss: -217.5033 - accuracy: 0.2609
Epoch 806: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -216.1017 - accuracy: 0.2617 - val_loss: -194.6882 - val_accuracy: 0.2609
Epoch 807/830
20/21 [===========================>..] - ETA: 0s - loss: -215.6051 - accuracy: 0.2625
Epoch 807: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 167ms/step - loss: -216.3456 - accuracy: 0.2617 - val_loss: -194.9405 - val_accuracy: 0.2609
Epoch 808/830
20/21 [===========================>..] - ETA: 0s - loss: -217.3136 - accuracy: 0.2625
Epoch 808: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -216.6270 - accuracy: 0.2617 - val_loss: -195.1701 - val_accuracy: 0.2609
Epoch 809/830
20/21 [===========================>..] - ETA: 0s - loss: -215.9453 - accuracy: 0.2625
Epoch 809: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -216.8734 - accuracy: 0.2617 - val_loss: -195.4111 - val_accuracy: 0.2609
Epoch 810/830
20/21 [===========================>..] - ETA: 0s - loss: -215.9622 - accuracy: 0.2625
Epoch 810: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -217.1438 - accuracy: 0.2617 - val_loss: -195.6609 - val_accuracy: 0.2609
Epoch 811/830
20/21 [===========================>..] - ETA: 0s - loss: -219.1190 - accuracy: 0.2625
Epoch 811: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 162ms/step - loss: -217.4193 - accuracy: 0.2617 - val_loss: -195.8669 - val_accuracy: 0.2609
Epoch 812/830
20/21 [===========================>..] - ETA: 0s - loss: -217.5871 - accuracy: 0.2625
Epoch 812: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -217.6616 - accuracy: 0.2617 - val_loss: -196.1180 - val_accuracy: 0.2609
Epoch 813/830
20/21 [===========================>..] - ETA: 0s - loss: -217.8094 - accuracy: 0.2609
Epoch 813: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 168ms/step - loss: -217.9315 - accuracy: 0.2617 - val_loss: -196.3575 - val_accuracy: 0.2609
Epoch 814/830
20/21 [===========================>..] - ETA: 0s - loss: -216.8822 - accuracy: 0.2625
Epoch 814: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -218.2090 - accuracy: 0.2617 - val_loss: -196.6285 - val_accuracy: 0.2609
Epoch 815/830
20/21 [===========================>..] - ETA: 0s - loss: -218.9071 - accuracy: 0.2625
Epoch 815: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 163ms/step - loss: -218.4896 - accuracy: 0.2617 - val_loss: -196.8474 - val_accuracy: 0.2609
Epoch 816/830
20/21 [===========================>..] - ETA: 0s - loss: -218.1792 - accuracy: 0.2625
Epoch 816: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -218.7536 - accuracy: 0.2617 - val_loss: -197.1112 - val_accuracy: 0.2609
Epoch 817/830
20/21 [===========================>..] - ETA: 0s - loss: -218.7248 - accuracy: 0.2609
Epoch 817: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -219.0405 - accuracy: 0.2617 - val_loss: -197.3549 - val_accuracy: 0.2609
Epoch 818/830
20/21 [===========================>..] - ETA: 0s - loss: -217.4065 - accuracy: 0.2625
Epoch 818: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -219.3196 - accuracy: 0.2617 - val_loss: -197.6227 - val_accuracy: 0.2609
Epoch 819/830
20/21 [===========================>..] - ETA: 0s - loss: -218.9984 - accuracy: 0.2625
Epoch 819: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -219.5959 - accuracy: 0.2617 - val_loss: -197.8499 - val_accuracy: 0.2609
Epoch 820/830
20/21 [===========================>..] - ETA: 0s - loss: -219.8165 - accuracy: 0.2609
Epoch 820: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -219.8507 - accuracy: 0.2617 - val_loss: -198.0779 - val_accuracy: 0.2609
Epoch 821/830
20/21 [===========================>..] - ETA: 0s - loss: -218.6243 - accuracy: 0.2625
Epoch 821: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -220.1200 - accuracy: 0.2617 - val_loss: -198.3421 - val_accuracy: 0.2609
Epoch 822/830
20/21 [===========================>..] - ETA: 0s - loss: -219.5532 - accuracy: 0.2609
Epoch 822: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -220.3955 - accuracy: 0.2617 - val_loss: -198.5751 - val_accuracy: 0.2609
Epoch 823/830
20/21 [===========================>..] - ETA: 0s - loss: -221.3560 - accuracy: 0.2594
Epoch 823: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -220.6664 - accuracy: 0.2617 - val_loss: -198.8045 - val_accuracy: 0.2609
Epoch 824/830
20/21 [===========================>..] - ETA: 0s - loss: -220.0304 - accuracy: 0.2625
Epoch 824: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -220.9355 - accuracy: 0.2617 - val_loss: -199.0727 - val_accuracy: 0.2609
Epoch 825/830
20/21 [===========================>..] - ETA: 0s - loss: -223.1446 - accuracy: 0.2625
Epoch 825: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -221.2215 - accuracy: 0.2617 - val_loss: -199.2868 - val_accuracy: 0.2609
Epoch 826/830
20/21 [===========================>..] - ETA: 0s - loss: -221.3142 - accuracy: 0.2625
Epoch 826: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -221.4569 - accuracy: 0.2617 - val_loss: -199.5291 - val_accuracy: 0.2609
Epoch 827/830
20/21 [===========================>..] - ETA: 0s - loss: -220.4675 - accuracy: 0.2625
Epoch 827: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 165ms/step - loss: -221.7252 - accuracy: 0.2617 - val_loss: -199.7852 - val_accuracy: 0.2609
Epoch 828/830
20/21 [===========================>..] - ETA: 0s - loss: -224.4209 - accuracy: 0.2625
Epoch 828: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 164ms/step - loss: -222.0017 - accuracy: 0.2617 - val_loss: -199.9863 - val_accuracy: 0.2609
Epoch 829/830
20/21 [===========================>..] - ETA: 0s - loss: -224.4190 - accuracy: 0.2625
Epoch 829: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 166ms/step - loss: -222.2255 - accuracy: 0.2617 - val_loss: -200.1907 - val_accuracy: 0.2609
Epoch 830/830
20/21 [===========================>..] - ETA: 0s - loss: -221.8635 - accuracy: 0.2625
Epoch 830: saving model to training_1/cp.ckpt
21/21 [==============================] - 4s 189ms/step - loss: -222.4579 - accuracy: 0.2617 - val_loss: -200.4411 - val_accuracy: 0.2609



Epoch 830/930
21/21 [==============================] - 12s 221ms/step - loss: -360.1625 - accuracy: 0.2617 - val_loss: -200.6917 - val_accuracy: 0.2609
Epoch 831/930
21/21 [==============================] - 4s 179ms/step - loss: -411.2680 - accuracy: 0.2617 - val_loss: -197.3088 - val_accuracy: 0.2609
Epoch 832/930
21/21 [==============================] - 5s 182ms/step - loss: -457.1402 - accuracy: 0.2617 - val_loss: -189.8385 - val_accuracy: 0.2609
Epoch 833/930
21/21 [==============================] - 4s 180ms/step - loss: -500.3221 - accuracy: 0.2617 - val_loss: -183.2904 - val_accuracy: 0.2609
Epoch 834/930
21/21 [==============================] - 4s 181ms/step - loss: -558.0883 - accuracy: 0.2617 - val_loss: -172.7488 - val_accuracy: 0.2609
Epoch 835/930
21/21 [==============================] - 4s 180ms/step - loss: -617.8730 - accuracy: 0.2617 - val_loss: -164.1339 - val_accuracy: 0.2609
Epoch 836/930
21/21 [==============================] - 4s 181ms/step - loss: -675.4917 - accuracy: 0.2617 - val_loss: -149.8737 - val_accuracy: 0.2609
Epoch 837/930
21/21 [==============================] - 4s 180ms/step - loss: -742.5988 - accuracy: 0.2617 - val_loss: -139.3675 - val_accuracy: 0.2609
Epoch 838/930
21/21 [==============================] - 5s 180ms/step - loss: -812.7107 - accuracy: 0.2617 - val_loss: -132.6418 - val_accuracy: 0.2609
Epoch 839/930
21/21 [==============================] - 4s 180ms/step - loss: -879.8080 - accuracy: 0.2617 - val_loss: -129.5714 - val_accuracy: 0.2609
Epoch 840/930
21/21 [==============================] - 5s 182ms/step - loss: -940.3779 - accuracy: 0.2617 - val_loss: -122.2758 - val_accuracy: 0.2609
Epoch 841/930
21/21 [==============================] - 5s 180ms/step - loss: -1005.3481 - accuracy: 0.2617 - val_loss: -118.5022 - val_accuracy: 0.2609
Epoch 842/930
21/21 [==============================] - 4s 180ms/step - loss: -1074.5382 - accuracy: 0.2617 - val_loss: -120.1452 - val_accuracy: 0.2609
Epoch 843/930
21/21 [==============================] - 4s 180ms/step - loss: -1137.9709 - accuracy: 0.2617 - val_loss: -121.0301 - val_accuracy: 0.2609
Epoch 844/930
21/21 [==============================] - 5s 180ms/step - loss: -1205.8915 - accuracy: 0.2617 - val_loss: -125.5192 - val_accuracy: 0.2609
Epoch 845/930
21/21 [==============================] - 4s 179ms/step - loss: -1282.8057 - accuracy: 0.2617 - val_loss: -129.5839 - val_accuracy: 0.2609
Epoch 846/930
21/21 [==============================] - 4s 179ms/step - loss: -1338.8478 - accuracy: 0.2617 - val_loss: -141.8486 - val_accuracy: 0.2609
Epoch 847/930
21/21 [==============================] - 4s 179ms/step - loss: -1398.5887 - accuracy: 0.2617 - val_loss: -151.5022 - val_accuracy: 0.2609
Epoch 848/930
21/21 [==============================] - 4s 180ms/step - loss: -1468.2715 - accuracy: 0.2617 - val_loss: -180.3663 - val_accuracy: 0.2609
Epoch 849/930
21/21 [==============================] - 4s 180ms/step - loss: -1521.1489 - accuracy: 0.2617 - val_loss: -198.9556 - val_accuracy: 0.2609
Epoch 850/930
21/21 [==============================] - 4s 180ms/step - loss: -1575.3508 - accuracy: 0.2617 - val_loss: -215.0495 - val_accuracy: 0.2609
Epoch 851/930
21/21 [==============================] - 4s 179ms/step - loss: -1634.9194 - accuracy: 0.2617 - val_loss: -224.2258 - val_accuracy: 0.2609
Epoch 852/930
21/21 [==============================] - 4s 181ms/step - loss: -1648.7451 - accuracy: 0.2617 - val_loss: -271.2778 - val_accuracy: 0.2609
Epoch 853/930
21/21 [==============================] - 5s 179ms/step - loss: -1708.7310 - accuracy: 0.2617 - val_loss: -315.8470 - val_accuracy: 0.2609
Epoch 854/930
21/21 [==============================] - 4s 181ms/step - loss: -1735.9656 - accuracy: 0.2617 - val_loss: -344.2692 - val_accuracy: 0.2609
Epoch 855/930
21/21 [==============================] - 4s 182ms/step - loss: -1771.3145 - accuracy: 0.2617 - val_loss: -362.9887 - val_accuracy: 0.2609
Epoch 856/930
21/21 [==============================] - 4s 181ms/step - loss: -1859.0798 - accuracy: 0.2617 - val_loss: -417.2768 - val_accuracy: 0.2609
Epoch 857/930
21/21 [==============================] - 4s 179ms/step - loss: -1914.3665 - accuracy: 0.2617 - val_loss: -477.3849 - val_accuracy: 0.2609
Epoch 858/930
21/21 [==============================] - 4s 181ms/step - loss: -1913.6680 - accuracy: 0.2617 - val_loss: -500.4326 - val_accuracy: 0.2609
Epoch 859/930
21/21 [==============================] - 4s 179ms/step - loss: -1927.5709 - accuracy: 0.2617 - val_loss: -472.8360 - val_accuracy: 0.2609
Epoch 860/930
21/21 [==============================] - 4s 180ms/step - loss: -1966.9233 - accuracy: 0.2617 - val_loss: -493.1004 - val_accuracy: 0.2609
Epoch 861/930
21/21 [==============================] - 4s 180ms/step - loss: -2034.4598 - accuracy: 0.2617 - val_loss: -523.9993 - val_accuracy: 0.2609
Epoch 862/930
21/21 [==============================] - 4s 179ms/step - loss: -2077.4448 - accuracy: 0.2617 - val_loss: -512.4680 - val_accuracy: 0.2609
Epoch 863/930
21/21 [==============================] - 4s 179ms/step - loss: -2056.2771 - accuracy: 0.2617 - val_loss: -515.2181 - val_accuracy: 0.2609
Epoch 864/930
21/21 [==============================] - 5s 181ms/step - loss: -2099.9651 - accuracy: 0.2617 - val_loss: -499.2907 - val_accuracy: 0.2609
Epoch 865/930
21/21 [==============================] - 4s 180ms/step - loss: -2129.7793 - accuracy: 0.2617 - val_loss: -474.9835 - val_accuracy: 0.2609
Epoch 866/930
21/21 [==============================] - 4s 180ms/step - loss: -2153.9141 - accuracy: 0.2617 - val_loss: -503.2149 - val_accuracy: 0.2609
Epoch 867/930
21/21 [==============================] - 5s 181ms/step - loss: -2160.2498 - accuracy: 0.2617 - val_loss: -493.2190 - val_accuracy: 0.2609
Epoch 868/930
21/21 [==============================] - 4s 181ms/step - loss: -2184.0833 - accuracy: 0.2617 - val_loss: -463.3849 - val_accuracy: 0.2609
Epoch 869/930
21/21 [==============================] - 4s 179ms/step - loss: -2178.5701 - accuracy: 0.2617 - val_loss: -447.0753 - val_accuracy: 0.2609
Epoch 870/930
21/21 [==============================] - 5s 181ms/step - loss: -2203.9946 - accuracy: 0.2617 - val_loss: -436.8973 - val_accuracy: 0.2609
Epoch 871/930
21/21 [==============================] - 4s 180ms/step - loss: -2233.3254 - accuracy: 0.2617 - val_loss: -439.6349 - val_accuracy: 0.2609
Epoch 872/930
21/21 [==============================] - 4s 180ms/step - loss: -2247.9988 - accuracy: 0.2617 - val_loss: -446.1808 - val_accuracy: 0.2609
Epoch 873/930
21/21 [==============================] - 4s 181ms/step - loss: -2294.7397 - accuracy: 0.2617 - val_loss: -460.4512 - val_accuracy: 0.2609
Epoch 874/930
21/21 [==============================] - 4s 181ms/step - loss: -2331.7583 - accuracy: 0.2617 - val_loss: -450.4458 - val_accuracy: 0.2609
Epoch 875/930
21/21 [==============================] - 5s 181ms/step - loss: -2371.3425 - accuracy: 0.2617 - val_loss: -432.7750 - val_accuracy: 0.2609
Epoch 876/930
21/21 [==============================] - 5s 181ms/step - loss: -2290.3921 - accuracy: 0.2617 - val_loss: -440.4396 - val_accuracy: 0.2609
Epoch 877/930
21/21 [==============================] - 4s 180ms/step - loss: -2384.2380 - accuracy: 0.2617 - val_loss: -439.8216 - val_accuracy: 0.2609
Epoch 878/930
21/21 [==============================] - 4s 181ms/step - loss: -2368.8918 - accuracy: 0.2617 - val_loss: -413.7596 - val_accuracy: 0.2609
Epoch 879/930
21/21 [==============================] - 5s 180ms/step - loss: -2351.8953 - accuracy: 0.2617 - val_loss: -403.3851 - val_accuracy: 0.2609
Epoch 880/930
21/21 [==============================] - 4s 180ms/step - loss: -2459.2742 - accuracy: 0.2617 - val_loss: -374.6290 - val_accuracy: 0.2609
Epoch 881/930
21/21 [==============================] - 4s 180ms/step - loss: -2434.8149 - accuracy: 0.2617 - val_loss: -361.4822 - val_accuracy: 0.2609
Epoch 882/930
21/21 [==============================] - 4s 179ms/step - loss: -2480.3457 - accuracy: 0.2617 - val_loss: -338.8993 - val_accuracy: 0.2609
Epoch 883/930
21/21 [==============================] - 4s 179ms/step - loss: -2494.8694 - accuracy: 0.2617 - val_loss: -329.7845 - val_accuracy: 0.2609
Epoch 884/930
21/21 [==============================] - 4s 182ms/step - loss: -2531.4758 - accuracy: 0.2617 - val_loss: -325.1349 - val_accuracy: 0.2609
Epoch 885/930
21/21 [==============================] - 5s 179ms/step - loss: -2529.6785 - accuracy: 0.2617 - val_loss: -322.1754 - val_accuracy: 0.2609
Epoch 886/930
21/21 [==============================] - 4s 183ms/step - loss: -2523.4814 - accuracy: 0.2617 - val_loss: -332.8174 - val_accuracy: 0.2609
Epoch 887/930
21/21 [==============================] - 5s 185ms/step - loss: -2528.4434 - accuracy: 0.2617 - val_loss: -334.8138 - val_accuracy: 0.2609
Epoch 888/930
21/21 [==============================] - 5s 181ms/step - loss: -2499.2520 - accuracy: 0.2617 - val_loss: -316.2396 - val_accuracy: 0.2609
Epoch 889/930
21/21 [==============================] - 5s 179ms/step - loss: -2529.8877 - accuracy: 0.2617 - val_loss: -310.2762 - val_accuracy: 0.2609
Epoch 890/930
21/21 [==============================] - 4s 181ms/step - loss: -2591.8291 - accuracy: 0.2617 - val_loss: -304.1946 - val_accuracy: 0.2609
Epoch 891/930
21/21 [==============================] - 5s 179ms/step - loss: -2588.8467 - accuracy: 0.2617 - val_loss: -297.5925 - val_accuracy: 0.2609
Epoch 892/930
21/21 [==============================] - 4s 180ms/step - loss: -2623.3909 - accuracy: 0.2617 - val_loss: -279.2535 - val_accuracy: 0.2609
Epoch 893/930
21/21 [==============================] - 4s 182ms/step - loss: -2606.9741 - accuracy: 0.2617 - val_loss: -265.0380 - val_accuracy: 0.2609
Epoch 894/930
21/21 [==============================] - 4s 180ms/step - loss: -2624.1189 - accuracy: 0.2617 - val_loss: -281.8615 - val_accuracy: 0.2609
Epoch 895/930
21/21 [==============================] - 4s 179ms/step - loss: -2613.3457 - accuracy: 0.2617 - val_loss: -287.9758 - val_accuracy: 0.2609
Epoch 896/930
21/21 [==============================] - 4s 182ms/step - loss: -2651.7288 - accuracy: 0.2617 - val_loss: -248.4946 - val_accuracy: 0.2609
Epoch 897/930
21/21 [==============================] - 4s 180ms/step - loss: -2672.6174 - accuracy: 0.2617 - val_loss: -264.5689 - val_accuracy: 0.2609
Epoch 898/930
21/21 [==============================] - 4s 180ms/step - loss: -2629.4631 - accuracy: 0.2617 - val_loss: -263.6587 - val_accuracy: 0.2609
Epoch 899/930
21/21 [==============================] - 4s 180ms/step - loss: -2666.5508 - accuracy: 0.2617 - val_loss: -266.9302 - val_accuracy: 0.2609
Epoch 900/930
21/21 [==============================] - 4s 180ms/step - loss: -2645.4016 - accuracy: 0.2617 - val_loss: -291.5848 - val_accuracy: 0.2609
Epoch 901/930
21/21 [==============================] - 4s 180ms/step - loss: -2716.9370 - accuracy: 0.2617 - val_loss: -260.8102 - val_accuracy: 0.2609
Epoch 902/930
21/21 [==============================] - 4s 179ms/step - loss: -2682.1489 - accuracy: 0.2617 - val_loss: -249.1955 - val_accuracy: 0.2609
Epoch 903/930
21/21 [==============================] - 4s 180ms/step - loss: -2717.7642 - accuracy: 0.2617 - val_loss: -239.6641 - val_accuracy: 0.2609
Epoch 904/930
21/21 [==============================] - 4s 179ms/step - loss: -2737.7688 - accuracy: 0.2617 - val_loss: -231.6599 - val_accuracy: 0.2609
Epoch 905/930
21/21 [==============================] - 4s 180ms/step - loss: -2680.0479 - accuracy: 0.2617 - val_loss: -254.8389 - val_accuracy: 0.2609
Epoch 906/930
21/21 [==============================] - 4s 181ms/step - loss: -2772.4700 - accuracy: 0.2617 - val_loss: -257.0055 - val_accuracy: 0.2609
Epoch 907/930
21/21 [==============================] - 4s 180ms/step - loss: -2782.5000 - accuracy: 0.2617 - val_loss: -265.4584 - val_accuracy: 0.2609
Epoch 908/930
21/21 [==============================] - 5s 180ms/step - loss: -2770.6917 - accuracy: 0.2617 - val_loss: -251.7032 - val_accuracy: 0.2609
Epoch 909/930
21/21 [==============================] - 4s 180ms/step - loss: -2803.9146 - accuracy: 0.2617 - val_loss: -259.5325 - val_accuracy: 0.2609
Epoch 910/930
21/21 [==============================] - 5s 181ms/step - loss: -2758.2053 - accuracy: 0.2617 - val_loss: -238.6848 - val_accuracy: 0.2609
Epoch 911/930
21/21 [==============================] - 5s 180ms/step - loss: -2833.7842 - accuracy: 0.2617 - val_loss: -276.1738 - val_accuracy: 0.2609
Epoch 912/930
21/21 [==============================] - 4s 182ms/step - loss: -2787.7236 - accuracy: 0.2617 - val_loss: -261.5335 - val_accuracy: 0.2609
Epoch 913/930
21/21 [==============================] - 4s 180ms/step - loss: -2821.8079 - accuracy: 0.2617 - val_loss: -264.4073 - val_accuracy: 0.2609
Epoch 914/930
21/21 [==============================] - 5s 180ms/step - loss: -2710.8860 - accuracy: 0.2617 - val_loss: -256.1047 - val_accuracy: 0.2609
Epoch 915/930
21/21 [==============================] - 4s 180ms/step - loss: -2835.1006 - accuracy: 0.2617 - val_loss: -279.8043 - val_accuracy: 0.2609
Epoch 916/930
21/21 [==============================] - 4s 181ms/step - loss: -2831.9131 - accuracy: 0.2617 - val_loss: -275.6079 - val_accuracy: 0.2609
Epoch 917/930
21/21 [==============================] - 5s 180ms/step - loss: -2855.0408 - accuracy: 0.2617 - val_loss: -244.4726 - val_accuracy: 0.2609
Epoch 918/930
21/21 [==============================] - 4s 181ms/step - loss: -2846.7678 - accuracy: 0.2617 - val_loss: -221.1270 - val_accuracy: 0.2609
Epoch 919/930
21/21 [==============================] - 4s 181ms/step - loss: -2797.4033 - accuracy: 0.2617 - val_loss: -265.7595 - val_accuracy: 0.2609
Epoch 920/930
21/21 [==============================] - 5s 182ms/step - loss: -2844.5571 - accuracy: 0.2617 - val_loss: -262.6353 - val_accuracy: 0.2609
Epoch 921/930
21/21 [==============================] - 4s 179ms/step - loss: -2890.9038 - accuracy: 0.2617 - val_loss: -292.8575 - val_accuracy: 0.2609
Epoch 922/930
21/21 [==============================] - 4s 180ms/step - loss: -2871.3188 - accuracy: 0.2617 - val_loss: -317.3295 - val_accuracy: 0.2609
Epoch 923/930
21/21 [==============================] - 5s 180ms/step - loss: -2836.7236 - accuracy: 0.2617 - val_loss: -308.8721 - val_accuracy: 0.2609
Epoch 924/930
21/21 [==============================] - 4s 180ms/step - loss: -2879.0256 - accuracy: 0.2617 - val_loss: -312.0043 - val_accuracy: 0.2609
Epoch 925/930
21/21 [==============================] - 4s 179ms/step - loss: -2869.4111 - accuracy: 0.2617 - val_loss: -324.9518 - val_accuracy: 0.2609
Epoch 926/930
21/21 [==============================] - 5s 180ms/step - loss: -2877.0371 - accuracy: 0.2617 - val_loss: -296.7602 - val_accuracy: 0.2609
Epoch 927/930
21/21 [==============================] - 4s 179ms/step - loss: -2896.8218 - accuracy: 0.2617 - val_loss: -308.5374 - val_accuracy: 0.2609
Epoch 928/930
21/21 [==============================] - 4s 182ms/step - loss: -2878.8062 - accuracy: 0.2617 - val_loss: -292.2719 - val_accuracy: 0.2609
Epoch 929/930
21/21 [==============================] - 5s 179ms/step - loss: -2834.8582 - accuracy: 0.2617 - val_loss: -295.4926 - val_accuracy: 0.2609
Epoch 930/930
21/21 [==============================] - 4s 179ms/step - loss: -2912.6504 - accuracy: 0.2617 - val_loss: -356.7943 - val_accuracy: 0.2609




  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

Exemplo de adição de imagem:
![Gráfico de Accuracy e loss](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABboAAAW/CAYAAABqrEWnAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjcuMSwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/bCgiHAAAACXBIWXMAAA9hAAAPYQGoP6dpAADDN0lEQVR4nOzdd5RV5d0+/GuGMjRBRKQoiiKxIigoQWPHYOOJJUawUCx5YuzERI2KigqJLdZo4oMlKtao0VgRSyxEjYixx4JioVgCCCpl5rx/+Do/R7oCw5bPZ629Fuc+9977u/cc95Jrbr6nrFQqlQIAAAAAAAVVXtsFAAAAAADAdyHoBgAAAACg0ATdAAAAAAAUmqAbAAAAAIBCE3QDAAAAAFBogm4AAAAAAApN0A0AAAAAQKEJugEAAAAAKDRBNwAAAAAAhSboBgBgngYMGJD27dt/q31PO+20lJWVLdmCljNvv/12ysrKcvXVVy/zc5eVleW0006rfn311VenrKwsb7/99kL3bd++fQYMGLBE6/kunxUAAFgSBN0AAAVTVla2SNsjjzxS26Wu8I466qiUlZXljTfemO+ck046KWVlZfn3v/+9DCtbfB988EFOO+20jB07trZLmadXXnklZWVladCgQaZMmVLb5QAAsIwJugEACubaa6+tse20007zHN9ggw2+03muuOKKvPbaa99q35NPPjmff/75dzr/98H++++fJBkxYsR859xwww3p1KlTNtlkk299ngMPPDCff/551lprrW99jIX54IMPcvrpp88z6P4un5Ul5brrrkvr1q2TJLfeemut1gIAwLJXt7YLAABg8RxwwAE1Xv/zn//MyJEj5xr/ps8++yyNGjVa5PPUq1fvW9WXJHXr1k3duv5Xs3v37ll33XVzww03ZPDgwXO9P3r06IwbNy6/+93vvtN56tSpkzp16nynY3wX3+WzsiSUSqWMGDEi++23X8aNG5frr78+hxxySK3WND8zZsxI48aNa7sMAIDvHSu6AQC+h7bbbrtsvPHGefbZZ7PNNtukUaNG+e1vf5sk+dvf/pbddtstbdu2TUVFRTp06JAzzjgjlZWVNY7xzb7LX/WkPvfcc/PnP/85HTp0SEVFRTbffPM888wzNfadV4/usrKyHHHEEbnjjjuy8cYbp6KiIhtttFHuu+++uep/5JFH0q1btzRo0CAdOnTIn/70p0Xu+/3YY49ln332yZprrpmKioq0a9cuxx577FwrzAcMGJAmTZrk/fffzx577JEmTZqkZcuWOe644+a6F1OmTMmAAQPSrFmzrLzyyunfv/8it8fYf//98+qrr2bMmDFzvTdixIiUlZWlb9++mTVrVgYPHpyuXbumWbNmady4cbbeeus8/PDDCz3HvHp0l0qlnHnmmVljjTXSqFGjbL/99nnppZfm2veTTz7Jcccdl06dOqVJkyZp2rRpdtlllzz//PPVcx555JFsvvnmSZKBAwdWt8f5qj/5vHp0z5gxI7/61a/Srl27VFRUZL311su5556bUqlUY97ifC7m54knnsjbb7+dPn36pE+fPvnHP/6R9957b655VVVVufDCC9OpU6c0aNAgLVu2zM4775x//etfNeZdd9112WKLLdKoUaM0b94822yzTR544IEaNX+9R/pXvtn//Kufy6OPPppf/vKXWW211bLGGmskSd5555388pe/zHrrrZeGDRumRYsW2WeffebZZ33KlCk59thj0759+1RUVGSNNdZIv3798tFHH2X69Olp3Lhxjj766Ln2e++991KnTp0MGzZsEe8kAEBxWWYDAPA99fHHH2eXXXZJnz59csABB6RVq1ZJvgzfmjRpkkGDBqVJkyZ56KGHMnjw4EybNi3nnHPOQo87YsSIfPrpp/nf//3flJWV5eyzz85ee+2Vt956a6Erex9//PHcdttt+eUvf5mVVlopF110Ufbee++MHz8+LVq0SJI899xz2XnnndOmTZucfvrpqayszJAhQ9KyZctFuu5bbrkln332WQ477LC0aNEiTz/9dC6++OK89957ueWWW2rMraysTK9evdK9e/ece+65efDBB3PeeeelQ4cOOeyww5J8GRj/5Cc/yeOPP55f/OIX2WCDDXL77benf//+i1TP/vvvn9NPPz0jRozIZpttVuPcN998c7beeuusueaa+eijj/J///d/6du3bw499NB8+umnGT58eHr16pWnn346Xbp0WaTzfWXw4ME588wzs+uuu2bXXXfNmDFj8uMf/zizZs2qMe+tt97KHXfckX322Sdrr712Jk2alD/96U/Zdttt8/LLL6dt27bZYIMNMmTIkAwePDg///nPs/XWWydJttxyy3meu1Qq5X/+53/y8MMP5+CDD06XLl1y//3359e//nXef//9/OEPf6gxf1E+Fwty/fXXp0OHDtl8882z8cYbp1GjRrnhhhvy61//usa8gw8+OFdffXV22WWXHHLIIZkzZ04ee+yx/POf/0y3bt2SJKeffnpOO+20bLnllhkyZEjq16+fp556Kg899FB+/OMfL/L9/7pf/vKXadmyZQYPHpwZM2YkSZ555pk8+eST6dOnT9ZYY428/fbbueyyy7Lddtvl5Zdfrv7XF9OnT8/WW2+dV155JQcddFA222yzfPTRR7nzzjvz3nvvpUuXLtlzzz1z00035fzzz6+xsv+GG25IqVSqbqEDAPC9VgIAoNAOP/zw0jf/t27bbbctJSldfvnlc83/7LPP5hr73//931KjRo1KX3zxRfVY//79S2uttVb163HjxpWSlFq0aFH65JNPqsf/9re/lZKU7rrrruqxU089da6akpTq169feuONN6rHnn/++VKS0sUXX1w91rt371KjRo1K77//fvXY66+/Xqpbt+5cx5yXeV3fsGHDSmVlZaV33nmnxvUlKQ0ZMqTG3E033bTUtWvX6td33HFHKUnp7LPPrh6bM2dOaeutty4lKV111VULrWnzzTcvrbHGGqXKysrqsfvuu6+UpPSnP/2p+pgzZ86ssd9///vfUqtWrUoHHXRQjfEkpVNPPbX69VVXXVVKUho3blypVCqVJk+eXKpfv35pt912K1VVVVXP++1vf1tKUurfv3/12BdffFGjrlLpy591RUVFjXvzzDPPzPd6v/lZ+eqenXnmmTXm/fSnPy2VlZXV+Aws6udifmbNmlVq0aJF6aSTTqoe22+//UqdO3euMe+hhx4qJSkdddRRcx3jq3v0+uuvl8rLy0t77rnnXPfk6/fxm/f/K2uttVaNe/vVz+VHP/pRac6cOTXmzutzOnr06FKS0l/+8pfqscGDB5eSlG677bb51n3//feXkpTuvffeGu9vsskmpW233Xau/QAAvo+0LgEA+J6qqKjIwIED5xpv2LBh9Z8//fTTfPTRR9l6663z2Wef5dVXX13ocffdd980b968+vVXq3vfeuuthe7bs2fPdOjQofr1JptskqZNm1bvW1lZmQcffDB77LFH2rZtWz1v3XXXzS677LLQ4yc1r2/GjBn56KOPsuWWW6ZUKuW5556ba/4vfvGLGq+33nrrGtdyzz33pG7dutUrvJMve2IfeeSRi1RP8mVf9ffeey//+Mc/qsdGjBiR+vXrZ5999qk+Zv369ZN82WLjk08+yZw5c9KtW7d5tj1ZkAcffDCzZs3KkUceWaPdyzHHHDPX3IqKipSXf/nXgsrKynz88cdp0qRJ1ltvvcU+71fuueee1KlTJ0cddVSN8V/96lcplUq59957a4wv7HOxIPfee28+/vjj9O3bt3qsb9++ef7552u0avnrX/+asrKynHrqqXMd46t7dMcdd6SqqiqDBw+uviffnPNtHHrooXP1UP/653T27Nn5+OOPs+6662bllVeucd//+te/pnPnztlzzz3nW3fPnj3Ttm3bXH/99dXvvfjii/n3v/+90N79AADfF4JuAIDvqdVXX706OP26l156KXvuuWeaNWuWpk2bpmXLltVh2NSpUxd63DXXXLPG669C7//+97+Lve9X+3+17+TJk/P5559n3XXXnWvevMbmZfz48RkwYEBWWWWV6r7b2267bZK5r++rPs3zqyf5spdymzZt0qRJkxrz1ltvvUWqJ0n69OmTOnXqZMSIEUmSL774Irfffnt22WWXGr80uOaaa7LJJpukQYMGadGiRVq2bJm77757kX4uX/fOO+8kSTp27FhjvGXLljXOl3wZqv/hD39Ix44dU1FRkVVXXTUtW7bMv//978U+79fP37Zt26y00ko1xjfYYIMa9X1lYZ+LBbnuuuuy9tprp6KiIm+88UbeeOONdOjQIY0aNaoR/L755ptp27ZtVllllfke680330x5eXk23HDDhZ53cay99tpzjX3++ecZPHhwdQ/zr+77lClTatz3N998MxtvvPECj19eXp79998/d9xxRz777LMkX7ZzadCgQfUvUgAAvu8E3QAA31NfXzH6lSlTpmTbbbfN888/nyFDhuSuu+7KyJEj8/vf/z7Jl6HnwnxzZepXSt/4ksElve+iqKyszE477ZS77747xx9/fO64446MHDmy+ksTv3l986tnSVtttdWy00475a9//Wtmz56du+66K59++mmN3snXXXddBgwYkA4dOmT48OG57777MnLkyOywww6L9HP5toYOHZpBgwZlm222yXXXXZf7778/I0eOzEYbbbRUz/t13/ZzMW3atNx1110ZN25cOnbsWL1tuOGG+eyzzzJixIgl9tlaFN/8EtOvzOu/xSOPPDJnnXVWfvazn+Xmm2/OAw88kJEjR6ZFixbf6r7369cv06dPzx133JFSqZQRI0Zk9913T7NmzRb7WAAAReTLKAEAViCPPPJIPv7449x2223ZZpttqsfHjRtXi1X9P6uttloaNGiQN954Y6735jX2TS+88EL+85//5Jprrkm/fv2qx0eOHPmta1prrbUyatSoTJ8+vcaq7tdee22xjrP//vvnvvvuy7333psRI0akadOm6d27d/X7t956a9ZZZ53cdtttNdpkzKvVxqLUnCSvv/561llnnerxDz/8cK5V0rfeemu23377DB8+vMb4lClTsuqqq1a/XpzWHWuttVYefPDBfPrppzVWdX/VGuer+r6r2267LV988UUuu+yyGrUmX/58Tj755DzxxBP50Y9+lA4dOuT+++/PJ598Mt9V3R06dEhVVVVefvnlBX75Z/PmzTNlypQaY7NmzcqECRMWufZbb701/fv3z3nnnVc99sUXX8x13A4dOuTFF19c6PE23njjbLrpprn++uuzxhprZPz48bn44osXuR4AgKKzohsAYAXy1crZr69ynTVrVv74xz/WVkk11KlTJz179swdd9yRDz74oHr8jTfemKuv8/z2T2peX6lUyoUXXvita9p1110zZ86cXHbZZdVjlZWVix0i7rHHHmnUqFH++Mc/5t57781ee+2VBg0aLLD2p556KqNHj17smnv27Jl69erl4osvrnG8Cy64YK65derUmWvV8y233JL333+/xljjxo2TZK4gdl523XXXVFZW5pJLLqkx/oc//CFlZWWL3G99Ya677rqss846+cUvfpGf/vSnNbbjjjsuTZo0qW5fsvfee6dUKuX000+f6zhfXf8ee+yR8vLyDBkyZK5V1V+/Rx06dKjRbz1J/vznP893Rfe8zOu+X3zxxXMdY++9987zzz+f22+/fb51f+XAAw/MAw88kAsuuCAtWrRYYvcZAKAIrOgGAFiBbLnllmnevHn69++fo446KmVlZbn22muXaXuHhTnttNPywAMPZKuttsphhx1WHZhuvPHGGTt27AL3XX/99dOhQ4ccd9xxef/999O0adP89a9/XaRez/PTu3fvbLXVVjnhhBPy9ttvZ8MNN8xtt9222P2rmzRpkj322KO6T/fX25Ykye67757bbrste+65Z3bbbbeMGzcul19+eTbccMNMnz59sc7VsmXLHHfccRk2bFh233337Lrrrnnuuedy7733zrXyeffdd8+QIUMycODAbLnllnnhhRdy/fXX11gJnnwZ7q688sq5/PLLs9JKK6Vx48bp3r37PPtP9+7dO9tvv31OOumkvP322+ncuXMeeOCB/O1vf8sxxxxT44snv60PPvggDz/88FxfePmVioqK9OrVK7fccksuuuiibL/99jnwwANz0UUX5fXXX8/OO++cqqqqPPbYY9l+++1zxBFHZN11181JJ52UM844I1tvvXX22muvVFRU5Jlnnknbtm0zbNiwJMkhhxySX/ziF9l7772z00475fnnn8/9998/171dkN133z3XXnttmjVrlg033DCjR4/Ogw8+mBYtWtSY9+tf/zq33npr9tlnnxx00EHp2rVrPvnkk9x55525/PLL07lz5+q5++23X37zm9/k9ttvz2GHHZZ69ep9izsLAFBMVnQDAKxAWrRokb///e9p06ZNTj755Jx77rnZaaedcvbZZ9d2adW6du2ae++9N82bN88pp5yS4cOHZ8iQIdlxxx1rrICel3r16uWuu+5Kly5dMmzYsJx++unp2LFj/vKXv3zresrLy3PnnXdm//33z3XXXZeTTjopq6++eq655prFPtZX4XabNm2yww471HhvwIABGTp0aJ5//vkcddRRuf/++3PdddelW7du36ruM888M6effnqee+65/PrXv86bb76ZBx54oHpl9ld++9vf5le/+lXuv//+HH300RkzZkzuvvvutGvXrsa8evXq5ZprrkmdOnXyi1/8In379s2jjz46z3N/dc+OOeaY/P3vf88xxxyTl19+Oeecc07OP//8b3U933TjjTemqqqqRvuXb+rdu3c+/vjj6n8NcNVVV+Wcc87JuHHj8utf/zpDhw7N559/ni233LJ6nyFDhuTKK6/M559/npNOOimDBw/OO++8kx133LF6zqGHHprjjz8+//jHP/KrX/0q48aNy8iRI+e6twty4YUXpl+/frn++uvzq1/9KhMmTMiDDz4415eeNmnSJI899lgOO+yw3HPPPTnqqKPyxz/+Meutt17WWGONGnNbtWqVH//4x0m+XN0NALAiKSstT8t3AABgPvbYY4+89NJLef3112u7FFhu7bnnnnnhhRcWqac9AMD3iRXdAAAsdz7//PMar19//fXcc8892W677WqnICiA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ABSaoBsAAAAAgEITdAMAAAAAUGiCbgAAAAAACk3QDQAAAABAoQm6AQAAAAAoNEE3AAAAAACFJugGAAAAAKDQaj3ovvTSS9O+ffs0aNAg3bt3z9NPP73A+RdccEHWW2+9NGzYMO3atcuxxx6bL774YhlVCwAAAADA8qZWg+6bbropgwYNyqmnnpoxY8akc+fO6dWrVyZPnjzP+SNGjMgJJ5yQU089Na+88kqGDx+em266Kb/97W+XceUAAAAAACwvajXoPv/883PooYdm4MCB2XDDDXP55ZenUaNGufLKK+c5/8knn8xWW22V/fbbL+3bt8+Pf/zj9O3bd6GrwAEAAAAA+P6qtaB71qxZefbZZ9OzZ8//V0x5eXr27JnRo0fPc58tt9wyzz77bHWw/dZbb+Wee+7JrrvuOt/zzJw5M9OmTauxAQAAAADw/VG3tk780UcfpbKyMq1ataox3qpVq7z66qvz3Ge//fbLRx99lB/96EcplUqZM2dOfvGLXyywdcmwYcNy+umnL9HaAQAAAABYftT6l1EujkceeSRDhw7NH//4x4wZMya33XZb7r777pxxxhnz3efEE0/M1KlTq7d33313GVYMAAAAAMDSVmsrulddddXUqVMnkyZNqjE+adKktG7dep77nHLKKTnwwANzyCGHJEk6deqUGTNm5Oc//3lOOumklJfPndtXVFSkoqJiyV8AAAAAAADLhVpb0V2/fv107do1o0aNqh6rqqrKqFGj0qNHj3nu89lnn80VZtepUydJUiqVll6xAAAAAAAst2ptRXeSDBo0KP3790+3bt2yxRZb5IILLsiMGTMycODAJEm/fv2y+uqrZ9iwYUmS3r175/zzz8+mm26a7t2754033sgpp5yS3r17VwfeAAAAAACsWGo16N53333z4YcfZvDgwZk4cWK6dOmS++67r/oLKsePH19jBffJJ5+csrKynHzyyXn//ffTsmXL9O7dO2eddVZtXQIAAAAAALWsrLSC9fyYNm1amjVrlqlTp6Zp06a1XQ4AAAAAAPOwOFlurfXoBgAAAACAJUHQDQAAAABAoQm6AQAAAAAoNEE3AAAAAACFJugGAAAAAKDQBN0AAAAAABSaoBsAAAAAgEITdAMAAAAAUGiCbgAAAAAACk3QDQAAAABAoQm6AQAAAAAoNEE3AAAAAACFJugGAAAAAKDQ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AAAAAAAW1WIH3RUVFZk0adJc4xMmTEjduovd8hsAAAAAAL6TxQ66f/zjH+fEE0/M1KlTq8emTJmS3/72t9lpp52WaHEAAAAAALAwi70E+9xzz80222yTtdZaK5tuummSZOzYsWnVqlWuvfbaJV4gAAAAAAAsyGIH3auvvnr+/e9/5/rrr8/zzz+fhg0bZuDAgenbt2/q1au3NGoEAAAAAID5+lZNtRs3bpyf//znS7oWAAAAAABYbN/62yNffvnljB8/PrNmzaox/j//8z/fuSgAAAAAAFhUix10v/XWW9lzzz3zwgsvpKysLKVSKUlSVlaWJKmsrFyyFQIAAAAAwAKUL+4ORx99dNZee+1Mnjw5jRo1yksvvZR//OMf6datWx555JGlUCIAAAAAAMzfYq/oHj16dB566KGsuuqqKS8vT3l5eX70ox9l2LBhOeqoo/Lcc88tjToBAAAAAGCeFntFd2VlZVZaaaUkyaqrrpoPPvggSbLWWmvltddeW7LVAQAAAADAQiz2iu6NN944zz//fNZee+107949Z599durXr58///nPWWeddZZGjQAAAAAAMF+LHXSffPLJmTFjRpJkyJAh2X333bP11lunRYsWuemmm5Z4gQAAAAAAsCBlpVKp9F0P8sknn6R58+YpKytbEjUtVdOmTUuzZs0yderUNG3atLbLAQAAAABgHhYny12sHt2zZ89O3bp18+KLL9YYX2WVVQoRcgMAAAAA8P2zWEF3vXr1suaaa6aysnJp1QMAAAAAAItlsYLuJDnppJPy29/+Np988snSqAcAAAAAABbLYn8Z5SWXXJI33ngjbdu2zVprrZXGjRvXeH/MmDFLrDgAAAAAAFiYxQ6699hjj6VQBgAAAAAAfDtlpVKpVNtFLEuL802dAAAAAADUjsXJche7RzcAAAAAACxPFrt1SXl5ecrKyub7fmVl5XcqCAAAAAAAFsdiB9233357jdezZ8/Oc889l2uuuSann376EisMAAAAAAAWxRLr0T1ixIjcdNNN+dvf/rYkDrfU6NENAAAAALD8q5Ue3T/84Q8zatSoJXU4AAAAAABYJEsk6P78889z0UUXZfXVV18ShwMAAAAAgEW22D26mzdvXuPLKEulUj799NM0atQo11133RItDgAAAAAAFmaxg+4//OEPNYLu8vLytGzZMt27d0/z5s2XaHEAAAAAALAwix10DxgwYCmUAQAAAAAA385i9+i+6qqrcsstt8w1fsstt+Saa65ZIkUBAAAAAMCiWuyge9iwYVl11VXnGl9ttdUydOjQJVIUAAAAAAAsqsUOusePH5+11157rvG11lor48ePXyJFAQAAAADAolrsoHu11VbLv//977nGn3/++bRo0WKJFAUAAAAAAItqsYPuvn375qijjsrDDz+cysrKVFZW5qGHHsrRRx+dPn36LI0aAQAAAABgvuou7g5nnHFG3n777ey4446pW/fL3auqqtKvXz89ugEAAAAAWObKSqVS6dvs+Prrr2fs2LFp2LBhOnXqlLXWWmtJ17ZUTJs2Lc2aNcvUqVPTtGnT2i4HAAAAAIB5WJwsd7Fbl3ylY8eO2WeffbL77rt/p5D70ksvTfv27dOgQYN07949Tz/99ALnT5kyJYcffnjatGmTioqK/OAHP8g999zzrc8PAAAAAECxLXbQvffee+f3v//9XONnn3129tlnn8U61k033ZRBgwbl1FNPzZgxY9K5c+f06tUrkydPnuf8WbNmZaeddsrbb7+dW2+9Na+99lquuOKKrL766ot7GQAAAAAAfE8sduuSli1b5qGHHkqnTp1qjL/wwgvp2bNnJk2atMjH6t69ezbffPNccsklSb7s9d2uXbsceeSROeGEE+aaf/nll+ecc87Jq6++mnr16i3SOWbOnJmZM2dWv542bVratWundQkAAAAAwHJsqbYumT59eurXrz/XeL169TJt2rRFPs6sWbPy7LPPpmfPnv+vmPLy9OzZM6NHj57nPnfeeWd69OiRww8/PK1atcrGG2+coUOHprKycr7nGTZsWJo1a1a9tWvXbpFrBAAAAABg+bfYQXenTp1y0003zTV+4403ZsMNN1zk43z00UeprKxMq1ataoy3atUqEydOnOc+b731Vm699dZUVlbmnnvuySmnnJLzzjsvZ5555nzPc+KJJ2bq1KnV27vvvrvINQIAAAAAsPyru7g7nHLKKdlrr73y5ptvZocddkiSjBo1KiNGjMitt966xAv8uqqqqqy22mr585//nDp16qRr1655//33c8455+TUU0+d5z4VFRWpqKhYqnUBAAAAAFB7Fjvo7t27d+64444MHTo0t956axo2bJjOnTvnoYceyiqrrLLIx1l11VVTp06duXp6T5o0Ka1bt57nPm3atEm9evVSp06d6rENNtggEydOzKxZs+bZUgUAAAAAgO+3xW5dkiS77bZbnnjiicyYMSNvvfVWfvazn+W4445L586dF/kY9evXT9euXTNq1KjqsaqqqowaNSo9evSY5z5bbbVV3njjjVRVVVWP/ec//0mbNm2E3AAAAAAAK6hvFXQnyT/+8Y/0798/bdu2zXnnnZcddtgh//znPxfrGIMGDcoVV1yRa665Jq+88koOO+ywzJgxIwMHDkyS9OvXLyeeeGL1/MMOOyyffPJJjj766PznP//J3XffnaFDh+bwww//tpcBAAAAAEDBLVbrkokTJ+bqq6/O8OHDM23atPzsZz/LzJkzc8cddyzWF1F+Zd99982HH36YwYMHZ+LEienSpUvuu+++6i+oHD9+fMrL/18W365du9x///059thjs8kmm2T11VfP0UcfneOPP36xzw0AAAAAwPdDWalUKi3KxN69e+cf//hHdtttt+y///7ZeeedU6dOndSrVy/PP//8twq6a8O0adPSrFmzTJ06NU2bNq3tcgAAAAAAmIfFyXIXeUX3vffem6OOOiqHHXZYOnbs+J2LBAAAAACAJWGRe3Q//vjj+fTTT9O1a9d07949l1xyST766KOlWRsAAAAAACzUIgfdP/zhD3PFFVdkwoQJ+d///d/ceOONadu2baqqqjJy5Mh8+umnS7NOAAAAAACYp0Xu0T0vr732WoYPH55rr702U6ZMyU477ZQ777xzSda3xOnRDQAAAACw/FucLHeRV3TPy3rrrZezzz477733Xm644YbvcigAAAAAAPhWvtOK7iKyohsAAAAAYPm3zFZ0AwAAAABAbRN0AwAAAABQaIJuAAAAAAAKTdANAAAAAEChCboBAAAAACg0QTcAAAAAAIUm6AYAAAAAoNAE3QAAAAAAFJqgGwAAAACAQhN0AwAAAABQaIJuAAAAAAAKTdANAAAAAEChCboBAAAAACg0QTcAAAAAAIUm6AYAAAAAoNAE3QAAAAAAFJqgGwAAAACAQhN0AwAAAABQaIJuAAAAAAAKTdANAAAAAEChCboBAAAAACg0QTcAAAAAAIUm6AYAAAAAoNAE3QAAAAAAFJqgGwAAAACAQhN0AwAAAABQaIJuAAAAAAAKTdANAAAAAEChCboBAAAAACg0QTcAAAAAAIUm6AYAAAAA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1FFHZeWVV06LFi1y/PHHp3///tljjz0Wet3Dhw/PfvvtlwMPPDBXXnnlXO+/99576du3b1ZZZZU0btw43bp1y1NPPVX9/l133ZXNN988DRo0yKqrrpo999yzxrXecccdNY638sor5+qrr06SvP322ykrK8tNN92UbbfdNg0aNMj111+fjz/+OH379s3qq6+eRo0apVOnTrnhhhtqHKeqqipnn3121l133VRUVGTNNdfMWWedlSTZYYcdcsQRR9SY/+GHH6Z+/foZNWrUQu/Jslarvy756KOPUllZmVatWtUYb9WqVV599dX57jd16tSsvvrqmTlzZurUqZM//vGP2WmnneY5d9iwYTn99NOXaN0AAAAAsKx9PrsyGw6unfa9Lw/plUb1l0yUeMIJJ+Tcc8/NOuusk+bNm+fdd9/NrrvumrPOOisVFRX5y1/+kt69e+e1117LmmuuOd/jnH766Tn77LNzzjnn5OKLL87++++fd955J6ussso853/22Wc599xzc+2116a8vDwHHHBAjjvuuFx//fVJkt///ve5/vrrc9VVV2WDDTbIhRdemDvuuCPbb7/9Aq/n008/zS233JKnnnoq66+/fqZOnZrHHnssW2+9dZJk+vTp2XbbbbP66qvnzjvvTOvWrTNmzJhUVVUlSe6+++7sueeeOemkk/KXv/wls2bNyj333POt7ut5552XTTfdNA0aNMgXX3yRrl275vjjj0/Tpk1z991358ADD0yHDh2yxRZbJElOPPHEXHHFFfnDH/6QH/3oR5kwYUJ1LnvIIYfkiCOOyHnnnZeKiookyXXXXZfVV189O+yww2LXt7QV8t8FrLTSShk7dmymT5+eUaNGZdCgQVlnnXWy3XbbzTX3xBNPzKBBg6pfT5s2Le3atVuG1QIAAAAAXxkyZEiNRaurrLJKOnfuXP36jDPOyO23354777xzrhXFXzdgwID07ds3STJ06NBcdNFFefrpp7PzzjvPc/7s2bNz+eWXp0OHDkmSI444IkOGDKl+/+KLL86JJ55YvZr6kksuWaTA+cYbb0zHjh2z0UYbJUn69OmT4cOHVwfdI0aMyIcffphnnnmmOoRfd911q/c/66yz0qdPnxqLdb9+PxbVMccck7322qvG2HHHHVf95yOPPDL3339/br755myxxRb59NNPc+GFF+aSSy5J//79kyQdOnTIj370oyTJXnvtlSOOOCJ/+9vf8rOf/SzJlyvjBwwYkLKyssWub2mr1aB71VVXTZ06dTJp0qQa45MmTUrr1q3nu195eXn1h6FLly555ZVXMmzYsHkG3RUVFdW/cQAAAACAompYr05eHtKr1s69pHTr1q3G6+nTp+e0007L3XffnQkTJmTOnDn5/PPPM378+AUeZ5NNNqn+c+PGjdO0adNMnjx5vvMbNWpUHXInSZs2barnT506NZMmTape6ZwkderUSdeuXatXXs/PlVdemQMOOKD69QEHHJBtt902F198cfWC3U033XS+K83Hjh2bQw89dIHnWBTfvK+VlZUZOnRobr755rz//vuZNWtWZs6cmUaNGiVJXnnllcycOTM77rjjPI/XoEGD6lYsP/vZzzJmzJi8+OKLNVrELE9qNeiuX79+unbtmlGjRlX3uqmqqsqoUaMW+Nuab6qqqsrMmTOXUpUAAAAAUPvKysqWWPuQ2tS4ceMar4877riMHDky5557btZdd900bNgwP/3pTzNr1qwFHuebX7ZYVla2wFB6XvMXtff4/Lz88sv55z//maeffrrGF1BWVlbmxhtvzKGHHpqGDRsu8BgLe39edc6ePXuued+8r+ecc04uvPDCXHDBBenUqVMaN26cY445pvq+Luy8yZftS7p06ZL33nsvV111VXbYYYestdZaC92vNtTql1EmyaBBg3LFFVfkmmuuySuvvJLDDjssM2bMyMCBA5Mk/fr1y4knnlg9f9iwYRk5cmTeeuutvPLKKznvvPNy7bXX1vitCQAAAABQDE888UQGDBiQPffcM506dUrr1q3z9ttvL9MamjVrllatWuWZZ56pHqusrMyYMWMWuN/w4cOzzTbb5Pnnn8/YsWOrt0GDBmX48OFJvlx5Pnbs2HzyySfzPMYmm2yywC93bNmyZY0vzXz99dfz2WefLfSannjiifzkJz/JAQcckM6dO2edddbJf/7zn+r3O3bsmIYNGy7w3J06dUq3bt1yxRVXZMSIETnooIMWet7aUuu/Atp3333z4YcfZvDgwZk4cWK6dOmS++67r/oLKsePH5/y8v+Xx8+YMSO//OUv895776Vhw4ZZf/31c91112XfffetrUsAAAAAAL6ljh075rbbbkvv3r1TVlaWU045ZaHtQpaGI488MsOGDcu6666b9ddfPxdffHH++9//zrcf9ezZs3PttddmyJAh2XjjjWu8d8ghh+T888/PSy+9lL59+2bo0KHZY489MmzYsLRp0ybPPfdc2rZtmx49euTUU0/NjjvumA4dOqRPnz6ZM2dO7rnnnuoV4jvssEMuueSS9OjRI5WVlTn++OPnWp0+Lx07dsytt96aJ598Ms2bN8/555+fSZMmZcMNN0zyZWuS448/Pr/5zW9Sv379bLXVVvnwww/z0ksv5eCDD65xLUcccUQaN25c3b98eVTrK7qTLxu/v/POO5k5c2aeeuqpdO/evfq9Rx55JFdffXX16zPPPDOvv/56Pv/883zyySd58sknhdwAAAAAUFDnn39+mjdvni233DK9e/dOr169stlmmy3zOo4//vj07ds3/fr1S48ePdKkSZP06tUrDRo0mOf8O++8Mx9//PE8w98NNtggG2ywQYYPH5769evngQceyGqrrZZdd901nTp1yu9+97vUqfNl3/Ptttsut9xyS+6888506dIlO+ywQ55++unqY5133nlp165dtt566+y333457rjjqvtsL8jJJ5+czTbbLL169cp2222X1q1bV7eP/sopp5ySX/3qVxk8eHA22GCD7LvvvnP1Oe/bt2/q1q2bvn37zvdeLA/KSt+1EU3BTJs2Lc2aNcvUqVPTtGnT2i4HAAAAAObpiy++yLhx47L22msv1wHj91VVVVU22GCD/OxnP8sZZ5xR2+XUmrfffjsdOnTIM888s1R+AbGgz/niZLm13roEAAAAAKC2vfPOO3nggQey7bbbZubMmbnkkksybty47LfffrVdWq2YPXt2Pv7445x88sn54Q9/WCur7BfHctG6BAAAAACgNpWXl+fqq6/O5ptvnq222iovvPBCHnzwwWywwQa1XVqteOKJJ9KmTZs888wzufzyy2u7nIWyohsAAAAAWOG1a9cuTzzxRG2XsdzYbrvtUqSu11Z0AwAAAABQaIJuAAAAAAAKTdANAAAAAEChCboBAAAAACg0QTcAAAAAAIUm6AYAAAAAoNAE3QAAAADAcmW77bbLMcccU/26ffv2ueCCCxa4T1lZWe64447vfO4ldRyWLUE3AAAAALBE9O7dOzvvvPM833vsscdSVlaWf//734t93GeeeSY///nPv2t5NZx22mnp0qXLXOMTJkzILrvsskTPNT+ff/55Vllllay66qqZOXPmMjnn95WgGwAAAABYIg4++OCMHDky77333lzvXXXVVenWrVs22WSTxT5uy5Yt06hRoyVR4kK1bt06FRUVy+Rcf/3rX7PRRhtl/fXXr/VV5KVSKXPmzKnVGr4LQTcAAAAAFEGplMyaUTtbqbRIJe6+++5p2bJlrr766hrj06dPzy233JKDDz44H3/8cfr27ZvVV189jRo1SqdOnXLDDTcs8LjfbF3y+uuvZ5tttkmDBg2y4YYbZuTIkXPtc/zxx+cHP/hBGjVqlHXWWSennHJKZs+enSS5+uqrc/rpp+f5559PWVlZysrKqmv+ZuuSF154ITvssEMaNmyYFi1a5Oc//3mmT59e/f6AAQOyxx575Nxzz02bNm3SokWLHH744dXnWpDhw4fngAMOyAEHHJDhw4fP9f5LL72U3XffPU2bNs1KK62UrbfeOm+++Wb1+1deeWU22mijVFRUpE2bNjniiCOSJG+//XbKysoyduzY6rlTpkxJWVlZHnnkkSTJI488krKystx7773p2rVrKioq8vjjj+fNN9/MT37yk7Rq1SpNmjTJ5ptvngcffLBGXTNnzszxxx+fdu3apaKiIuuuu26GDx+eUqmUddddN+eee26N+WPHjk1ZWVneeOONhd6Tb6vuUjsyAAAAALDkzP4sGdq2ds792w+S+o0XOq1u3brp169frr766px00kkpKytLktxyyy2prKxM3759M3369HTt2jXHH398mjZtmrvvvjsHHnhgOnTokC222GKh56iqqspee+2VVq1a5amnnsrUqVNr9PP+ykorrZSrr746bdu2zQsvvJBDDz00K620Un7zm99k3333zYsvvpj77ruvOsRt1qzZXMeYMWNGevXqlR49euSZZ57J5MmTc8ghh+SII46oEeY//PDDadOmTR5++OG88cYb2XfffdOlS5cceuih872ON998M6NHj85tt92WUqmUY489Nu+8807WWmutJMn777+fbbbZJtttt10eeuihNG3aNE888UT1quvLLrssgwYNyu9+97vssssumTp1ap544omF3r9vOuGEE3LuuedmnXXWSfPmzfPuu+9m1113zVlnnZWKior85S9/Se/evfPaa69lzTXXTJL069cvo0ePzkUXXZTOnTtn3Lhx+eijj1JWVpaDDjooV111VY477rjqc1x11VXZZpttsu666y52fYtK0A0AAAAALDEHHXRQzjnnnDz66KPZbrvtknwZdO69995p1qxZmjVrViMEPfLII3P//ffn5ptvXqSg+8EHH8yrr76a+++/P23bfhn8Dx06dK6+2ieffHL1n9u3b5/jjjsuN954Y37zm9+kYcOGadKkSerWrZvWrVvP91wjRozIF198kb/85S9p3PjLoP+SSy5J79698/vf/z6tWrVKkjRv3jyXXHJJ6tSpk/XXXz+77bZbRo0atcCg+8orr8wuu+yS5s2bJ0l69eqVq666KqeddlqS5NJLL02zZs1y4403pl69ekmSH/zgB9X7n3nmmfnVr36Vo48+unps8803X+j9+6YhQ4Zkp512qn69yiqrpHPnztWvzzjjjNx+++258847c8QRR+Q///lPbr755owcOTI9e/ZMkqyzzjrV8wcMGJDBgwfn6aefzhZbbJHZs2dnxIgRc63yXtIE3QAAAABQBPUafbmyurbOvYjWX3/9bLnllrnyyiuz3Xbb5Y033shjjz2WIUOGJEkqKyszdOjQ3HzzzXn//fcza9aszJw5c5F7cL/yyitp165ddcidJD169Jhr3k033ZSLLroob775ZqZPn545c+akadOmi3wdX52rc+fO1SF3kmy11VapqqrKa6+9Vh10b7TRRqlTp071nDZt2uSFF16Y73ErKytzzTXX5MILL6weO+CAA3Lcccdl8ODBKS8vz9ixY7P11ltXh9xfN3ny5HzwwQfZcccdF+t65qVbt241Xk+fPj2nnXZa7r777kyYMCFz5szJ559/nvHjxyf5sg1JnTp1su22287zeG3bts1uu+2WK6+8MltssUXuuuuuzJw5M/vss893rnVB9OgGAAAAgCIoK/uyfUhtbP9/C5JFdfDBB+evf/1rPv3001x11VXp0KFDdTB6zjnn5MILL8zxxx+fhx9+OGPHjk2vXr0ya9asJXarRo8enf333z+77rpr/v73v+e5557LSSedtETP8XXfDKPLyspSVVU13/n3339/3n///ey7776pW7du6tatmz59+uSdd97JqFGjkiQNGzac7/4Lei9Jysu/jH1LX+utPr+e4V8P8ZPkuOOOy+23356hQ4fmsccey9ixY9OpU6fqe7ewcyfJIYcckhtvvDGff/55rrrqquy7775L/ctEBd0AAAAAwBL1s5/9LOXl5RkxYkT+8pe/5KCDDqru1/3EE0/kJz/5SQ444IB07tw566yzTv7zn/8s8rE32GCDvPvuu5kwYUL12D//+c8ac5588smstdZaOemkk9KtW7d07Ngx77zzTo059evXT2Vl5ULP9fzzz2fGjBnVY0888UTKy8uz3nrrLXLN3zR8+PD06dMnY8eOrbH16dOn+kspN9lkkzz22GPzDKhXWmmltG/fvjoU/6aWLVsmSY179PUvplyQJ554IgMGDMiee+6ZTp06pXXr1nn77ber3+/UqVOqqqry6KOPzvcYu+66axo3bpzLLrss9913Xw466KBFOvd3IegGAAAAAJaoJk2aZN99982JJ56YCRMmZMCAAdXvdezYMSNHjsyTTz6ZV155Jf/7v/+bSZMmLfKxe/bsmR/84Afp379/nn/++Tz22GM56aSTaszp2LFjxo8fnxtvvDFvvvlmLrrootx+++015rRv3z7jxo3L2LFj89FHH2XmzJlznWv//fdPgwYN0r9//7z44ot5+OGHc+SRR+bAAw+sbluyuD788MPcdddd6d+/fzbeeOMaW79+/XLHHXfkk08+yRFHHJFp06alT58++de//pXXX3891157bV577bUkyWmnnZbzzjsvF110UV5//fWMGTMmF198cZIvV13/8Ic/zO9+97u88sorefTRR2v0LF+Qjh075rbbbsvYsWPz/PPPZ7/99quxOr19+/bp379/DjrooNxxxx0ZN25cHnnkkdx8883Vc+rUqZMBAwbkxBNPTMeOHefZWmZJE3QDAAAAAEvcwQcfnP/+97/p1atXjX7aJ598cjbbbLP06tUr2223XVq3bp099thjkY9bXl6e22+/PZ9//nm22GKLHHLIITnrrLNqzPmf//mfHHvssTniiCPSpUuXPPnkkznllFNqzNl7772z8847Z/vtt0/Lli1zww03zHWuRo0a5f77788nn3ySzTffPD/96U+z44475pJLLlm8m/E1X32x5bz6a++4445p2LBhrrvuurRo0SIPPfRQpk+fnm233TZdu3bNFVdcUd0mpX///rngggvyxz/+MRtttFF23333vP7669XHuvLKKzNnzpx07do1xxxzTM4888xFqu/8889P8+bNs+WWW6Z3797p1atXNttssxpzLrvssvz0pz/NL3/5y6y//vo59NBDa6x6T778+c+aNSsDBw5c3Fv0rZSVvt6oZQUwbdq0NGvWLFOnTl3s5vMAAAAAsKx88cUXGTduXNZee+00aNCgtsuBxfLYY49lxx13zLvvvrvA1e8L+pwvTpZbd4lUDQAAAADACm/mzJn58MMPc9ppp2Wfffb51i1eFpfWJQAAAAAALBE33HBD1lprrUyZMiVnn332MjuvFd0rqNmVVbnwwdcz+dMvarsUAAAAAOZhpXql7LhGWRpO+Tx161ctfAe+t8rLy9J25Ya1XcYiGTBgQI0vH11WBN0rokfPTunxS3LorNm1XQkAAAAA8zGryRqZvNrQrDqzlAaVZbVdDrWosqxOsvLGtV3Gck3QvSJ6+s+pP3tq6ns+AgAAACy3vshn+ShVqZOq1C0T5KzIyr/HP/9SqbREjiPoXtHM+DiZ8WGSZOeZv8u5fTfPxm1Xrt2aAAAAAJhLncqq5MMvMmultmm4UpPaLoda9H0OumfNmpUkqVOnznc6jqB7RfPhK0mSd6taZlLDDtlg465J+ff3PxQAAACAoqpbKqXRF+Pz4SdTUq9Bo5SXl9d2SdSaUjLn+/dde1VVVfnwww/TqFGj1K373aJqQfeKZvKXQfd/Smtk2x+0TB0hNwAAAMByqaysLG3atMm4cePyzjvv1HY5sFSUl5dnzTXXTNl3XLUu6F7BzJn0Suomeb20RrZff7XaLgcAAACABahfv346duxY3d4Bvm/q16+/RP61gqB7BTPxjeeyRpJJFe3Tb8NWtV0OAAAAAAtRXl6eBg0a1HYZsFzT2GcF8sGUz9NoyutJku223jaN6vs9BwAAAABQfILuFcgdj4/NKmWfpipl2WbLLWu7HAAAAACAJULQvQL5xQZf9nKas1K7lNVvXMvVAAAAAAAsGStc74pSqZQkmTZtWi1XUgveeT6ZWUrW+EG+WBGvHwAAAAAojK8y3K8y3QUpKy3KrO+R9957L+3atavtMgAAAAAAWATvvvtu1lhjjQXOWeGC7qqqqnzwwQdZaaWVUlZWVtvlLHPTpk1Lu3bt8u6776Zp06a1XQ7AYvMcA4rOcwwoOs8xoOg8x4qjVCrl008/Tdu2bVNevuAu3Ctc65Ly8vKFpv8rgqZNm/oPGSg0zzGg6DzHgKLzHAOKznOsGJo1a7ZI83wZJQAAAAAAhSboBgAAAACg0ATdK5iKioqceuqpqaioqO1SAL4VzzGg6DzHgKLzHAOKznPs+2mF+zJKAAAAAAC+X6zoBgAAAACg0ATdAAAAAAAUmqAbAAAAAIBCE3QDAAAAAFBogu4VyKWXXpr27dunQYMG6d69e55++unaLgkgSTJs2LBsvvnmWWmllbLaaqtljz32yGuvvVZjzhdffJHDDz88LVq0SJMmTbL33ntn0qRJNeaMHz8+u+22Wxo1apTVVlstv/71rzNnzpxleSkA+d3vfpeysrIcc8wx1WOeYcDy7v33388BBxyQFi1apGHDhunUqVP+9a9/Vb9fKpUyePDgtGnTJg0bNkzPnj3z+uuv1zjGJ598kv333z9NmzbNyiuvnIMPPjjTp09f1pcCrIAqKytzyimnZO21107Dhg3ToUOHnHHGGSmVStVzPMe+/wTdK4ibbropgwYNyqmnnpoxY8akc+fO6dWrVyZPnlzbpQHk0UcfzeGHH55//vOfGTlyZGbPnp0f//jHmTFjRvWcY489NnfddVduueWWPProo/nggw+y1157Vb9fWVmZ3XbbLbNmzcqTTz6Za665JldffXUGDx5cG5cErKCeeeaZ/OlPf8omm2xSY9wzDFie/fe//81WW22VevXq5d57783LL7+c8847L82bN6+ec/bZZ+eiiy7K5ZdfnqeeeiqNGzdOr1698sUXX1TP2X///fPSSy9l5MiR+fvf/55//OMf+fnPf14blwSsYH7/+9/nsssuyyWXXJJXXnklv//973P22Wfn4osvrp7jObYCKLFC2GKLLUqHH3549evKyspS27ZtS8OGDavFqgDmbfLkyaUkpUcffbRUKpVKU6ZMKdWrV690yy23VM955ZVXSklKo0ePLpVKpdI999xTKi8vL02cOLF6zmWXXVZq2rRpaebMmcv2AoAV0qefflrq2LFjaeTIkaVtt922dPTRR5dKJc8wYPl3/PHHl370ox/N9/2qqqpS69atS+ecc0712JQpU0oVFRWlG264oVQqlUovv/xyKUnpmWeeqZ5z7733lsrKykrvv//+0iseoFQq7bbbbqWDDjqoxthee+1V2n///UulkufYisKK7hXArFmz8uyzz6Znz57VY+Xl5enZs2dGjx5di5UBzNvUqVOTJKusskqS5Nlnn83s2bNrPMfWX3/9rLnmmtXPsdGjR6dTp05p1apV9ZxevXpl2rRpeemll5Zh9cCK6vDDD89uu+1W41mVeIYBy78777wz3bp1yz777JPVVlstm266aa644orq98eNG5eJEyfWeI41a9Ys3bt3r/EcW3nlldOtW7fqOT179kx5eXmeeuqpZXcxwAppyy23zKhRo/Kf//wnSfL888/n8ccfzy677JLEc2xFUbe2C2Dp++ijj1JZWVnjL05J0qpVq7z66qu1VBXAvFVVVeWYY47JVlttlY033jhJMnHixNSvXz8rr7xyjbmtWrXKxIkTq+fM6zn31XsAS9ONN96YMWPG5JlnnpnrPc8wYHn31ltv5bLLLsugQYPy29/+Ns8880yOOuqo1K9fP/37969+Ds3rOfX159hqq61W4/26detmlVVW8RwDlroTTjgh06ZNy/rrr586deqksrIyZ511Vvbff/8k8RxbQQi6AViuHH744XnxxRfz+OOP13YpAIvk3XffzdFHH52RI0emQYMGtV0OwGKrqqpKt27dMnTo0CTJpptumhdffDGXX355+vfvX8vVASzczTffnOuvvz4jRozIRhttlLFjx+aYY45J27ZtPcdWIFqXrABWXXXV1KlTJ5MmTaoxPmnSpLRu3bqWqgKY2xFHHJG///3vefjhh7PGGmtUj7du3TqzZs3KlClTasz/+nOsdevW83zOffUewNLy7LPPZvLkydlss81St27d1K1bN48++mguuuii1K1bN61atfIMA5Zrbdq0yYYbblhjbIMNNsj48eOT/L/n0IL+Ttm6detMnjy5xvtz5szJJ5984jkGLHW//vWvc8IJJ6RPnz7p1KlTDjzwwBx77LEZNmxYEs+xFYWgewVQv379dO3aNaNGjaoeq6qqyqhRo9KjR49arAzgS6VSKUcccURuv/32PPTQQ1l77bVrvN+1a9fUq1evxnPstddey/jx46ufYz169MgLL7xQ439MRo4cmaZNm871FzeAJWnHHXfMCy+8kLFjx1Zv3bp1y/7771/9Z88wYHm21VZb5bXXXqsx9p///CdrrbVWkmTttddO69atazzHpk2blqeeeqrGc2zKlCl59tlnq+c89NBDqaqqSvfu3ZfBVQArss8++yzl5TVjzjp16qSqqiqJ59iKQuuSFcSgQYPSv3//dOvWLVtssUUuuOCCzJgxIwMHDqzt0gBy+OGHZ8SIEfnb3/6WlVZaqbr/WbNmzdKwYcM0a9YsBx98cAYNGpRVVlklTZs2zZFHHpkePXrkhz/8YZLkxz/+cTbccMMceOCBOfvsszNx4sScfPLJOfzww1NRUVGblwd8z6200krV3ynwlcaNG6dFixbV455hwPLs2GOPzZZbbpmhQ4fmZz/7WZ5++un8+c9/zp///OckSVlZWY455piceeaZ6dixY9Zee+2ccsopadu2bfbYY48kX64A33nnnXPooYfm8ssvz+zZs3PEEUekT58+adu2bS1eHbAi6N27d84666ysueaa2WijjfLcc8/l/PPPz0EHHZTEc2yFUWKFcfHFF5fWXHPNUv369UtbbLFF6Z///GdtlwRQKpVKpSTz3K666qrqOZ9//nnpl7/8Zal58+alRo0alfbcc8/ShAkTahzn7bffLu2yyy6lhg0bllZdddXSr371q9Ls2bOX8dUAlErbbrtt6eijj65+7RkGLO/uuuuu0sYbb1yqqKgorb/++qU///nPNd6vqqoqnXLKKaVWrVqVKioqSjvuuGPptddeqzHn448/LvXt27fUpEmTUtOmTUsDBw4sffrpp8vyMoAV1LRp00pHH310ac011yw1aNCgtM4665ROOumk0syZM6vneI59/5WVSqVSbQbtAAAAAADwXejRDQAAAABAoQm6AQAAAAAoNEE3AAAAAACFJugGAAAAAKDQBN0AAAAAABSaoBsAAAAAgEITdAMAAAAAUGiCbgAAAAAACk3QDQAAAABAoQm6AQAAAAAoNEE3AAAAAACFJugG4P9j797jrKrr/Y+/hwEGEGdARUBFUURFRVRQDnq8HTG8hGGeNA8p4K0Mr6h5S7yVVGaZl0StsE6RZqldVBRJrczyQhgqmiaKmYA3GAXlMrN/f/hznyYQGBwYFjyfj8c8Dnvt79rrs3HOfuSr1XcDAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AwCo3fPjwdO/efaXOvfjii1NRUdG0A61hXnrppVRUVOTmm29e7deuqKjIxRdfXH588803p6KiIi+99NJyz+3evXuGDx/epPN8nN8VAADWXUI3AMA6rKKiYoV+HnzwweYedZ136qmnpqKiIi+88MJHrrngggtSUVGRv/71r6txssb75z//mYsvvjhTpkxp7lHKPvwvG775zW829ygAAKyEls09AAAAzed///d/Gzz+0Y9+lIkTJy5xvFevXh/rOjfddFPq6+tX6twvf/nLOffccz/W9dcGQ4cOzTXXXJPx48dn9OjRS13z05/+NL17985OO+200tc5+uij89nPfjZVVVUr/RrL889//jOXXHJJunfvnp133rnBcx/ndwUAgHWX0A0AsA773Oc+1+Dxn/70p0ycOHGJ4/9u/vz5adeu3Qpfp1WrVis1X5K0bNkyLVv6j639+/fP1ltvnZ/+9KdLDd2PPPJIpk+fnq997Wsf6zqVlZWprKz8WK/xcXyc3xUAANZdti4BAGCZ9t133+y444554oknsvfee6ddu3Y5//zzkyS//OUvc8ghh2STTTZJVVVVevTokcsuuyx1dXUNXuPf913+120ibrzxxvTo0SNVVVXZbbfd8thjjzU4d2l7dFdUVOTkk0/OnXfemR133DFVVVXZYYcdMmHChCXmf/DBB9OvX7+0adMmPXr0yA033LDC+37//ve/z2c+85lsvvnmqaqqSrdu3XLGGWfkvffeW+L9tW/fPq+++mqGDBmS9u3bp1OnTjnrrLOW+LuYM2dOhg8fnpqamnTo0CHDhg3LnDlzljtL8sFd3c8++2wmT568xHPjx49PRUVFjjrqqCxcuDCjR49O3759U1NTk/XWWy977bVXHnjggeVeY2l7dJdKpXzlK1/JZpttlnbt2mW//fbL008/vcS5b731Vs4666z07t077du3T3V1dQ466KA8+eST5TUPPvhgdttttyTJiBEjytvjfLg/+dL26J43b17OPPPMdOvWLVVVVdl2223zzW9+M6VSqcG6xvxerKzZs2fnuOOOS+fOndOmTZv06dMnP/zhD5dYd8stt6Rv375Zf/31U11dnd69e+c73/lO+flFixblkksuSc+ePdOmTZtsuOGG+c///M9MnDixyWYFAFiXuDUGAIDlevPNN3PQQQfls5/9bD73uc+lc+fOST6Iou3bt8+oUaPSvn37/Pa3v83o0aNTW1ubK664YrmvO378+Lzzzjv5/Oc/n4qKinzjG9/Ipz/96bz44ovLvbP3D3/4Q26//fZ88YtfzPrrr5+rr746hx9+eGbMmJENN9wwSfKXv/wlBx54YLp27ZpLLrkkdXV1ufTSS9OpU6cVet+33XZb5s+fn5NOOikbbrhhHn300VxzzTX5xz/+kdtuu63B2rq6ugwaNCj9+/fPN7/5zdx///258sor06NHj5x00klJPgjGn/rUp/KHP/whX/jCF9KrV6/ccccdGTZs2ArNM3To0FxyySUZP358dt111wbX/tnPfpa99torm2++ed54441873vfy1FHHZUTTjgh77zzTr7//e9n0KBBefTRR5fYLmR5Ro8ena985Ss5+OCDc/DBB2fy5Mn5xCc+kYULFzZY9+KLL+bOO+/MZz7zmWy55ZaZNWtWbrjhhuyzzz555plnsskmm6RXr1659NJLM3r06Jx44onZa6+9kiR77LHHUq9dKpVy6KGH5oEHHshxxx2XnXfeOffee2/OPvvsvPrqq/n2t7/dYP2K/F6srPfeey/77rtvXnjhhZx88snZcsstc9ttt2X48OGZM2dOTjvttCTJxIkTc9RRR2X//ffP17/+9STJtGnT8vDDD5fXXHzxxRkzZkyOP/747L777qmtrc3jjz+eyZMn54ADDvhYcwIArJNKAADw/40cObL07/8RcZ999iklKY0dO3aJ9fPnz1/i2Oc///lSu3btSu+//3752LBhw0pbbLFF+fH06dNLSUobbrhh6a233iof/+Uvf1lKUvr1r39dPnbRRRctMVOSUuvWrUsvvPBC+diTTz5ZSlK65ppryscGDx5cateuXenVV18tH3v++edLLVu2XOI1l2Zp72/MmDGlioqK0ssvv9zg/SUpXXrppQ3W7rLLLqW+ffuWH995552lJKVvfOMb5WOLFy8u7bXXXqUkpXHjxi13pt1226202Wablerq6srHJkyYUEpSuuGGG8qvuWDBggbnvf3226XOnTuXjj322AbHk5Quuuii8uNx48aVkpSmT59eKpVKpdmzZ5dat25dOuSQQ0r19fXldeeff34pSWnYsGHlY++//36DuUqlD/5ZV1VVNfi7eeyxxz7y/f7778qHf2df+cpXGqz77//+71JFRUWD34EV/b1Ymg9/J6+44oqPXHPVVVeVkpR+/OMfl48tXLiwNGDAgFL79u1LtbW1pVKpVDrttNNK1dXVpcWLF3/ka/Xp06d0yCGHLHMmAABWnK1LAABYrqqqqowYMWKJ423bti3/+Z133skbb7yRvfbaK/Pnz8+zzz673Nc98sgj07Fjx/LjD+/uffHFF5d77sCBA9OjR4/y45122inV1dXlc+vq6nL//fdnyJAh2WSTTcrrtt566xx00EHLff2k4fubN29e3njjjeyxxx4plUr5y1/+ssT6L3zhCw0e77XXXg3ey913352WLVuW7/BOPtgT+5RTTlmheZIP9lX/xz/+kd/97nflY+PHj0/r1q3zmc98pvyarVu3TpLU19fnrbfeyuLFi9OvX7+lbnuyLPfff38WLlyYU045pcF2L6effvoSa6uqqtKixQf/ilFXV5c333wz7du3z7bbbtvo637o7rvvTmVlZU499dQGx88888yUSqXcc889DY4v7/fi47j77rvTpUuXHHXUUeVjrVq1yqmnnpp33303Dz30UJKkQ4cOmTdv3jK3IenQoUOefvrpPP/88x97LgAA7NENAMAK2HTTTcvh9F89/fTTOeyww1JTU5Pq6up06tSp/EWWc+fOXe7rbr755g0efxi933777Uaf++H5H547e/bsvPfee9l6662XWLe0Y0szY8aMDB8+PBtssEF53+199tknyZLvr02bNktsifKv8yTJyy+/nK5du6Z9+/YN1m277bYrNE+SfPazn01lZWXGjx+fJHn//fdzxx135KCDDmrwXxr88Ic/zE477VTe/7lTp0656667Vuify796+eWXkyQ9e/ZscLxTp04Nrpd8ENW//e1vp2fPnqmqqspGG22UTp065a9//Wujr/uv199kk02y/vrrNzjeq1evBvN9aHm/Fx/Hyy+/nJ49e5Zj/kfN8sUvfjHbbLNNDjrooGy22WY59thjl9gn/NJLL82cOXOyzTbbpHfv3jn77LPz17/+9WPPCACwrhK6AQBYrn+9s/lDc+bMyT777JMnn3wyl156aX79619n4sSJ5T2J6+vrl/u6lZWVSz1e+rcvGWzqc1dEXV1dDjjggNx1110555xzcuedd2bixInlL0389/f3UfM0tY033jgHHHBAfvGLX2TRokX59a9/nXfeeSdDhw4tr/nxj3+c4cOHp0ePHvn+97+fCRMmZOLEifmv//qvFfrnsrIuv/zyjBo1KnvvvXd+/OMf5957783EiROzww47rNLr/qtV/XuxIjbeeONMmTIlv/rVr8r7ix900EEN9mLfe++98/e//z0/+MEPsuOOO+Z73/tedt1113zve99bbXMCAKxNfBklAAAr5cEHH8ybb76Z22+/PXvvvXf5+PTp05txqv+z8cYbp02bNnnhhReWeG5px/7d1KlT87e//S0//OEPc8wxx5SPL2s7iuXZYostMmnSpLz77rsN7up+7rnnGvU6Q4cOzYQJE3LPPfdk/Pjxqa6uzuDBg8vP//znP89WW22V22+/vcF2IxdddNFKzZwkzz//fLbaaqvy8ddff32Ju6R//vOfZ7/99sv3v//9BsfnzJmTjTbaqPz4X2dakevff//9eeeddxrc1f3h1jgfzrc6bLHFFvnrX/+a+vr6Bnd1L22W1q1bZ/DgwRk8eHDq6+vzxS9+MTfccEMuvPDC8v+iYIMNNsiIESMyYsSIvPvuu9l7771z8cUX5/jjj19t7wkAYG3hjm4AAFbKh3fO/uudsgsXLsx3v/vd5hqpgcrKygwcODB33nln/vnPf5aPv/DCC0vs6/xR5ycN31+pVMp3vvOdlZ7p4IMPzuLFi3P99deXj9XV1eWaa65p1OsMGTIk7dq1y3e/+93cc889+fSnP502bdosc/Y///nPeeSRRxo988CBA9OqVatcc801DV7vqquuWmJtZWXlEndO33bbbXn11VcbHFtvvfWSfBDAl+fggw9OXV1drr322gbHv/3tb6eiomKF91tvCgcffHBmzpyZW2+9tXxs8eLFueaaa9K+ffvytjZvvvlmg/NatGiRnXbaKUmyYMGCpa5p3759tt566/LzAAA0jju6AQBYKXvssUc6duyYYcOG5dRTT01FRUX+93//d7VuEbE8F198ce67777sueeeOemkk8rBdMcdd8yUKVOWee52222XHj165Kyzzsqrr76a6urq/OIXv/hYez0PHjw4e+65Z84999y89NJL2X777XP77bc3ev/q9u3bZ8iQIeV9uv9125Ik+eQnP5nbb789hx12WA455JBMnz49Y8eOzfbbb5933323Udfq1KlTzjrrrIwZMyaf/OQnc/DBB+cvf/lL7rnnngZ3aX943UsvvTQjRozIHnvskalTp+YnP/lJgzvBk6RHjx7p0KFDxo4dm/XXXz/rrbde+vfvny233HKJ6w8ePDj77bdfLrjggrz00kvp06dP7rvvvvzyl7/M6aef3uCLJ5vCpEmT8v777y9xfMiQITnxxBNzww03ZPjw4XniiSfSvXv3/PznP8/DDz+cq666qnzH+fHHH5+33nor//Vf/5XNNtssL7/8cq655prsvPPO5f28t99+++y7777p27dvNthggzz++OP5+c9/npNPPrlJ3w8AwLpC6AYAYKVsuOGG+c1vfpMzzzwzX/7yl9OxY8d87nOfy/77759BgwY193hJkr59++aee+7JWWedlQsvvDDdunXLpZdemmnTppW3m/gorVq1yq9//euceuqpGTNmTNq0aZPDDjssJ598cvr06bNS87Ro0SK/+tWvcvrpp+fHP/5xKioqcuihh+bKK6/MLrvs0qjXGjp0aMaPH5+uXbvmv/7rvxo8N3z48MycOTM33HBD7r333my//fb58Y9/nNtuuy0PPvhgo+f+yle+kjZt2mTs2LF54IEH0r9//9x333055JBDGqw7//zzM2/evIwfPz633nprdt1119x1110599xzG6xr1apVfvjDH+a8887LF77whSxevDjjxo1bauj+8O9s9OjRufXWWzNu3Lh07949V1xxRc4888xGv5flmTBhwhJfHJkk3bt3z4477pgHH3ww5557bn74wx+mtrY22267bcaNG5fhw4eX137uc5/LjTfemO9+97uZM2dOunTpkiOPPDIXX3xxecuTU089Nb/61a9y3333ZcGCBdliiy3yla98JWeffXaTvycAgHVBRWlNuuUGAABWgyFDhuTpp5/O888/39yjAAAATcAe3QAArNXee++9Bo+ff/753H333dl3332bZyAAAKDJuaMbAIC1WteuXTN8+PBstdVWefnll3P99ddnwYIF+ctf/pKePXs293gAAEATsEc3AABrtQMPPDA//elPM3PmzFRVVWXAgAG5/PLLRW4AAFiLNOvWJb/73e8yePDgbLLJJqmoqMidd9653HMefPDB7LrrrqmqqsrWW2+dm2++eZXPCQBAcY0bNy4vvfRS3n///cydOzcTJkzIrrvu2txjAQAATahZQ/e8efPSp0+fXHfddSu0fvr06TnkkEOy3377ZcqUKTn99NNz/PHH5957713FkwIAAAAAsKZaY/borqioyB133JEhQ4Z85Jpzzjknd911V5566qnysc9+9rOZM2dOJkyYsBqmBAAAAABgTVOoPbofeeSRDBw4sMGxQYMG5fTTT//IcxYsWJAFCxaUH9fX1+ett97KhhtumIqKilU1KgAAAAAAH0OpVMo777yTTTbZJC1aLHtzkkKF7pkzZ6Zz584NjnXu3Dm1tbV577330rZt2yXOGTNmTC655JLVNSIAAAAAAE3olVdeyWabbbbMNYUK3SvjvPPOy6hRo8qP586dm8033zyvvPJKqqurm3EyAAAAAAA+Sm1tbbp165b1119/uWsLFbq7dOmSWbNmNTg2a9asVFdXL/Vu7iSpqqpKVVXVEserq6uFbgAAAACANdyKbEG97I1N1jADBgzIpEmTGhybOHFiBgwY0EwTAQAAAADQ3Jo1dL/77ruZMmVKpkyZkiSZPn16pkyZkhkzZiT5YNuRY445prz+C1/4Ql588cV86UtfyrPPPpvvfve7+dnPfpYzzjijOcYHAAAAAGAN0Kyh+/HHH88uu+ySXXbZJUkyatSo7LLLLhk9enSS5LXXXitH7yTZcsstc9ddd2XixInp06dPrrzyynzve9/LoEGDmmV+AAAAAACaX0WpVCo19xCrU21tbWpqajJ37lx7dAMAAADACiiVSlm8eHHq6uqaexTWMq1atUplZeVSn2tMyy3Ul1ECAAAAAKvXwoUL89prr2X+/PnNPQproYqKimy22WZp3779x3odoRsAAAAAWKr6+vpMnz49lZWV2WSTTdK6detUVFQ091isJUqlUl5//fX84x//SM+ePT/yzu4VIXQDAAAAAEu1cOHC1NfXp1u3bmnXrl1zj8NaqFOnTnnppZeyaNGijxW6m/XLKAEAAACANV+LFjIiq0ZT/S8E/IYCAAAAAFBoQjcAAAAAAIUmdAMAAAAALEf37t1z1VVXrfD6Bx98MBUVFZkzZ84qm4n/I3QDAAAAAGuNioqKZf5cfPHFK/W6jz32WE488cQVXr/HHnvktddeS01NzUpdb0UJ6h9o2dwDAAAAAAA0lddee63851tvvTWjR4/Oc889Vz7Wvn378p9LpVLq6urSsuXyM2mnTp0aNUfr1q3TpUuXRp3DynNHNwAAAACwQkqlUuYvXNwsP6VSaYVm7NKlS/mnpqYmFRUV5cfPPvts1l9//dxzzz3p27dvqqqq8oc//CF///vf86lPfSqdO3dO+/bts9tuu+X+++9v8Lr/vnVJRUVFvve97+Wwww5Lu3bt0rNnz/zqV78qP//vd1rffPPN6dChQ+6999706tUr7du3z4EHHtggzC9evDinnnpqOnTokA033DDnnHNOhg0bliFDhqz0P7O33347xxxzTDp27Jh27drloIMOyvPPP19+/uWXX87gwYPTsWPHrLfeetlhhx1y9913l88dOnRoOnXqlLZt26Znz54ZN27cSs+yKrmjGwAAAABYIe8tqsv2o+9tlms/c+mgtGvdNDnz3HPPzTe/+c1stdVW6dixY1555ZUcfPDB+epXv5qqqqr86Ec/yuDBg/Pcc89l8803/8jXueSSS/KNb3wjV1xxRa655poMHTo0L7/8cjbYYIOlrp8/f36++c1v5n//93/TokWLfO5zn8tZZ52Vn/zkJ0mSr3/96/nJT36ScePGpVevXvnOd76TO++8M/vtt99Kv9fhw4fn+eefz69+9atUV1fnnHPOycEHH5xnnnkmrVq1ysiRI7Nw4cL87ne/y3rrrZdnnnmmfNf7hRdemGeeeSb33HNPNtpoo7zwwgt57733VnqWVUnoBgAAAADWKZdeemkOOOCA8uMNNtggffr0KT++7LLLcscdd+RXv/pVTj755I98neHDh+eoo45Kklx++eW5+uqr8+ijj+bAAw9c6vpFixZl7Nix6dGjR5Lk5JNPzqWXXlp+/pprrsl5552Xww47LEly7bXXlu+uXhkfBu6HH344e+yxR5LkJz/5Sbp165Y777wzn/nMZzJjxowcfvjh6d27d5Jkq622Kp8/Y8aM7LLLLunXr1+SD+5qX1MJ3QAAAADACmnbqjLPXDqo2a7dVD4Mtx969913c/HFF+euu+7Ka6+9lsWLF+e9997LjBkzlvk6O+20U/nP6623XqqrqzN79uyPXN+uXbty5E6Srl27ltfPnTs3s2bNyu67715+vrKyMn379k19fX2j3t+Hpk2blpYtW6Z///7lYxtuuGG23XbbTJs2LUly6qmn5qSTTsp9992XgQMH5vDDDy+/r5NOOimHH354Jk+enE984hMZMmRIOZivaezRDQAAAACskIqKirRr3bJZfioqKprsfay33noNHp911lm54447cvnll+f3v/99pkyZkt69e2fhwoXLfJ1WrVot8fezrCi9tPUruvf4qnL88cfnxRdfzNFHH52pU6emX79+ueaaa5IkBx10UF5++eWcccYZ+ec//5n9998/Z511VrPO+1GEbgAAAABgnfbwww9n+PDhOeyww9K7d+906dIlL7300mqdoaamJp07d85jjz1WPlZXV5fJkyev9Gv26tUrixcvzp///OfysTfffDPPPfdctt9++/Kxbt265Qtf+EJuv/32nHnmmbnpppvKz3Xq1CnDhg3Lj3/841x11VW58cYbV3qeVcnWJQAAAADAOq1nz565/fbbM3jw4FRUVOTCCy9c6e1CPo5TTjklY8aMydZbb53tttsu11xzTd5+++0Vupt96tSpWX/99cuPKyoq0qdPn3zqU5/KCSeckBtuuCHrr79+zj333Gy66ab51Kc+lSQ5/fTTc9BBB2WbbbbJ22+/nQceeCC9evVKkowePTp9+/bNDjvskAULFuQ3v/lN+bk1jdANAAAAAKzTvvWtb+XYY4/NHnvskY022ijnnHNOamtrV/sc55xzTmbOnJljjjkmlZWVOfHEEzNo0KBUVi5/f/K99967wePKysosXrw448aNy2mnnZZPfvKTWbhwYfbee+/cfffd5W1U6urqMnLkyPzjH/9IdXV1DjzwwHz7299OkrRu3TrnnXdeXnrppbRt2zZ77bVXbrnllqZ/402gotTcm8CsZrW1tampqcncuXNTXV3d3OMAAAAAwBrr/fffz/Tp07PlllumTZs2zT3OOqe+vj69evXKEUcckcsuu6y5x1kllvU71piW645uAAAAAIA1wMsvv5z77rsv++yzTxYsWJBrr70206dPz//8z/8092hrPF9GCQAAAACwBmjRokVuvvnm7Lbbbtlzzz0zderU3H///WvsvthrEnd0AwAAAACsAbp165aHH364uccoJHd0AwAAAABQaEI3AAAAAACFJnQDAAAAAFBoQjcAAAAAAIUmdAMAAAAAUGhCNwAAAAAAhSZ0AwAAAAD8m3333Tenn356+XH37t1z1VVXLfOcioqK3HnnnR/72k31OusSoRsAAAAAWGsMHjw4Bx544FKf+/3vf5+Kior89a9/bfTrPvbYYznxxBM/7ngNXHzxxdl5552XOP7aa6/loIMOatJr/bubb745HTp0WKXXWJ2EbgAAAABgrXHcccdl4sSJ+cc//rHEc+PGjUu/fv2y0047Nfp1O3XqlHbt2jXFiMvVpUuXVFVVrZZrrS2EbgAAAABgxZRKycJ5zfNTKq3QiJ/85CfTqVOn3HzzzQ2Ov/vuu7ntttty3HHH5c0338xRRx2VTTfdNO3atUvv3r3z05/+dJmv++9blzz//PPZe++906ZNm2y//faZOHHiEuecc8452WabbdKuXbtstdVWufDCC7No0aIkH9xRfckll+TJJ59MRUVFKioqyjP/+9YlU6dOzX/913+lbdu22XDDDXPiiSfm3XffLT8/fPjwDBkyJN/85jfTtWvXbLjhhhk5cmT5WitjxowZ+dSnPpX27dunuro6RxxxRGbNmlV+/sknn8x+++2X9ddfP9XV1enbt28ef/zxJMnLL7+cwYMHp2PHjllvvfWyww475O67717pWVZEy1X66gAAAADA2mPR/OTyTZrn2uf/M2m93nKXtWzZMsccc0xuvvnmXHDBBamoqEiS3Hbbbamrq8tRRx2Vd999N3379s0555yT6urq3HXXXTn66KPTo0eP7L777su9Rn19fT796U+nc+fO+fOf/5y5c+c22M/7Q+uvv35uvvnmbLLJJpk6dWpOOOGErL/++vnSl76UI488Mk899VQmTJiQ+++/P0lSU1OzxGvMmzcvgwYNyoABA/LYY49l9uzZOf7443PyySc3iPkPPPBAunbtmgceeCAvvPBCjjzyyOy888454YQTlvt+lvb+PozcDz30UBYvXpyRI0fmyCOPzIMPPpgkGTp0aHbZZZdcf/31qayszJQpU9KqVaskyciRI7Nw4cL87ne/y3rrrZdnnnkm7du3b/QcjSF0AwAAAABrlWOPPTZXXHFFHnrooey7775JPti25PDDD09NTU1qampy1llnldefcsopuffee/Ozn/1shUL3/fffn2effTb33ntvNtnkg/B/+eWXL7Gv9pe//OXyn7t3756zzjort9xyS770pS+lbdu2ad++fVq2bJkuXbp85LXGjx+f999/Pz/60Y+y3nofhP5rr702gwcPzte//vV07tw5SdKxY8dce+21qayszHbbbZdDDjkkkyZNWqnQPWnSpEydOjXTp09Pt27dkiQ/+tGPssMOO+Sxxx7LbrvtlhkzZuTss8/OdtttlyTp2bNn+fwZM2bk8MMPT+/evZMkW221VaNnaCyhGwAAAABYMa3afXBndXNdewVtt9122WOPPfKDH/wg++67b1544YX8/ve/z6WXXpokqaury+WXX56f/exnefXVV7Nw4cIsWLBghffgnjZtWrp161aO3EkyYMCAJdbdeuutufrqq/P3v/897777bhYvXpzq6uoVfh8fXqtPnz7lyJ0ke+65Z+rr6/Pcc8+VQ/cOO+yQysrK8pquXbtm6tSpjbrWv16zW7du5cidJNtvv306dOiQadOmZbfddsuoUaNy/PHH53//938zcODAfOYzn0mPHj2SJKeeempOOumk3HfffRk4cGAOP/zwldoXvTHs0Q0AAAAArJiKig+2D2mOn/+/BcmKOu644/KLX/wi77zzTsaNG5cePXpkn332SZJcccUV+c53vpNzzjknDzzwQKZMmZJBgwZl4cKFTfZX9cgjj2To0KE5+OCD85vf/CZ/+ctfcsEFFzTpNf7Vh9uGfKiioiL19fWr5FpJcvHFF+fpp5/OIYcckt/+9rfZfvvtc8cddyRJjj/++Lz44os5+uijM3Xq1PTr1y/XXHPNKpslEboBAAAAgLXQEUcckRYtWmT8+PH50Y9+lGOPPba8X/fDDz+cT33qU/nc5z6XPn36ZKuttsrf/va3FX7tXr165ZVXXslrr71WPvanP/2pwZo//vGP2WKLLXLBBRekX79+6dmzZ15++eUGa1q3bp26urrlXuvJJ5/MvHnzyscefvjhtGjRIttuu+0Kz9wYH76/V155pXzsmWeeyZw5c7L99tuXj22zzTY544wzct999+XTn/50xo0bV36uW7du+cIXvpDbb789Z555Zm666aZVMuuHhG4AAAAAYK3Tvn37HHnkkTnvvPPy2muvZfjw4eXnevbsmYkTJ+aPf/xjpk2bls9//vOZNWvWCr/2wIEDs80222TYsGF58skn8/vf/z4XXHBBgzU9e/bMjBkzcsstt+Tvf/97rr766vIdzx/q3r17pk+fnilTpuSNN97IggULlrjW0KFD06ZNmwwbNixPPfVUHnjggZxyyik5+uijy9uWrKy6urpMmTKlwc+0adMycODA9O7dO0OHDs3kyZPz6KOP5phjjsk+++yTfv365b333svJJ5+cBx98MC+//HIefvjhPPbYY+nVq1eS5PTTT8+9996b6dOnZ/LkyXnggQfKz60qQjcAAAAAsFY67rjj8vbbb2fQoEEN9tP+8pe/nF133TWDBg3Kvvvumy5dumTIkCEr/LotWrTIHXfckffeey+77757jj/++Hz1q19tsObQQw/NGWeckZNPPjk777xz/vjHP+bCCy9ssObwww/PgQcemP322y+dOnXKT3/60yWu1a5du9x777156623sttuu+W///u/s//+++faa69t3F/GUrz77rvZZZddGvwMHjw4FRUV+eUvf5mOHTtm7733zsCBA7PVVlvl1ltvTZJUVlbmzTffzDHHHJNtttkmRxxxRA466KBccsklST4I6CNHjkyvXr1y4IEHZptttsl3v/vdjz3vslSUSqXSKr3CGqa2tjY1NTWZO3duozd+BwAAAIB1yfvvv5/p06dnyy23TJs2bZp7HNZCy/oda0zLdUc3AAAAAACFJnQDAAAAAFBoQjcAAAAAAIUmdAMAAAAAUGhCNwAAAACwTKVSqblHYC3VVL9bQjcAAAAAsFStWrVKksyfP7+ZJ2FttXDhwiRJZWXlx3qdlk0xDAAAAACw9qmsrEyHDh0ye/bsJEm7du1SUVHRzFOxtqivr8/rr7+edu3apWXLj5eqhW4AAAAA4CN16dIlScqxG5pSixYtsvnmm3/s/wJF6AYAAAAAPlJFRUW6du2ajTfeOIsWLWrucVjLtG7dOi1afPwdtoVuAAAAAGC5KisrP/Y+yrCq+DJKAAAAAAAKTegGAAAAAKDQhG4AAAAAAApN6AYAAAAAoNCEbgAA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V2bOnJmFCxemdevWS5xTVVWVqqqqph0eAAAAAIA1RrPd0d26dev07ds3kyZNKh+rr6/PpEmTMmDAgKWes+eee+aFF15IfX19+djf/va3dO3adamRGwAAAACAtV+zbl0yatSo3HTTTfnhD3+YadOm5aSTTsq8efMyYsSIJMkxxxyT8847r7z+pJNOyltvvZXTTjstf/vb33LXXXfl8ssvz8iRI5vrLQAAAAAA0MyabeuSJDnyyCPz+uuvZ/To0Zk5c2Z23nnnTJgwofwFlTNmzEiLFv/X4rt165Z77703Z5xxRnbaaadsuummOe2003LOOec011sAAAAAAKCZVZRKpVJzD7E61dbWpqamJnPnzk11dXVzjwMAAAAAwFI0puU269YlAAAAAADwcQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABRao0N39+7dc+mll2bGjBmrYh4AAAAAAGiURofu008/Pbfffnu22mqrHHDAAbnllluyYMGCVTEbAAAAAAAs10qF7ilTpuTRRx9Nr169csopp6Rr1645+eSTM3ny5FUxIwAAAAAAfKSKUqlU+jgvsGjRonz3u9/NOeeck0WLFqV379459dRTM2LEiFRUVDTVnE2mtrY2NTU1mTt3bqqrq5t7HAAAAAAAlqIxLbflyl5k0aJFueOOOzJu3LhMnDgx//Ef/5Hjjjsu//jHP3L++efn/vvvz/jx41f25QEAAAAAYIU0OnRPnjw548aNy09/+tO0aNEixxxzTL797W9nu+22K6857LDDsttuuzXpoAAAAAAAsDSNDt277bZbDjjggFx//fUZMmRIWrVqtcSaLbfcMp/97GebZEAAAAAAAFiWRofuF198MVtsscUy16y33noZN27cSg8FAAAAAAArqtGh+8PI/fjjj2fatGlJkl69eqVfv35NOxkAAAAAAKyARofuf/zjHznqqKPy8MMPp0OHDkmSOXPmZI899sgtt9ySzTbbrKlnBAAAAACAj9SisSccf/zxWbRoUaZNm5a33norb731VqZNm5b6+vocf/zxq2JGAAAAAAD4SBWlUqnUmBPatm2bP/7xj9lll10aHH/iiSey1157Zf78+U06YFOrra1NTU1N5s6dm+rq6uYeBwAAAACApWhMy230Hd3dunXLokWLljheV1eXTTbZpLEvBwAAAAAAH0ujQ/cVV1yRU045JY8//nj52OOPP57TTjst3/zmN5t0OAAAAAAAWJ5Gb13SsWPHzJ8/P4sXL07Llh98l+WHf15vvfUarH3rrbeabtImYusSAAAAAIA1X2NabsvGvvhVV121snMBAAAAAECTa3ToHjZs2KqYAwAAAAAAVkqjQ3fywRdP3nnnnZk2bVqSZIcddsihhx6aysrKJh0OAAAAAACWp9Gh+4UXXsjBBx+cV199Ndtuu22SZMyYMenWrVvuuuuu9OjRo8mHBAAAAACAj9KisSeceuqp6dGjR1555ZVMnjw5kydPzowZM7Llllvm1FNPXRUzAgAAAADAR2r0Hd0PPfRQ/vSnP2WDDTYoH9twww3zta99LXvuuWeTDgcAAAAAAMvT6Du6q6qq8s477yxx/N13303r1q2bZCgAAAAAAFhRjQ7dn/zkJ3PiiSfmz3/+c0qlUkqlUv70pz/lC1/4Qg499NBVMSMAAAAAAHykRofuq6++Oj169MiAAQPSpk2btGnTJnvuuWe23nrrfOc731kVMwIAAAAAwEdq1B7dpVIptbW1ueWWW/Lqq69m2rRpSZJevXpl6623XiUDAgAAAADAsjQ6dG+99dZ5+umn07NnT3EbAAAAAIBm16itS1q0aJGePXvmzTffXFXzAAAAAABAozR6j+6vfe1rOfvss/PUU0+tinkAAAAAAKBRKkqlUqkxJ3Ts2DHz58/P4sWL07p167Rt27bB82+99VaTDtjUamtrU1NTk7lz56a6urq5xwEAAAAAYCka03IbtUd3knz7299ORUXFSg8HAAAAAABNqdGhe/jw4atgDAAAAAAAWDmN3qO7srIys2fPXuL4m2++mcrKyiYZCgAAAAAAVlSjQ/dHbem9YMGCtG7d+mMPBAAAAAAAjbHCW5dcffXVSZKKiop873vfS/v27cvP1dXV5Xe/+1222267pp8QAAAAAACWYYVD97e//e0kH9zRPXbs2AbblLRu3Trdu3fP2LFjm35CAAAAAABYhhUO3dOnT0+S7Lfffrn99tvTsWPHVTYUAAAAAACsqBUO3R964IEHVsUcAAAAAACwUhoduuvq6nLzzTdn0qRJmT17durr6xs8/9vf/rbJhgMAAAAAgOVpdOg+7bTTcvPNN+eQQw7JjjvumIqKilUxFwAAAAAArJBGh+5bbrklP/vZz3LwwQevinkAAAAAAKBRWjT2hNatW2frrbdeFbMAAAAAAECjNTp0n3nmmfnOd76TUqm0KuYBAAAAAIBGafTWJX/4wx/ywAMP5J577skOO+yQVq1aNXj+9ttvb7LhAAAAAABgeRodujt06JDDDjtsVcwCAAAAAACN1ujQPW7cuFUxBwAAAAAArJQV3qN79uzZy3x+8eLFefTRRz/2QAAAAAAA0BgrHLq7du3aIHb37t07r7zySvnxm2++mQEDBjTtdAAAAAAAsBwrHLpLpVKDxy+99FIWLVq0zDUAAAAAALCqrXDoXhEVFRVN+XIAAAAAALBcTRq6AQAAAABgdWu5ogsrKiryzjvvpE2bNimVSqmoqMi7776b2traJCn/XwAAAAAAWJ1WOHSXSqVss802DR7vsssuDR7bugQAAAAAgNVthUP3Aw88sCrnAAAAAACAlbLCoXufffZZlXMAAAAAAMBK8WWUAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKF97NBdW1ubO++8M9OmTWuKeQAAAAAAoFEaHbqPOOKIXHvttUmS9957L/369csRRxyRnXbaKb/4xS+afEAAAAAAAFiWRofu3/3ud9lrr72SJHfccUdKpVLmzJmTq6++Ol/5yleafEAAAAAAAFiWRofuuXPnZoMNNkiSTJgwIYcffnjatWuXQw45JM8//3yTDwgAAAAAAMvS6NDdrVu3PPLII5k3b14mTJiQT3ziE0mSt99+O23atGnyAQEAAAAAYFlaNvaE008/PUOHDk379u2zxRZbZN99903ywZYmvXv3bur5AAAAAABgmRodur/4xS9m9913zyuvvJIDDjggLVp8cFP4VlttZY9uAAAAAABWu4pSqVT6OC9QV1eXqVOnZosttkjHjh2baq5Vpra2NjU1NZk7d26qq6ubexwAAAAAAJaiMS230Xt0n3766fn+97+f5IPIvc8++2TXXXdNt27d8uCDD67UwAAAAAAAsLIaHbp//vOfp0+fPkmSX//615k+fXqeffbZnHHGGbnggguafEAAAAAAAFiWRofuN954I126dEmS3H333fnMZz6TbbbZJscee2ymTp3a5AMCAAAAAMCyNDp0d+7cOc8880zq6uoyYcKEHHDAAUmS+fPnp7KysskHBAAAAACAZWnZ2BNGjBiRI444Il27dk1FRUUGDhyYJPnzn/+c7bbbrskHBAAAAACAZWl06L744ouz44475pVXXslnPvOZVFVVJUkqKytz7rnnNvmAAAAAAACwLBWlUqnU3EOsTrW1tampqcncuXNTXV3d3OMAAAAAALAUjWm5jd6jO0keeuihDB48OFtvvXW23nrrHHroofn973+/UsMCAAAAAMDH0ejQ/eMf/zgDBw5Mu3btcuqpp+bUU09N27Zts//++2f8+PGrYkYAAAAAAPhIjd66pFevXjnxxBNzxhlnNDj+rW99KzfddFOmTZvWpAM2NVuXAAAAAACs+Vbp1iUvvvhiBg8evMTxQw89NNOnT2/sywEAAAAAwMfS6NDdrVu3TJo0aYnj999/f7p169YkQwEAAAAAwIpq2dgTzjzzzJx66qmZMmVK9thjjyTJww8/nJtvvjnf+c53mnxAAAAAAABYlkaH7pNOOildunTJlVdemZ/97GdJPti3+9Zbb82nPvWpJh8QAAAAAACWpVGhe/Hixbn88stz7LHH5g9/+MOqmgkAAAAAAFZYo/bobtmyZb7xjW9k8eLFq2oeAAAAAABolEZ/GeX++++fhx56aFXMAgAAAAAAjdboPboPOuignHvuuZk6dWr69u2b9dZbr8Hzhx56aJMNBwAAAAAAy1NRKpVKjTmhRYuPvgm8oqIidXV1H3uoVam2tjY1NTWZO3duqqurm3scAAAAAACWojEtt9F3dNfX16/0YAAAAAAA0NQavUc3AAAAAACsSVY4dP/2t7/N9ttvn9ra2iWemzt3bnbYYYf87ne/a9LhAAAAAABgeVY4dF911VU54YQTlroXSk1NTT7/+c/n29/+dpMOBwAAAAAAy7PCofvJJ5/MgQce+JHPf+ITn8gTTzzRJEMBAAAAAMCKWuHQPWvWrLRq1eojn2/ZsmVef/31JhkKAAAAAABW1AqH7k033TRPPfXURz7/17/+NV27dm2SoQAAAAAAYEWtcOg++OCDc+GFF+b9999f4rn33nsvF110UT75yU826XAAAAAAALA8FaVSqbQiC2fNmpVdd901lZWVOfnkk7PtttsmSZ599tlcd911qaury+TJk9O5c+dVOvDHVVtbm5qamsydO3epX6wJAAAAAEDza0zLbbmiL9q5c+f88Y9/zEknnZTzzjsvH/bxioqKDBo0KNddd90aH7kBAAAAAFj7rHDoTpItttgid999d95+++288MILKZVK6dmzZzp27Liq5gMAAAAAgGVqVOj+UMeOHbPbbrs19SwAAAAAANBoK/xllAAAAAAAsCYSugEAAAAAKDShGwAAAACAQhO6AQAAAAAoNKEbAAAAAIBCE7oBAAAAACg0oRsAAAAAgEITugEAAAAAKLQ1InRfd9116d69e9q0aZP+/fvn0UcfXaHzbrnlllRUVGTIkCGrdkAAAAAAANZYzR66b7311owaNSoXXXRRJk+enD59+mTQoEGZPXv2Ms976aWXctZZZ2WvvfZaTZMCAAAAALAmavbQ/a1vfSsnnHBCRowYke233z5jx45Nu3bt8oMf/OAjz6mrq8vQoUNzySWXZKuttlqN0wIAAAAAsKZp1tC9cOHCPPHEExk4cGD5WIsWLTJw4MA88sgjH3nepZdemo033jjHHXfccq+xYMGC1NbWNvgBAAAAAGDt0ayh+4033khdXV06d+7c4Hjnzp0zc+bMpZ7zhz/8Id///vdz0003rdA1xowZk5qamvJPt27dPvbcAAAAAACsOZp965LGeOedd3L00UfnpptuykYbbbRC55x33nmZO3du+eeVV15ZxVMCAAAAALA6tWzOi2+00UaprKzMrFmzGhyfNWtWunTpssT6v//973nppZcyePDg8rH6+vokScuWLfPcc8+lR48eDc6pqqpKVVXVKpgeAAAAAIA1QbPe0d26dev07ds3kyZNKh+rr6/PpEmTMmDAgCXWb7fddpk6dWqmTJlS/jn00EOz3377ZcqUKbYlAQAAAABYBzXrHd1JMmrUqAwbNiz9+vXL7rvvnquuuirz5s3LiBEjkiTHHHNMNt1004wZMyZt2rTJjjvu2OD8Dh06JMkSxwEAAAAAWDc0e+g+8sgj8/rrr2f06NGZOXNmdt5550yYMKH8BZUzZsxIixaF2kocAAAAAIDVqKJUKpWae4jVqba2NjU1NZk7d26qq6ubexwAAAAAAJaiMS3XrdIAAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAAQKEJ3QAAAAAAFJrQDQAAAABAoQndAAAAAAAUmtANAAAAAEChCd0AAAAAABSa0A0AAAAA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rQDka1/7WioqKnL66aeXj/kMA9Z0r776aj73uc9lww03TNu2bdO7d+88/vjj5edLpVJGjx6drl27pm3bthk4cGCef/75Bq/x1ltvZejQoamurk6HDh1y3HHH5d13313dbwVYB9XV1eXCCy/MlltumbZt26ZHjx657LLLUiqVymt8jq39hO51xK233ppRo0bloosuyuTJk9OnT58MGjQos2fPbu7RAPLQQw9l5MiR+dOf/pSJEydm0aJF+cQnPpF58+aV15xxxhn59a9/ndtuuy0PPfRQ/vnPf+bTn/50+fm6uroccsghWbhwYf74xz/mhz/8YW6++eaMHj26Od4SsI567LHHcsMNN2SnnXZqcNxnGLAme/vtt7PnnnumVatWueeee/LMM8/kyiuvTMeOHctrvvGNb+Tqq6/O2LFj8+c//znrrbdeBg0alPfff7+8ZujQoXn66aczceLE/OY3v8nvfve7nHjiic3xloB1zNe//vVcf/31ufbaazNt2rR8/etfzze+8Y1cc8015TU+x9YBJdYJu+++e2nkyJHlx3V1daVNNtmkNGbMmGacCmDpZs+eXUpSeuihh0qlUqk0Z86cUqtWrUq33XZbec20adNKSUqPPPJIqVQqle6+++5SixYtSjNnziyvuf7660vV1dWlBQsWrN43AKyT3nnnnVLPnj1LEydOLO2zzz6l0047rVQq+QwD1nznnHNO6T//8z8/8vn6+vpSly5dSldccUX52Jw5c0pVVVWln/70p6VSqVR65plnSklKjz32WHnNPffcU6qoqCi9+uqrq254gFKpdMghh5SOPfbYBsc+/elPl4YOHVoqlXyOrSvc0b0OWLhwYZ544okMHDiwfKxFixYZOHBgHnnkkWacDGDp5s6dmyTZYIMNkiRPPPFEFi1a1OBzbLvttsvmm29e/hx75JFH0rt373Tu3Lm8ZtCgQamtrc3TTz+9GqcH1lUjR47MIYcc0uCzKvEZBqz5fvWrX6Vfv375zGc+k4033ji77LJLbrrppvLz06dPz8yZMxt8jtXU1KR///4NPsc6dOiQfv36ldcMHDgwLVq0yJ///OfV92aAddIee+yRSZMm5W9/+1uS5Mknn8wf/vCHHHTQQUl8jq0rWjb3AKx6b7zxRurq6hr8i1OSdO7cOc8++2wzTQWwdPX19Tn99NOz5557Zscdd0ySzJw5M61bt06HDh0arO3cuXNmzpxZXrO0z7kPnwNYlW655ZZMnjw5jz322BLP+QwD1nQvvvhirr/++owaNSrnn39+HnvssZx66qlp3bp1hg0bVv4cWtrn1L9+jm288cYNnm/ZsmU22GADn2PAKnfuueemtrY22223XSorK1NXV5evfvWrGTp0aJL4HFtHCN0ArFFGjhyZp556Kn/4wx+aexSAFfLKK6/ktNNOy8SJE9OmTZvmHgeg0err69OvX79cfvnlSZJddtklTz31VMaOHZthw4Y183QAy/ezn/0sP/nJTzJ+/PjssMMOmTJlSk4//fRssskmPsfWIbYuWQdstNFGqayszKxZsxocnzVrVrp06dJMUwEs6eSTT85vfvObPPDAA9lss83Kx7t06ZKFCxdmzpw5Ddb/6+dYly5dlvo59+FzAKvKE088kdmzZ2fXXXdNy5Yt07Jlyzz00EO5+uqr07Jly3Tu3NlnGLBG69q1a7bffvsGx3r16pUZM2Yk+b/PoWX9O2WXLl0ye/bsBs8vXrw4b731ls8xYJU7++yzc+655+azn/1sevfunaOPPjpnnHFGxowZk8Tn2LpC6F4HtG7dOn379s2kSZPKx+rr6zNp0qQMGDCgGScD+ECpVMrJJ5+cO+64I7/97W+z5ZZbNni+b9++adWqVYPPseeeey4zZswof44NGDAgU6dObfAfTCZOnJjq6uol/sUNoCntv//+mTp1aqZMmVL+6devX4YOHVr+s88wYE2255575rnnnmtw7G9/+1u22GKLJMmWW26ZLl26NPgcq62tzZ///OcGn2Nz5szJE088UV7z29/+NvX19enfv/9qeBfAumz+/Plp0aJh5qysrEx9fX0Sn2PrCluXrCNGjRqVYcOGpV+/ftl9991z1VVXZd68eRkxYkRzjwaQkSNHZvz48fnlL3+Z9ddfv7z/WU1NTdq2bZuampocd9xxGTVqVDbYYINUV1fnlFNOyYABA/If//EfSZJPfOIT2X777XP00UfnG9/4RmbOnJkvf/nLGTlyZKqqqprz7QFrufXXX7/8nQIfWm+99bLhhhuWj/sMA9ZkZ5xxRvbYY49cfvnlOeKII/Loo4/mxhtvzI033pgkqaioyOmnn56vfOUr6dmzZ7bccstceOGF2WSTTTJkyJAkH9wBfuCBB+aEE07I2LFjs2jRopx88sn57Gc/m0022aQZ3x2wLhg8eHC++tWvZvPNN88OO+yQv/zlL/nWt76VY489NonPsXVGiXXGNddcU9p8881LrVu3Lu2+++6lP/3pT809EkCpVCqVkiz1Z9y4ceU17733XumLX/xiqWPHjqV27dqVDjvssNJrr73W4HVeeuml0kEHHVRq27ZtaaONNiqdeeaZpUWLFq3mdwNQKu2zzz6l0047rfzYZxiwpvv1r39d2nHHHUtVVVWl7bbbrnTjjTc2eL6+vr504YUXljp37lyqqqoq7b///qXnnnuuwZo333yzdNRRR5Xat29fqq6uLo0YMaL0zjvvrM63AayjamtrS6eddlpp8803L7Vp06a01VZblS644ILSggULymt8jq39KkqlUqk5QzsAAAAAAHwc9ugGAAAAAKDQhG4AAAAAAApN6AYAAAAAoNCEbgAAAAAACk3oBgAAAACg0IRuAAAAAAAKTegGAAAAAKDQhG4AAAAAAApN6AYAgHXUgw8+mIqKisyZM6e5RwEAgI9F6AYAAAAAoNCEbgAAAAAACk3oBgCAZlJfX58xY8Zkyy23TNu2bdOnT5/8/Oc/T/J/24rcdddd2WmnndKmTZv8x3/8R5566qkGr/GLX/wiO+ywQ6qqqtK9e/dceeWVDZ5fsGBBzjnnnHTr1i1VVVXZeuut8/3vf7/BmieeeCL9+vVLu3btsscee+S5555btW8cAACamNANAADNZMyYMfnRj36UsWPH5umnn84ZZ5yRz33uc3nooYfKa84+++xceeWVeeyxx9KpU6cMHjw4ixYtSvJBoD7iiCPy2c9+NlOnTs3FF1+cCy+8MDfffHP5/GOOOSY//elPc/XVV2fatGm54YYb0r59+wZzXHDBBbnyyivz+OOPp2XLljn22GNXy/sHAICmUlEqlUrNPQQAAKxrFixYkA022CD3339/BgwYUD5+/PHHZ/78+TnxxBOz33775ZZbbsmRRx6ZJHnrrbey2Wab5eabb84RRxyRoUOH5vXXX899991XPv9LX/pS7rrrrjz99NP529/+lm233TYTJ07MwIEDl5jhwQcfzH777Zf7778/+++/f5Lk7rvvziGHHJL33nsvbdq0WcV/CwAA0DTc0Q0AAM3ghRdeyPz583PAAQekffv25Z8f/ehH+fvf/15e968RfIMNNsi2226badOmJUmmTZuWPffcs8Hr7rnnnnn++edTV1eXKVOmpLKyMvvss88yZ9lpp53Kf+7atWuSZPbs2R/7PQIAwOrSsrkHAACAddG7776bJLnrrruy6aabNniuqqqqQexeWW3btl2hda1atSr/uaKiIskH+4cDAEBRuKMbAACawfbbb5+qqqrMmDEjW2+9dYOfbt26ldf96U9/Kv/57bffzt/+9rf06tUrSdKrV688/PDDDV734YcfzjbbbJPKysr07t079fX1Dfb8BgCAtZE7ugEAoBmsv/76Oeuss3LGGWekvr4+//mf/5m5c+fm4YcfTnV1dbbYYoskyaWXXpoNN9wwnTt3zgUXXJCNNtooQ4YMSZKceeaZ2W233XLZZZflyCOPzCOPPJJrr7023/3ud5Mk3bt3z7Bhw3Lsscfm6quvTp8+ffLyyy9n9uzZOeKII5rrrQMAQJMTugEAoJlcdtll6dSpU8aMGZMXX3wxHTp0yK677przzz+/vHXI1772tZx22ml5/vnns/POO+fXv/51WrdunSTZdddd87Of/SyjR4/OZZddlq5du+bSSy/N8OHDy9e4/vrrc/755+eLX/xi3nzzzWy++eY5//zzm+PtAgDAKlNRKpVKzT0EAADQ0IMPPpj99tsv/6+dO6gBAIaBGDYI5U+yFAZji2Qj6DuqbnfPzLw+BwAAvmajGwAAAACANKEbAAAAAIA00yUAAAAAAKT56AYAAAAAIE3oBgAAAAAgTegGAAAAACBN6AYAAAAAIE3oBgAAAAAgTegGAAAAACBN6AYAAAAAIE3oBgAAAAAg7QJJ5ef4dSLjKwAAAABJRU5ErkJggg==)


![Gráfico de Accuracy e loss após o uso de fine tune] (data: data:image/png;base64,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RKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxKpTErly5EtbW1pDJZHBxccGZM2dKrVtQUICgoCDY2NhAJpPBwcEBUVFRKnUCAwMhkUhUNjs7O5U6ubm5mDBhAkxMTCCXy+Hp6Ym0tLSKhE9EREREGk7tJHb79u3w8/PD3Llzcf78eTg4OMDNzQ33798vsb6/vz/Wrl2L0NBQXL16FePGjUPfvn1x4cIFlXrNmjVDSkqKuJ04cULl+JQpU7Bnzx7s3LkTx44dw71799CvXz91wyciIiKiKkDtJHbp0qUYM2YMRowYgaZNm2LNmjUwMDDA+vXrS6y/efNmzJo1C+7u7mjYsCHGjx8Pd3d3fP/99yr1dHR0YG5uLm61atUSj2VkZGDdunVYunQpunbtCicnJ4SFheHPP//EqVOn1L0EIiIiItJwaiWx+fn5OHfuHFxdXf+vAS0tuLq6IjY2tsRz8vLyIJPJVMr09fWLjbTeuHEDlpaWaNiwIYYMGYKkpCTx2Llz51BQUKDSr52dHerVq/fSfjMzM1U2IiIiIqoa1EpiHz58CIVCATMzM5VyMzMzpKamlniOm5sbli5dihs3bkCpVCI6OhoRERFISUkR67i4uGDDhg2IiorC6tWrkZCQgA4dOuDJkycAgNTUVOjp6cHY2Ljc/QYHB8PIyEjcrKys1LlUIiIiInqHvfHVCZYvXw5bW1vY2dlBT08Pvr6+GDFiBLS0/q/rHj16YMCAAWjRogXc3Nywb98+pKenY8eOHRXud+bMmcjIyBC3u3fvvo7LISIiIqJ3gFpJbK1ataCtrV1sVYC0tDSYm5uXeI6pqSkiIyORnZ2NxMREXL9+HXK5HA0bNiy1H2NjY3zwwQe4efMmAMDc3Bz5+flIT08vd79SqRSGhoYqGxERERFVDWolsXp6enByckJMTIxYplQqERMTg7Zt2770XJlMhjp16qCwsBC//vorevfuXWrdrKws3Lp1CxYWFgAAJycn6OrqqvQbHx+PpKSkMvslIiIioqpHR90T/Pz84O3tDWdnZ7Rp0wYhISHIzs7GiBEjAADDhw9HnTp1EBwcDAA4ffo0kpOT4ejoiOTkZAQGBkKpVOLrr78W25w2bRo8PDxQv3593Lt3D3PnzoW2tja8vLwAAEZGRhg1ahT8/PxQs2ZNGBoaYuLEiWjbti0+/PDD1/E5EBEREZEGUTuJHThwIB48eICAgACkpqbC0dERUVFR4sNeSUlJKvNdc3Nz4e/vj9u3b0Mul8Pd3R2bN29WeUjr33//hZeXFx49egRTU1N89NFHOHXqFExNTcU6y5Ytg5aWFjw9PZGXlwc3NzesWrXqFS6diIiIiDSVRBAEobKDeBsyMzNhZGSEjIwMzo8lIiIiteQU5MAl3AUAcHrwaRjoGlRyRFWTOvnaG1+dgIiIiIjodWMSS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHEqlMSuXLkS1tbWkMlkcHFxwZkzZ0qtW1BQgKCgINjY2EAmk8HBwQFRUVEqdYKDg9G6dWtUr14dtWvXRp8+fRAfH69Sp3PnzpBIJCrbuHHjKhI+EREREWk4tZPY7du3w8/PD3PnzsX58+fh4OAANzc33L9/v8T6/v7+WLt2LUJDQ3H16lWMGzcOffv2xYULF8Q6x44dw4QJE3Dq1ClER0ejoKAAn3zyCbKzs1XaGjNmDFJSUsRt0aJF6oZPRERERFWARBAEQZ0TXFxc0Lp1a6xYsQIAoFQqYWVlhYkTJ2LGjBnF6ltaWmL27NmYMGGCWObp6Ql9fX1s2bKlxD4ePHiA2rVr49ixY+jYsSOAZyOxjo6OCAkJUSdcUWZmJoyMjJCRkQFDQ8MKtUFERETvp5yCHLiEuwAATg8+DQNdg0qOqGpSJ19TayQ2Pz8f586dg6ur6/81oKUFV1dXxMbGlnhOXl4eZDKZSpm+vj5OnDhRaj8ZGRkAgJo1a6qUb926FbVq1ULz5s0xc+ZM5OTklNpGXl4eMjMzVTYiIiIiqhp01Kn88OFDKBQKmJmZqZSbmZnh+vXrJZ7j5uaGpUuXomPHjrCxsUFMTAwiIiKgUChKrK9UKjF58mS0b98ezZs3F8sHDx6M+vXrw9LSEpcuXcL06dMRHx+PiIiIEtsJDg7GvHnz1Lk8IiIiItIQaiWxFbF8+XKMGTMGdnZ2kEgksLGxwYgRI7B+/foS60+YMAFXrlwpNlI7duxY8Wd7e3tYWFigW7duuHXrFmxsbIq1M3PmTPj5+Yn7mZmZsLKyek1XRURERESVSa3pBLVq1YK2tjbS0tJUytPS0mBubl7iOaampoiMjER2djYSExNx/fp1yOVyNGzYsFhdX19f/P777zhy5Ajq1q370lhcXJ7NS7l582aJx6VSKQwNDVU2IiIiIqoa1Epi9fT04OTkhJiYGLFMqVQiJiYGbdu2fem5MpkMderUQWFhIX799Vf07t1bPCYIAnx9fbFr1y4cPnwYDRo0KDOWuLg4AICFhYU6l0BEREREVYDa0wn8/Pzg7e0NZ2dntGnTBiEhIcjOzsaIESMAAMOHD0edOnUQHBwMADh9+jSSk5Ph6OiI5ORkBAYGQqlU4uuvvxbbnDBhAsLDw/Hbb7+hevXqSE1NBQAYGRlBX18ft27dQnh4ONzd3WFiYoJLly5hypQp6NixI1q0aPE6PgciIiIi0iBqJ7EDBw7EgwcPEBAQgNTUVDg6OiIqKkp82CspKQlaWv83wJubmwt/f3/cvn0bcrkc7u7u2Lx5M4yNjcU6q1evBvBsGa3nhYWFwcfHB3p6ejh06JCYMFtZWcHT0xP+/v4VuGQiIiIi0nRqrxOrqbhOLBEREVUU14l9O97YOrFERERERO8CJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQah0ksEREREWkcJrFEREREpHGYxBIRERGRxmESS0REREQap0JJ7MqVK2FtbQ2ZTAYXFxecOXOm1LoFBQUICgqCjY0NZDIZHBwcEBUVpXabubm5mDBhAkxMTCCXy+Hp6Ym0tLSKhE9EREREGk7tJHb79u3w8/PD3Llzcf78eTg4OMDNzQ33798vsb6/vz/Wrl2L0NBQXL16FePGjUPfvn1x4cIFtdqcMmUK9uzZg507d+LYsWO4d+8e+vXrV4FLJiIiIiJNJxEEQVDnBBcXF7Ru3RorVqwAACiVSlhZWWHixImYMWNGsfqWlpaYPXs2JkyYIJZ5enpCX18fW7ZsKVebGRkZMDU1RXh4OPr37w8AuH79Opo0aYLY2Fh8+OGHZcadmZkJIyMjZGRkwNDQUJ1LJiIiovdcTkEOXMJdAACnB5+Gga5BJUdUNamTr6k1Epufn49z587B1dX1/xrQ0oKrqytiY2NLPCcvLw8ymUylTF9fHydOnCh3m+fOnUNBQYFKHTs7O9SrV++l/WZmZqpsRERERFQ1qJXEPnz4EAqFAmZmZirlZmZmSE1NLfEcNzc3LF26FDdu3IBSqUR0dDQiIiKQkpJS7jZTU1Ohp6cHY2PjcvcbHBwMIyMjcbOyslLnUomIiIjoHfbGVydYvnw5bG1tYWdnBz09Pfj6+mLEiBHQ0nqzXc+cORMZGRnidvfu3TfaHxERERG9PWplkrVq1YK2tnaxVQHS0tJgbm5e4jmmpqaIjIxEdnY2EhMTcf36dcjlcjRs2LDcbZqbmyM/Px/p6enl7lcqlcLQ0FBlIyIiIqKqQa0kVk9PD05OToiJiRHLlEolYmJi0LZt25eeK5PJUKdOHRQWFuLXX39F7969y92mk5MTdHV1VerEx8cjKSmpzH6JiIiIqOrRUfcEPz8/eHt7w9nZGW3atEFISAiys7MxYsQIAMDw4cNRp04dBAcHAwBOnz6N5ORkODo6Ijk5GYGBgVAqlfj666/L3aaRkRFGjRoFPz8/1KxZE4aGhpg4cSLatm1brpUJiIiIiKhqUTuJHThwIB48eICAgACkpqbC0dERUVFR4oNZSUlJKvNdc3Nz4e/vj9u3b0Mul8Pd3R2bN29WeUirrDYBYNmyZdDS0oKnpyfy8vLg5uaGVatWvcKlExEREZGmUnudWE3FdWKJiIioorhO7NvxxtaJJSIiIiJ6FzCJJSIiIiKNwySWiIiIiDQOk1giIiIi0jhMYomIiIhI4zCJJSIiIiKNwySWiIiIiDQOk1giIiIi0jhMYomIiIhI4zCJJSIiIiKNwySWiIiIiDQOk1giIiIi0jhMYomIiIhI4zCJJSIiIiKNwySWiIiIiDQOk1giIiIi0jhMYomIiIhI4zCJJSIiIiKNwySWiIiIiDQOk1giIiIi0jhMYomIiIhI4zCJJSIiIiKNwySWiIiIiDQOk1giIiIi0jgVSmJXrlwJa2tryGQyuLi44MyZMy+tHxISgsaNG0NfXx9WVlaYMmUKcnNzxePW1taQSCTFtgkTJoh1OnfuXOz4uHHjKhI+EREREWk4HXVP2L59O/z8/LBmzRq4uLggJCQEbm5uiI+PR+3atYvVDw8Px4wZM7B+/Xq0a9cO//zzD3x8fCCRSLB06VIAwNmzZ6FQKMRzrly5go8//hgDBgxQaWvMmDEICgoS9w0MDNQNn4iIiIiqALWT2KVLl2LMmDEYMWIEAGDNmjXYu3cv1q9fjxkzZhSr/+eff6J9+/YYPHgwgGejrl5eXjh9+rRYx9TUVOWcb7/9FjY2NujUqZNKuYGBAczNzdUNmYiIiIiqGLWmE+Tn5+PcuXNwdXX9vwa0tODq6orY2NgSz2nXrh3OnTsnTjm4ffs29u3bB3d391L72LJlC0aOHAmJRKJybOvWrahVqxaaN2+OmTNnIicnp9RY8/LykJmZqbIRERERUdWg1kjsw4cPoVAoYGZmplJuZmaG69evl3jO4MGD8fDhQ3z00UcQBAGFhYUYN24cZs2aVWL9yMhIpKenw8fHp1g79evXh6WlJS5duoTp06cjPj4eERERJbYTHByMefPmqXN5RERERKQh1J5OoK6jR49i4cKFWLVqFVxcXHDz5k18+eWXmD9/PubMmVOs/rp169CjRw9YWlqqlI8dO1b82d7eHhYWFujWrRtu3boFGxubYu3MnDkTfn5+4n5mZiasrKxe45URERERUWVRK4mtVasWtLW1kZaWplKelpZW6lzVOXPmYNiwYRg9ejSAZwlodnY2xo4di9mzZ0NL6/9mNCQmJuLQoUOljq4+z8XFBQBw8+bNEpNYqVQKqVRa7msjIiIiIs2h1pxYPT09ODk5ISYmRixTKpWIiYlB27ZtSzwnJydHJVEFAG1tbQCAIAgq5WFhYahduzZ69uxZZixxcXEAAAsLC3UugYiIiIiqALWnE/j5+cHb2xvOzs5o06YNQkJCkJ2dLa5WMHz4cNSpUwfBwcEAAA8PDyxduhQtW7YUpxPMmTMHHh4eYjILPEuGw8LC4O3tDR0d1bBu3bqF8PBwuLu7w8TEBJcuXcKUKVPQsWNHtGjR4lWun4iIiIg0kNpJ7MCBA/HgwQMEBAQgNTUVjo6OiIqKEh/2SkpKUhl59ff3h0Qigb+/P5KTk2FqagoPDw8sWLBApd1Dhw4hKSkJI0eOLNannp4eDh06JCbMVlZW8PT0hL+/v7rhExEREVEVIBFe/Jt+FZWZmQkjIyNkZGTA0NCwssMhIiIiDZJTkAOX8GfP45wefBoGunzh0pugTr5WodfOEhERERFVJiaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcZhEktEREREGodJLBERERFpHCaxRERERKRxmMQSERERkcbRqewAiIiISJVSqUR+fn5lh0HPySvIg4WexbOfc/OgpeA4YEXo6upCW1v7tbRVoSR25cqVWLx4MVJTU+Hg4IDQ0FC0adOm1PohISFYvXo1kpKSUKtWLfTv3x/BwcGQyWQAgMDAQMybN0/lnMaNG+P69evifm5uLqZOnYpt27YhLy8Pbm5uWLVqFczMzCpyCURERO+k/Px8JCQkQKlUVnYo9ByloMT0RtMBAPfu3oOWhElsRRkbG8Pc3BwSieSV2lE7id2+fTv8/PywZs0auLi4ICQkBG5uboiPj0ft2rWL1Q8PD8eMGTOwfv16tGvXDv/88w98fHwgkUiwdOlSsV6zZs1w6NCh/wtMRzW0KVOmYO/evdi5cyeMjIzg6+uLfv364eTJk+peAhER0TtJEASkpKRAW1sbVlZW0NJiovSuUCgVUGY8+8XC2sga2lqvZzTxfSIIAnJycnD//n0AgIWFxSu1p3YSu3TpUowZMwYjRowAAKxZswZ79+7F+vXrMWPGjGL1//zzT7Rv3x6DBw8GAFhbW8PLywunT59WDURHB+bm5iX2mZGRgXXr1iE8PBxdu3YFAISFhaFJkyY4deoUPvzwQ3Uvg4iI6J1TWFiInJwcWFpawsDAoLLDoecolApo5Tz7pUImkzGJrSB9fX0AwP3791G7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Yszxs2fPVlZWlrKzsyVJqamp6t+/vzZu3KiuXbvKz8+vQc65srJSs2fP1v/8z//Iy8tLDz30kCZNmqRXX31VkvTqq68qKytL8+fPV+/evbVjxw6NGzdO1113nUaNGtUgNXzf+++/r6ioKL3//vvat2+fUlJS1KtXL40bN+6SY5555hnNmjVLzz33nP7yl79oxIgR+vLLL9WyZUsdPHhQ9913n9LS0jR27Fjt2LFDkyZNapTav88jqxOkp6dr8eLFWr58uXbv3q3x48frzJkzGjNmjCRp5MiRysjIMPsPGTJEixYt0sqVK3Xw4EFt2LBBmZmZGjJkiPmHCwAArM/Hx0fLli3T8uXLFRoaqoEDB2rq1Kn67LPPzD7nP/IODQ1VZGSk+bpnz5769a9/rW7duqlDhw7KyclRu3btLrpyeNttt+mJJ55Qu3bt1K5dO3P8+SusLVu2vGyNN990sxm2g4KCtGPHjjr71dTUKC8vT/Hx8erTp48mTJig/Px8c392drbmzJmje+65R3Fxcbrnnns0ceJEvfjiiz/+F1dPLVq00Pz589WpUyf96le/0uDBg11qqsvo0aM1fPhwtW/fXjNmzNDp06fNh+1ffPFFdezYUc8995w6duyoBx54QKNHj260+i/kkXtiU1JSdOzYMWVlZcnhcKhXr15av369+bBXSUmJy5XXp556SjabTU899ZSOHDmi1q1ba8iQIZo+fbonygcAwJICfAK05cEtHjt2fd17770aPHiwPvzwQ3388cd65513NGvWLL388suXDUinT5/W008/rbVr1+ro0aM6d+6czp49q5KSEpd+8fHxV3oakqQVr61Qt67dzNfR0dF1rrAUGBiodu3ama+joqLMNfHPnDmj/fv369FHH3W5Cnru3LlGfTisa9euLhcAo6KitHPnzsuO6dHju/t/r7vuOgUHB5vnUVxcrH79+rn079+/fwNWfGkee7BrwoQJl7x9YNOmTS6vfXx8lJ2dbV72BwAAP57NZqvXR/pNgb+/v+644w7dcccdyszM1NixY5WdnX3ZEDtp0iRt2LBBs2fPVvv27RUQEKD77rvvooe3rrvuuquqLTo6Wu3bt//Bfr6+vi6vbTabeRvk6dOnJUmLFy9WQoLrLR5X8imzl5fXRbdYXniv6+VqutTzRVczxh0ssToBAAC4tnXp0sVlSS1fX1/V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)



## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow

Exemplo de link: [Roboflow - Meios de Transportes]([google.com](https://app.roboflow.com/cesar-school-hcuas/meios-de-transportes/1))

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace
