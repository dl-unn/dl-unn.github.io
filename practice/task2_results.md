# Results of Task 2

| Name                                                               | Test accuracy, %  | NN architecture|
|--------------------------------------------------------------------|-------------------|----------------|
| Alexey Sidnev (example)                                            |       59.2        | 1. Conv2D(3x3, ReLU, stride=2, out=20)<br>2. Conv2D(3x3, ReLU, stride=2, out=40)<br>3. Conv2D(3x3, ReLU, stride=2, out=80)<br>4. Fully connected (out=10)<br>5. Softmax 
| Batanina Liubov                                                    |       66.75       | 1. Conv2D(3x3, ReLU, padding="same", stride=1, out=32)<br>2. MaxPooling(2x2, stride=2)<br>3. BatchNormalization()<br>4. Conv2D(3x3, ReLU, padding="same", stride=1, out=64)<br>5. MaxPooling(2x2, stride=2)<br>6. BatchNormalization()<br>7. Conv2D(3x3, ReLU, padding="same", stride=1, out=128)<br>8. MaxPooling(2x2, stride=2)<br>9. BatchNormalization()<br>10. Flatten()<br>11. Fully connected(ReLU, out=128)<br>12. Dropout(0.1)<br>13. Fully connected (out=10)<br>14. Softmax
| Krasikova Ekaterina                                                |                   |                |
| Okunev Boris                                                       |                   |                |
| Zinoviev Vladimir                                                  |                   |                |
| Panova Elena                                                       |                   |                |
| Kuznetsov Vladislav                                                |                   |                |
| Degtyarev Anton                                                    |       53.44       | 1. Flatten()<br>2. FullyConnected(units=1024), Elu<br>3. FullyConnected(units=512), Elu<br>4. FullyConnected(units=10)<br>5. Softmax               |
| Rodionov Fedor                                                     |       49.5        | 1. Fully connected (out=256), ReLU <br>2. Fully connected (out=64), ReLU <br>3. Fully connected (out=10), ReLU <br>4. Softmax        |
| Panov Aleksandr                                                    |                   |                |
| Senyaev Andrey                                                     |                   |                |
| Kamelina Julia                                                     |                   |                |
| Protas Maria                                                       |                   |                |
| Romanov Alexander                                                  |                   |                |
| Kuznetsov Konstantin                                               |                   |                |
| Tarasov Oleg                                                       |                   |                |
| Mayachkin Arseny                                                   |                   |                |
| Usova Marina                                                       |                   |                |
| Shkenev Petr                                                       |                   |                |
| Daniil Roman                                                       |                   |                |
| Gribov Pavel                                                       |                   |                |
| Tarakanov Kirill                                                   |       54.79       | 1. Fully connected(out=256, activation=sigmoid)<br>2. Fully connected(out=128, activation=sigmoid)<br>3. Fully connected (out=10)<br>4. Softmax
| Gladyshev Alexey                                                   |                   |                |
| Nechesanov Vladimir                                                |                   |                |
| Ananiev Semyon                                                     |                   |                |
| Generalov Alexander                                                |                   |                |
| Trifonov Alexander                                                 |                   |                |
| Shutina Svetlana                                                   |                   |                |
| Kuznetsov Victor                                                   |       45.18       | 1. Fully connected (out=1100), ReLU <br>2. Fully connected (out=1100), ReLU <br>3. Fully connected (out=10), ReLU <br>4. Softmax
| Israfilov Marat                                                    |       51.02       | 1. Fully connected (ReLU, out=1024)<br>2. Fully connected (ReLU, out=512)<br>3. Fully connected (ReLU, out=256)<br>4. Fully connected (out=10)<br>5. Softmax
