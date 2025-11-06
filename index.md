Brendan Kuang
blkuang@ucsd.edu

> **What is the most interesting topic covered in your domain this quarter?**

1. The most interesting topic I've covered in my domain this quarter is the actual method by which functional accelerators are implemented on the hardware level. The tradeoff is that accelerators consume FPGA fabrice, and thus there is typically an inverse relationship between specificity and speed.

> **Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

2. One potential avenue that I've considered after implementing an LMUL Algorithm on the software level to verify its accuracy on an MLP neural network simple recognition test is to emulate LMUL on more types of neural networks (e.g LSTM, Transformer) to test its breadth of application. We could also investigate on how LMUL operates on more subjective and less deterministic tasks rather than class recognition.

> **What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

3. Currently, most of the LMUL speed tests we are doing are failing to show its benefits due to the gap between software and hardware. However, one solution would be to reimplement the speed tests in Verilog or some equivalent to measure clock cycles rather than use pure time on the software level.

> **What other techniques would you be interested in using in your project?**

4. One technique I'm really interested in is using general matrix multiplication optimization methods to further speed up inference time, for example the Strassens Matrix Multiplication Method, but this is something extremely costly project timeline wise.
