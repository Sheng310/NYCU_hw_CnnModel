# NYCU_hw_CnnModel
Pytorch 模型儲存


# 儲存
torch.save(net, '310605008_CnnModel.pt')


# 載入
放入Test on held out data，net.eval()的前面

!rm -rf NYCU_HW

!git clone https://github.com/Sheng310/NYCU_hw_CnnModel.git

net = torch.load("./NYCU_hw_CnnModel/310605008_CnnModel.pt")
