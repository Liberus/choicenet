# ChoiceNet
TensorFlow Implementation of ChoiceNet on regression tasks. 

### Summarized result: 
[Classification](https://rawgit.com/sjchoi86/choicenet/master/html/cls_results.html)
[Regression](https://rawgit.com/sjchoi86/choicenet/master/html/reg_results.html)

### Paper: [arxiv](https://arxiv.org/abs/1805.06431)

### Classification (MNIST) Result
<html><body><table><caption> Error type: [Permutation] </caption><tr><th> name </th><th> Result </th></tr><tr><td>Outlier Rate: 25.0%</td><td><img src='fig/fig_mnistRes_rp_25.png'></td></tr><tr><td>Outlier Rate: 45.0%</td><td><img src='fig/fig_mnistRes_rp_45.png'></td></tr><tr><td>Outlier Rate: 47.5%</td><td><img src='fig/fig_mnistRes_rp_47.png'></td></tr><br></body></table><body><table><caption> Error type: [Random Shuffle] </caption><tr><th> name </th><th> Result </th></tr><tr><td>Outlier Rate: 50.0%</td><td><img src='fig/fig_mnistRes_rs_50.png'></td></tr><tr><td>Outlier Rate: 90.0%</td><td><img src='fig/fig_mnistRes_rs_90.png'></td></tr><tr><td>Outlier Rate: 95.0%</td><td><img src='fig/fig_mnistRes_rs_95.png'></td></tr><br></body></table><body><table><caption> Error type: [Label Bias] </caption><tr><th> name </th><th> Result </th></tr><tr><td>Outlier Rate: 25.0%</td><td><img src='fig/fig_mnistRes_b_25.png'></td></tr><tr><td>Outlier Rate: 45.0%</td><td><img src='fig/fig_mnistRes_b_45.png'></td></tr><tr><td>Outlier Rate: 47.5%</td><td><img src='fig/fig_mnistRes_b_47.png'></td></tr><br></body></table></html>


### Regression Result
<html><body><table><caption> Reference Function: [cosexp] </caption><tr><th> name </th><th> Training Data </th><th> Multi-Layer Perceptron </th><th> Mixture Density Network </th><th> ChoiceNet </th></tr><tr><td>oRate: 0.0%</td><td><img src='fig/fig_MLP_cosexp_oRate0_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_cosexp_oRate0_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_cosexp_oRate0_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_cosexp_oRate0_var1.0e-06_res.png'></td></tr><tr><td>oRate: 10.0%</td><td><img src='fig/fig_MLP_cosexp_oRate10_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_cosexp_oRate10_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_cosexp_oRate10_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_cosexp_oRate10_var1.0e-06_res.png'></td></tr><tr><td>oRate: 30.0%</td><td><img src='fig/fig_MLP_cosexp_oRate30_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_cosexp_oRate30_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_cosexp_oRate30_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_cosexp_oRate30_var1.0e-06_res.png'></td></tr><tr><td>oRate: 50.0%</td><td><img src='fig/fig_MLP_cosexp_oRate50_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_cosexp_oRate50_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_cosexp_oRate50_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_cosexp_oRate50_var1.0e-06_res.png'></td></tr><tr><td>oRate: 60.0%</td><td><img src='fig/fig_MLP_cosexp_oRate60_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_cosexp_oRate60_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_cosexp_oRate60_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_cosexp_oRate60_var1.0e-06_res.png'></td></tr><tr><td>oRate: 70.0%</td><td><img src='fig/fig_MLP_cosexp_oRate70_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_cosexp_oRate70_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_cosexp_oRate70_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_cosexp_oRate70_var1.0e-06_res.png'></td></tr><br></body></table><body><table><caption> Reference Function: [linear] </caption><tr><th> name </th><th> Training Data </th><th> Multi-Layer Perceptron </th><th> Mixture Density Network </th><th> ChoiceNet </th></tr><tr><td>oRate: 0.0%</td><td><img src='fig/fig_MLP_linear_oRate0_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_linear_oRate0_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_linear_oRate0_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_linear_oRate0_var1.0e-06_res.png'></td></tr><tr><td>oRate: 10.0%</td><td><img src='fig/fig_MLP_linear_oRate10_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_linear_oRate10_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_linear_oRate10_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_linear_oRate10_var1.0e-06_res.png'></td></tr><tr><td>oRate: 30.0%</td><td><img src='fig/fig_MLP_linear_oRate30_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_linear_oRate30_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_linear_oRate30_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_linear_oRate30_var1.0e-06_res.png'></td></tr><tr><td>oRate: 50.0%</td><td><img src='fig/fig_MLP_linear_oRate50_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_linear_oRate50_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_linear_oRate50_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_linear_oRate50_var1.0e-06_res.png'></td></tr><tr><td>oRate: 60.0%</td><td><img src='fig/fig_MLP_linear_oRate60_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_linear_oRate60_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_linear_oRate60_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_linear_oRate60_var1.0e-06_res.png'></td></tr><tr><td>oRate: 70.0%</td><td><img src='fig/fig_MLP_linear_oRate70_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_linear_oRate70_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_linear_oRate70_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_linear_oRate70_var1.0e-06_res.png'></td></tr><br></body></table><body><table><caption> Reference Function: [step] </caption><tr><th> name </th><th> Training Data </th><th> Multi-Layer Perceptron </th><th> Mixture Density Network </th><th> ChoiceNet </th></tr><tr><td>oRate: 0.0%</td><td><img src='fig/fig_MLP_step_oRate0_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_step_oRate0_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_step_oRate0_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_step_oRate0_var1.0e-06_res.png'></td></tr><tr><td>oRate: 10.0%</td><td><img src='fig/fig_MLP_step_oRate10_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_step_oRate10_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_step_oRate10_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_step_oRate10_var1.0e-06_res.png'></td></tr><tr><td>oRate: 30.0%</td><td><img src='fig/fig_MLP_step_oRate30_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_step_oRate30_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_step_oRate30_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_step_oRate30_var1.0e-06_res.png'></td></tr><tr><td>oRate: 50.0%</td><td><img src='fig/fig_MLP_step_oRate50_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_step_oRate50_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_step_oRate50_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_step_oRate50_var1.0e-06_res.png'></td></tr><tr><td>oRate: 60.0%</td><td><img src='fig/fig_MLP_step_oRate60_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_step_oRate60_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_step_oRate60_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_step_oRate60_var1.0e-06_res.png'></td></tr><tr><td>oRate: 70.0%</td><td><img src='fig/fig_MLP_step_oRate70_var1.0e-06_data.png'></td><td><img src='fig/fig_MLP_step_oRate70_var1.0e-06_res.png'></td><td><img src='fig/fig_MDN_step_oRate70_var1.0e-06_res.png'></td><td><img src='fig/fig_CN_step_oRate70_var1.0e-06_res.png'></td></tr><br></body></table></html>

### HowTo?
- run code/main_reg_run.ipynb
- Properly modify followings based on the working environment:
```python
nWorker = 16
maxGPU  = 8
```
- (I was using 16 CPUs / 8 TESLA P40s / 96GB RAM.)

### Requirements
- Python3
- TF 1.4>= 

### Contact
- sungjoon.s.choi@gmail.com
- leo.brain@kakaobrain.com
- ian.theman@kakaobrain.com

This work was done in Kakao Brain. 
