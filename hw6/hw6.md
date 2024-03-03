# CS 601.471/671: Self-supervised Models
## Homework 6: Finetuning, PEFT, and In-context Learning

### Overview
In this programming homework, we will finetune encoder LMs for a classification task with yes/no questions. In
particular, we will
- Implement full-parameter finetuning.
- Explore various parameter-efficient finetuning strategies.

Additionally, we will also experiment with in-context learning using GPT-3.5 models via OpenAI APIs
### Setup
create a new environment for this homework:
```
conda create -n ssm_hw6 python=3.10.13
```

And install the required packages:
```
cd hw6
conda activate ssm_hw6
pip install -r requirements.txt
```

### Run the code
You can create your own sbatch scripts to run the code.

### Submission
Please follow the instructions in the homework pdf.


### Code
slurm-10134352.out, 10137613 : default 30 epoch
slurm-10136622.out : 1e-4 lr; 7 epoch; 64 batch
slurm-10136866.out : 5e-4 lr; 7 epoch; 64 batch
slurm-10137313.out : 1e-3 lr; 7 epoch; 64 batch