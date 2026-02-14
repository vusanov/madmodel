
# **Please read my Introduction part to understand my whole goal🤭)**

---
***Introduction***

House price prediction is a very common problem and can be easily done by anyone, my main purpose is not to solve this problem again, but to use different methods and techniques to experiment on the same problem and better understand how those techniques are applied in depth to many big problems in the field of deep learning.

***Techniques are applied:***

`Batch Normalization`: to keep the output values ​​at each layer always having a mean of 0 and a variance of 1 (also known as Guassian distribution).

`Residual Connection`: Avoid the phenomenon of vanishing derivatives by adding a layer of input values ​​of that layer to the layer of output values ​​of that layer (especially after ReLU activation when it turns all the negative values into 0, but Residual Connection brings them back again and gives other layers a shot to handle them). 

`Cosine annealing scheduler`: helps LR decrease according to the Cosine function curve. It starts off slow, then drops very fast in the middle and slows down at the end.

***Dataset***

This included `Hanoi_housing_dataset.csv`, as an example, has the most common 82497 home information from Hanoi in 2019 and 2022. It looks like:

| Ngày | Địa chỉ | Quận | Huyện | Loại hình nhà ở | Giấy tờ pháp lý | Số tầng | Số phòng ngủ | Diện tích | Dài | Rộng | Giá/m2 |
| :--- | :--- | :--- | :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| 8/5/2020 | Đường Hoàng Quốc Việt, Phường Nghĩa Đô, Quận Cầu Giấy, Hà Nội | Quận Cầu Giấy | Phường Nghĩa Đô | Nhà ngõ, hẻm | Đã có sổ | 4 | 5 phòng | 46 m² | NaN | NaN | 86,96 triệu/m² |
| 8/5/2020 | Đường Kim Giang, Phường Kim Giang, Quận Thanh Xuân, Hà Nội | Quận Thanh Xuân | Phường Kim Giang | Nhà mặt phố, mặt tiền | NaN | NaN | 3 phòng | 37 m² | NaN | NaN | 116,22 triệu/m² |
| 8/5/2020 | phố minh khai, Phường Minh Khai, Quận Hai Bà Trưng, Hà Nội | Quận Hai Bà Trưng | Phường Minh Khai | Nhà ngõ, hẻm | Đã có sổ | 4 | 4 phòng | 40 m² | 10 m | 4 m | 65 triệu/m² |
...

Have fun!

