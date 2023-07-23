# PPO
Basic implementation of Proximal Policy Gradient [(PPO)](https://arxiv.org/abs/1707.06347) which is largely based on the implementation available [here](https://github.com/rraileanu/idaac).

# Dependencies
Run the following to create the environment and install the required dependencies: 
```
conda create -n ppo python=3.7
conda activate ppo

cd ppo-template
pip install -r requirements.txt

pip install procgen

pip install protobuf==3.20.0

git clone https://github.com/openai/baselines.git
cd baselines 
python setup.py install 
```


# Instructions 

### To train ppo on Bigfish
```
python train.py --env_name bigfish
```

