# ATML_PA6
## Pre-trained Model Weights

Due to file size constraints, pre-trained model weights are hosted separately on Google Drive.

---

### **Task 2: LLM Alignment**

**Download Link:** [Google Drive - PA5 Task 2 Weights](https://drive.google.com/drive/folders/1Ai9BFI0nnOQ6WIf4pof-ymotBKDZjwXP)

#### Available Checkpoints:
- **DPO:** `model_dpo_final.pth`
- **Reward Model:** `model_reward_final.pth`
- **PPO Sparse:** `model_ppo_sparse_final.pth`
- **PPO Dense:** `model_ppo_dense_final.pth`
- **GRPO:** `model_grpo_final.pth`

#### Setup Instructions:
1. Download the checkpoint files from the Google Drive link
2. Place them in the pth_models directory of Task 2 (make one):
```
LLM_Alignment/pth_models
├── model_dpo_final.pth
├── model_reward_final.pth
├── model_ppo_sparse_final.pth
├── model_ppo_dense_final.pth
└── model_grpo_final.pth
```
3. Run the evaluation scripts (weights will be loaded automatically)

**Note:** If checkpoints are missing, the training scripts will automatically retrain from scratch.

---
