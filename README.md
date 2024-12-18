# MiniTorch Module 3

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html


You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/tensor.py minitorch/datasets.py minitorch/testing.py minitorch/optim.py

# 3.4 Timing Graph
<img src="images/Timing Graph.png" width="25%">

# Simple
![alt text](<images/Simple CPU Command.png>)
<img src="images/Simple CPU Logs.png" width="50%">
![alt text](<images/Simple GPU Command.png>)
<img src="images/Simple GPU Logs.png" width="50%">

# Split
![alt text](<images/Split CPU Command.png>)
<img src="images/Split CPU Logs.png" width="50%">
![alt text](<images/Split GPU Command.png>)
<img src="images/Split GPU Logs.png" width="50%">

# XOR
![alt text](<images/XOR CPU Command.png>)
<img src="images/XOR CPU Logs.png" width="50%">
![alt text](<images/XOR GPU Command.png>)
<img src="images/XOR GPU Logs.png" width="50%">

# Bigger Model (Simple)
![alt text](<images/Simple CPU Bigger Command.png>)
<img src="images/Simple CPU Bigger Logs.png" width="50%">
![alt text](<images/Simple GPU Bigger Command.png>)
<img src="images/Simple GPU Bigger Logs.png" width="50%">