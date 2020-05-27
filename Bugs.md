# Bug_Solution
Log for all the bugs that I met and its solution.
* Mujoco Library in Pycharm
```
Please add following line to .bashrc:
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/ssz/.mujoco/mujoco200/bin
```
> https://github.com/openai/mujoco-py/issues/267

> click Run -> Edit Configurations -> Environment Variables
> Add
> `LD_LIBRARY_PATH /path/to/.mujoco/mjpro150/bin`
> `MUJOCO_KEY_PATH /path/to/.mujoco`

## Pyspider
* Python==3.5
* wsgidav==2.4.1
* werkzeug==0.16.0
