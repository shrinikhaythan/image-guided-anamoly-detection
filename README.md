# Image-Guided Anomaly Detection (CV Pipeline)

**Real-time surgical defect detection using CNN segmentation + diffusion reconstruction + explainable heatmaps .** 

## Production Pipeline
| Step | Technology | Industrial Application |
|------|------------|----------------------|
| **Segmentation** | U-Net (CNN) | Part boundary detection |
| **Reconstruction** | DDPM/DDIM | Normal part generation |
| **Anomaly Map** | Residual Heatmaps | **Defect localization** |
| **Decision** | Traffic-light scoring | PASS/FAIL classification |
| **logical reasoning and raising alerts ** | agentic ai  | langgraph  |
## Technical Report and architecture diagram  attached in repo 
**Scales from medical CT → manufacturing inspection.**


