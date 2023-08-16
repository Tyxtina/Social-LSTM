# Social-LSTM
summer3
fork from Implementation of Social LSTM: Human Trajectory Prediction in Crowded Spaces
数据格式
frame_number    pedestrian_number   y_coordinates   x_coordinates
训练数据及验证在终端输入以下命令
python main.py mode --dataset [dataset_name] --epoch [epoch_num] --T_obs [observe_step] --T_pred [predict_step]
如python main.py "s" --dataset "eth" --epoch 3 
