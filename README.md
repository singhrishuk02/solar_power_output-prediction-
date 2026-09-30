# ☀️ Solar Power Output Prediction (Simple Linear Regression)

## Files
- `solar_power_output.csv`: dataset
- `solar_power_lr.ipynb`: problem → data → EDA → preprocessing → split → training → evaluation → save model
- `model.pkl`: trained model (created by the notebook)
- `app.py`: Streamlit app
- `requirements.txt`: libraries

## Run
```bash
pip install -r requirements.txt
streamlit run app.py
```
Enter the solar irradiance (plus panels, sun hours, price) and click **Predict**.

Model: `Output = 0.011 + 0.5005 × Irradiance` · Test R² ≈ 0.998
