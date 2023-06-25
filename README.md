# Mobile Edge Computing Task Offloading


### Vấn đề
**Mobile Edge Computing** mang lại nhiều lợi ích với khả năng hiệu suất cao, giảm tiêu thụ năng lượng, xử lý thời gian thực và mở ra các ứng dụng mới như *5G, VR,...*

Tuy nhiên một nút edge có thể tải cao khi có nhiều tác vụ chuyển đến vượt quá khả năng xử lý gây ra độ trễ lớn hoặc bị loại bỏ nếu nó có ràng buộc về thời gian.

Nghiên cứu này xem xét các tác vụ không thể phân chia và nhạy cảm với độ trễ ( binary task offloading). Đề xuất xây dựng một vấn đề phân tải các tác vụ để giảm thiểu chi phí.

### Mô hình 


* System
  Thiết bị M, nút biên N, episode T mỗi lượt có thời gian $\Delta$
  ![image](https://github.com/drpsy/MEC_taskOffloading/assets/87910428/4171a579-e62a-4d3f-b2f1-77f106c9154d)

* DRL-BASED OFFLOADING ALGORITHM (Deep Reinforcement Learning)
    Based on Deep Q-learning
* Network:
  LSTM layer,FC layers, dueling DQN
  
 ![image](https://github.com/drpsy/MEC_taskOffloading/assets/87910428/475c40c9-9239-47fd-aa2f-b861a31c9f96)

  

### Training
* Parameter used
  
![image](https://github.com/drpsy/MEC_taskOffloading/assets/87910428/ff039725-2bb1-4390-846c-bc2d1a6389dc)




![image](https://github.com/drpsy/MEC_taskOffloading/assets/87910428/d7ed9bb3-8db3-4a26-b300-2c2751dc477d)


### Evaluation

![image](https://github.com/drpsy/MEC_taskOffloading/assets/87910428/be4cd789-7f36-476d-a005-ae773cb42d12)


* Paper tham khảo cho bài toán : [](https://ieeexplore.ieee.org/document/9253665)





