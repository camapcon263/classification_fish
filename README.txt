# Mô tả dữ liệu (thư mục data): 

Bộ dữ liệu chứa 9 loại hải sản khác nhau được thu nhập từ một siêu thị Izmir, Thổ Nhị Kì được xuất bản trong ASYU 2020.

Trích dẫn:
@inproceedings{ulucan2020large,
  title={A Large-Scale Dataset for Fish Segmentation and Classification},
  author={Ulucan, Oguzhan and Karakaya, Diclehan and Turkan, Mehmet},
  booktitle={2020 Innovations in Intelligent Systems and Applications Conference (ASYU)},
  pages={1--5},
  year={2020},
  organization={IEEE}
}

Bộ dữ liệu bao gồm:
- gilt head bream (cá tráp đầu vàng)
- red sea bream (cá tráp đỏ)
- sea bass (cá vược)
- red mullet (cá đối đỏ)
- horse mackerel (cá thu ngựa)
- black sea sprat (cá trích biển đen)
- striped red mullet (cá đối đỏ sọc)
- trout (cá hồi)
- shrimp image (tôm)

Tập dữ liệu có kích thước 590x445, tất cả các nhãn dữ liệu đã được tăng cường (bằng cách lật và xoay ảnh) tổng số hình ảnh cho mỗi lớp là 2000; 1000 hình ảnh cá RGB và 1000 ground truth theo cặp của chúng.

## Fish_Dataset:
- Mỗi lớp được lưu trữ trong một tệp riêng, trong mỗi tệp bao gồm 2 thư mục con chứa: 1000 ảnh RGB và 1000 nhãn Ground Truth.
- Tất cả các hình ảnh cho mỗi lớp được sắp xếp từ "00000.png" đến "01000.png".
## NA_Fish_Dataset:
- Tập dữ liệu được sử dụng để kiểm tra mô hình, với mỗi loại cá có 50 ảnh, tôm có 30 ảnh.
- Tất cả ảnh được đặt tên từ "00001.png" đến "00050.png"

# Mô tả mô hình (thư mục model)
- Mô hình Logistic_regression
- Mô hình mạng CNN

# Link git: https://github.com/vannt263/classification_fish.git