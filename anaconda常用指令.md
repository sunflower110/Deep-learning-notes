# anaconda常用指令
## 创建环境
# 加载anaconda环境
module load anaconda/2020.11

# 创建环境
conda create -n py37 python=3.7

# 已安装环境
conda env list
# conda --info envs

# 激活环境
source activate py37

# 取消激活当前环境
source deactivate py37

# 安装所需软件
conda install pytorch torchvision torchaudio pytorch-cuda=11.6 -c pytorch -c nvidia

# 查看已安装库
conda list

# 删除Python环境
conda remove --name myenv --all
conda env remove --name myenv
