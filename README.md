# USCS-Dataset
### 📌 **Overview**

The Unmanned Swarm Combat Situation (USCS) Image Dataset is based on battlefield scenarios involving unmanned swarm combat, where situational information includes various types of combat units from the red and blue sides, intent trajectories, and combat interferences. The dataset is divided into four types of situational categories: Offensive, Defensive, Encirclement, and Maneuver tactics. With its standardized visual representation system, the USCS dataset provides a reliable benchmark for unmanned swarm combat situation analysis and decision-making, making it an ideal dataset for testing the accuracy and interpretability of SISA-CapsNet in situational image classification tasks  

## 📁 **Dataset Structure**

- **Directory Structure** 📂

  ```
  - USCS-Dataset/             # Dataset directory
  │   ├── train/              # Train data
  │   │   ├── Offensive/
  │   │   ├── Defensive/
  │   │   ├── Encirclement/
  │   │   ├── Maneuver/
  │   ├── test/               # Test data
  │   │   ├── Offensive/
  │   │   ├── Defensive/
  │   │   ├── Encirclement/
  │   │   ├── Maneuver/
  ```

- Data Format

  - Image data: PNG format, resolution 77×77
