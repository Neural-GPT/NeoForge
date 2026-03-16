## **NeoForge**

### **Sleek, modular ML utilities for Linear & Logistic Regression**
### **A lightweight Python library designed with sklearn-style API for clean, professional workflows, enhanced logging, and visualization utilities**

### **Features:**

**Linear & Logistic Regression – Fit, predict, and evaluate with a consistent API**

**Modular utilities – Learning rate scheduler, weight tracking, plotting, and metrics**

**Modular & Extendable – Add new models or custom methods without hassle**

**Demo Notebook – Quick showcase with example usage and visualizations**

### **Why NeoForge?**

**-Sklearn-style API – clean, consistent, professional**

**-Enhanced workflow – tracking, plotting, and extra utilities out of the box**

**-Extendable – easily add your own custom methods or models**

### **Utilities**

1. **Model Initialization**
   ```bash
   from linear_models import Linear_Regression
   model = Linear_Regression(alpha = 0.01, iter = 1000, l2 = 0.001)
   
2. **Model Training**
   ```bash
   model.fit(x, y, verbose = 50, freeze = 0.1, save_history_interval = 10, random_state = 42, cosine_annealing = True, normalise = True)
  
3. **Cost vs Epoch**
   ```bash
   model.plot_cost()



### **License**
**MIT © Arjun Gupta**
