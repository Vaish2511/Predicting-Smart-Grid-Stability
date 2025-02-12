# Predicting-Smart-Grid-Stability

## Description:
This project predicts smart grid stability using machine learning models in a decentralized environment. By integrating a differential equation-based Decentralized Smart Grid Control (DSGC) model with neural networks, it analyzes grid behavior under fluctuating Renewable Energy Sources (RES), achieving 92% classification accuracy.

## Key Features:
1. Smart Grid Stability Assessment: Utilizes machine learning models to evaluate the stability of the electric grid in real-time, factoring in fluctuations from Renewable Energy Sources (RES).
2. Decentralized Control Model: The DSGC framework ensures that grid control remains decentralized, enhancing the robustness and flexibility of the system.
3. Neural Network Integration: Combines differential equations with neural network architectures for enhanced prediction accuracy and stability assessment.
4. Real-time Predictions: Provides real-time stability predictions for the grid, helping in proactive grid management.
5. High Accuracy: Achieved a binary classification accuracy of 92% in predicting grid stability, offering reliable insights for system operators.

## Dataset:
This project uses the "Electrical Grid Stability Simulated Dataset," which simulates a 4-node star network comprising one energy supplier and three consumers. The dataset consists of 60,000 observations after augmentation (originally 10,000). Each observation contains 12 predictive features related to the grid's dynamic behavior and two dependent variables, including a binary label for grid stability (stable or unstable).

## Feature Description:
1. Reaction times (τ1 to τ4): Represent the response times of each network participant to changes in energy pricing.
2. Nominal power produced or consumed (p1 to p4): Measure energy production (positive values) and consumption (negative values). The balance between total energy produced and consumed is critical for stability.
3. Price elasticity coefficients (g1 to g4): Reflect how participants' energy consumption or production behavior changes in response to price fluctuations.
The dependent variable 'stabf' is a binary label representing grid stability (1 = stable, 0 = unstable). This label will be the target for the classification models.

## Techonologies Used:
1. Machine Learning Libraries (E.g.,TensorFlow, Sci-Kit)
2. Data Processing Libraries (E.g., Pandas, NumPy)

## Target Audience:
1. Energy Researchers: Scholars focused on energy systems, smart grid technologies, and renewable energy integration.
2. Power Grid Operators: Professionals managing and monitoring electric grids, especially in regions transitioning to renewable energy.
3. Data Scientists & Machine Learning Engineers: Those interested in applying machine learning to large-scale systems like energy infrastructure.
4. Policy Makers & Regulators: Individuals involved in energy policy and regulation who need insights into the stability and efficiency of the grid.
5. Utility Companies: Companies operating in the electric grid sector, looking to improve grid performance and reduce downtimes through predictive analysis.

## Why it Matters:
As renewable energy sources (RES) become more integrated into the global energy mix, the stability of the electric grid faces significant challenges due to their fluctuating nature. Predicting grid instability using machine learning offers a promising solution for enhancing grid reliability and efficiency. This project contributes to energy resilience by providing tools to predict and prevent potential grid failures, ensuring a stable power supply for consumers and improving the integration of renewable energy. It also helps mitigate the risks associated with decentralized grid operations, making energy infrastructure more sustainable and adaptable to the challenges of climate change.
