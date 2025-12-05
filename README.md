# SwinIR Model Optimization




## 🔹 실행법 (How to Run)

### ☝️ Colab에서 실행 : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/06unoh/model_optimization/blob/main/model_optimization_final.ipynb)


## 🔹 결과

| 항목 | FP32 | INT8 | 결과 |
|------|-----:|-----:|------:|
| 모델 크기 | 64.17MB | 37.10MB | 약 42.19% 경량화 |
| 추론 속도 | 약 737초 | 약 41초 | 약 94% 속도 개선 |
| 평균 DIFF | - | - | -2.50E-07 |
| MSE | - | - | 1.35E-06 |
| PSNR | - | - | 58.68dB |

→ 모델 경량화 및 속도 개선과 동시에 품질은 FP32와 동등한 수준

---
📄 [Work Details](https://portfolio-unoh.site/optim)  
🛠 Developed by 06unoh 
