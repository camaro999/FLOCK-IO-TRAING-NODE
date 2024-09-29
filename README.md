# FLOCK-IO-TRAING-NODE
FLOCK.IO TRAING NODE GUID
-INSTALL WSL
wget https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh 

bash Anaconda3-2024.06-1-Linux-x86_64.sh 

source ~/anaconda3/bin/activate

conda update conda

source ~/.bashrc

conda --version

- Main Install
  
$git clone https://github.com/FLock-io/testnet-training-node-quickstart.git
$conda create -n training-node python==3.10
$conda activate training-node
$cd testnet-training-node-quickstart
$pip install -r requirements.txt

- ENV

$env:TASK_ID="<task-id>"
$env:FLOCK_API_KEY="<your-flock-api-key-stakes-as-node-for-the-task>"
$env:HF_TOKEN="<your-hf-token>"
$env:HF_USERNAME="your-hf-user-name"
$env:CUDA_VISIBLE_DEVICES=0
python full_automation.py

