# AI-driven-Cyber-Security-Framework

## Abstract
Cyber warfare has revolutionized global security landscapes by rendering physical distance irrelevant,
with attacks constrained only by bandwidth and latency. The widespread reach of cyber threats presents
significant challenges in protecting Critical Infrastructure (CI), the backbone of modern society. The
interconnected nature of communication networks, where ISPs lease lines to both government and
commercial entities, and satellite corporations provide bandwidth across multiple countries, creates
vulnerabilities that adversaries exploit using powerful tools similar to those of legitimate entities
highlighting the urgent need for comprehensive and ethically sound frameworks for CI protection.

This research presents an innovative AI-driven framework for enhancing cybersecurity practices in
critical infrastructure organizations. The methodology involves developing an ensemble cyber risk
prediction model, incorporating SHAP graphs for model explainability, and fine-tuning the Llama 3.1 LLM
to generate tailored cybersecurity policy recommendations based on the predicted risks. The
implemented model achieved a 90.81% accuracy in cyber risk prediction using the XGBoost algorithm
and the LLM's ability to generate context-specific recommendations demonstrate the potential of AI in
improving cyber risk assessment and offering a powerful tool for proactive cybersecurity management
for CI organisations.

## Files 
- cyber risk prediction model.ipynb - jupyter notebook for risk prediction model
- cyber policy recommendation model.ipynb - jupyter notebook for finetuning Llama 3.1 LLM
- data.xlsx - pre processed VCDB dataset for training risk prediction model
- alpaca dataset.json - custom dataset for finetuning LLM for cyber applications
