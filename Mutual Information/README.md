# Mutual Information 학습 커리큘럼

## 1. 확률/통계 기초
- **목표:** 확률변수와 분포 이해
- **핵심 개념:**
  - Random Variable (X, Y)
  - PMF / PDF / CDF
  - Expectation (기댓값), Variance (분산)
  - Conditional Probability (조건부 확률)
  - Independence (독립성)

---

## 2. 정보이론
- **목표:** 정보량과 엔트로피 이해
- **핵심 개념:**
  - Entropy \(H(X), H(Y)\)
  - Conditional Entropy \(H(X|Y)\)
  - KL Divergence \(D_{KL}(P||Q)\)

---

## 3. Mutual Information 정의
- **목표:** MI의 수학적 정의와 직관 이해
- **핵심 개념:**
  - \(I(X;Y) = H(X) - H(X|Y)\)
  - \(I(X;Y) = D_{KL}(P(X,Y) || P(X)P(Y))\)
  - Joint / Marginal Distribution 이해
  - 연속형 / 이산형 확률변수 MI 계산

---

## 4. 샘플 기반 MI 추정
- **목표:** 실제 데이터에서 MI 계산
- **핵심 개념:**
  - Monte Carlo 기반 추정
  - Neural Estimation
    - MINE (Mutual Information Neural Estimator)
    - InfoNCE (Contrastive Learning 기반 MI lower bound)
  - Invariance / Data Augmentation 활용

---

## 5. 딥러닝 활용
- **목표:** Unsupervised Representation Learning에서 MI 활용
- **핵심 개념:**
  - IIC (Invariant Information Clustering)
  - Contrastive Learning (SimCLR, InfoNCE)
  - Representation Learning & Regularization
