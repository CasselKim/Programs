# 필수프로그램 for developer
본 마크다운은 포맷 후에 프로그램들 따로따로 받기 귀찮아서 적는 글입니다.  

[Python](https://www.python.org/downloads/)
![image](https://user-images.githubusercontent.com/48755377/62468941-2d262300-b7d2-11e9-85e5-b962cd1b168a.png)  ![image](https://user-images.githubusercontent.com/48755377/62469076-7f674400-b7d2-11e9-9a3f-bffba342a18e.png)

  

[Anaconda](https://www.anaconda.com/distribution/)
![image](https://user-images.githubusercontent.com/48755377/62469227-cd7c4780-b7d2-11e9-95bd-a5e82540e91e.png)
![image](https://user-images.githubusercontent.com/48755377/62469420-3368cf00-b7d3-11e9-8e52-5c17c7aeb3e8.png)

  

[Pycharm](https://www.jetbrains.com/pycharm/download/#section=windows)
![image](https://user-images.githubusercontent.com/48755377/62469569-788d0100-b7d3-11e9-8380-e7f3a17b3115.png)
![image](https://user-images.githubusercontent.com/48755377/62469775-edf8d180-b7d3-11e9-8cc3-d8923f124fe4.png)

  

[Visualstudio](https://visualstudio.microsoft.com/ko/downloads/) (cuda 받기 전에 먼저 받아주세요)
![image](https://user-images.githubusercontent.com/48755377/62470605-c30f7d00-b7d5-11e9-802e-aa9998e9ccc9.png)

  

[cuda](https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exelocal) (텐서플로우2.0부터는 cuda 10.0 사용가능)
![image](https://user-images.githubusercontent.com/48755377/62469915-37e1b780-b7d4-11e9-8527-13332163f5bf.png)

  

[cuDNN](https://developer.nvidia.com/rdp/cudnn-download)
![image](https://user-images.githubusercontent.com/48755377/62470119-ab83c480-b7d4-11e9-8d69-199b042494dd.png)
![image](https://user-images.githubusercontent.com/48755377/62471705-30bca880-b7d8-11e9-90bb-e9a01e76e7db.png)
![image](https://user-images.githubusercontent.com/48755377/62471664-1a165180-b7d8-11e9-97bb-0defc19f7a58.png)
`conda create -y -n cuda ipykernel`
`activate cuda`
`pip install tensorflow-gpu==2.0.0-beta1`

`conda create -y -n pytorch ipykernel`
`activate pytorch`
`conda install pytorch torchvision cudatoolkit=10.1 -c pytorch`  



[Typora](https://typora.io/#windows)  

[git](https://git-scm.com/downloads)