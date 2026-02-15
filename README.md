## For Training
1. download the Fill50K dataset
2. extract to `/training` 
3. try running `python tutorial_dataset_test.py`, if output with shape of the dataset, go ahead
4. download the .ckpt files to `/models` and the run `python tool_add_control.py ./models/v1-5-pruned.ckpt ./models/control_sd15_ini.ckpt`
5. next, train with `python tutorial_train.py`
