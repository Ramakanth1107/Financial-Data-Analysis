A Study on Liquid Neural Networks for Time-Series Forecasting 📈🤖
Project Overview 🌟
This capstone project evaluates the performance of Liquid Neural Networks (LNNs) in forecasting sequential data, focusing on stock price prediction using Tata Steel data from Kaggle. The study compares LNNs against traditional models like ARIMA, SARIMA, and deep learning models like LSTM and GRU, highlighting LNNs' adaptability to non-linear and volatile time-series patterns.
Key Features ✨

Dataset 📊: Tata Steel stock data with Date and Open price, sourced from Kaggle.
Data Preprocessing 🧹:
Handled missing values and outliers.
Normalized data using MinMaxScaler.
Applied windowing for sequence creation.


Models Implemented 🧠:
LNN: Custom Liquid Time-Constant (LTC) cell for dynamic adaptability.
LSTM & GRU: Deep learning models for long-term dependencies.
ARIMA & SARIMA: Statistical models for linear and seasonal trends.


Evaluation Metrics 📉:
Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
LNN achieved the lowest loss (2.3427e-04) and an R² of 99.1%.


Tools & Libraries 🛠️:
Python: Pandas, NumPy for data handling.
Visualization: Matplotlib, Seaborn for plots.
Machine Learning: TensorFlow, Statsmodels, Scikit-learn.



Project Structure 📂
├── data/
│   └── TATASTEEL.csv              # Stock dataset 📄
├── notebooks/
│   └── LLN_analysis.ipynb    # Jupyter Notebook with code 📓
├── README.md                      # Project documentation 📖
└── requirements.txt               # Dependencies ⚙️

Installation & Setup 🚀

Clone the repository:
git clone https://github.com/your-username/liquid-neural-networks.git


Install dependencies:
pip install -r requirements.txt


Run the Jupyter Notebook:
jupyter notebook notebooks/capstone_analysis.ipynb



Results 🎉

Model Performance 📊:
LNN: Lowest loss (2.3427e-04) and R² of 99.1%, excelling in capturing non-linear patterns.
LSTM: Loss of 2.3665e-04, R² of 99.1%.
GRU: Loss of 2.7349e-04, R² of 99.1%.
ARIMA: R² of 87.8%, loss of 19.706.
SARIMA: R² of 86.7%, loss of 19.560.


Key Insights 🔍:
Neural network models (LNN, LSTM, GRU) outperformed statistical models in accuracy.
LNN's dynamic adaptability makes it ideal for volatile financial data.
ARIMA and SARIMA are computationally efficient but struggle with non-linear trends.



Future Improvements 🔧

Explore hybrid models combining statistical and neural network strengths 🌐.
Incorporate attention mechanisms or ensemble methods for enhanced accuracy 🚀.
Extend to other domains like healthcare or weather forecasting 🌍.
Optimize LNN hyperparameters for faster convergence ⚡.

Dependencies ⚙️

Python 3.8+ 🐍
Pandas 🐼
NumPy 🔢
Matplotlib 📈
Seaborn 🎨
TensorFlow 🧠
Statsmodels 📊
Scikit-learn 🔍
Jupyter Notebook 📓

License 📜
This project is licensed under the MIT License.
Acknowledgments 🙏
Special thanks to Dr. Sudheer Devulapalli for guidance and the VIT-AP University team for their support.

Notes for Customization

Replace your-username in the clone command with your GitHub username.
Add visualizations (e.g., loss curves) by hosting images on GitHub or linking to the notebook.
Expand the notebook section with specific code snippets if desired.

