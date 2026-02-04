# The Human Touch: Navigating the Challenges of Automation and Accuracy for AI in Journalism 🌐
This repository contains the theoretical studies, data, and visualizations associated with the abstract, 
"The Human Touch: Navigating the Challenges of Automation and Accuracy for AI in Journalism." 
This project explores the critical intersection of artificial intelligence and journalistic practice, 
focusing on the ethical and practical considerations of AI tools in news production by exporing journalistic processes such as fact checking, 
content moderation, synthetic media and editorial policy.

# Project Overview
The core objective of this study is to examine the potential pitfalls and benefits of integrating AI into journalism. 
The epistemology of AI guardrails were explored through the lens of Human Rights Ethics-by-Design Framework to quantify and embedding RAI design including:
* Algorithmic Fairness Index (AFI)
* Bias Accuracy Trade-Off Metric
* Ethical Debt Metric and
* Community Alignment and Inclusivity Factor (CAIF)

# Key Components and Interpretation
* Purpose: To detect and mitigate biases that may cause discriminatory outcomes, enhancing trust and ensuring regulatory compliance.
* Scores/Thresholds: While there is no single universal formula, a common industry practice is to target scores above 80% (indicating minimal bias), while scores below 60% are considered high-risk.
* Interpretation: High scores reflect equitable outcomes; low scores suggest systemic biases.
* The 80% Rule: Many models use the "4/5ths" or "80%" rule (disparate impact) to compare the positive outcome rates of different groups

We specifically analyze how Human-in-The-Loop approach - Human labelling, De-identification and review of data throughout the entire model 
life-cycle in AI-driven automated systems impacts accuracy and the preservation of human intuition and judgment, 
which are foundational to quality journalism. The data visualizations, created using Python libraries within a Google Colab notebook, 
provide a visual representation of key findings from our theoretical framework. AI can act as a teammate by serving as an early warning system, 
using its immense processing power to rapidly detect anomalies in media, flag suspicious content, and 
cross-reference information from multiple sources. The journalist, as the human teammate, 
then applies critical thinking and ethical judgment to verify the findings before publication.

# Architecture:

RAG or agentic architectures for answering questions depends on a 
dynamic knowledge base that keeps updating over time, such as financial reports or 
documentation, so that the reasoning and planning steps remains logical and accurate.
To handle such a knowledge base, where the size continuously grows and the chances of hallucinations can increase, 
a separate logical-temporal (time-aware) agentic pipeline is required to manage this evolving knowledge base within your AI product as shown in the figure below
<img width="4800" height="2265" alt="image" src="https://github.com/user-attachments/assets/bf2c9189-93a3-43a1-9997-2ff2aa23592e" />

# Project Structure
`notebooks/:` Contains the Jupyter Notebook for data visualization and analysis. This notebook is designed to be run on Google Colab.

`data/:` Includes any datasets used for the visualizations. (Note: For this project, data is included directly within the Google Colab notebook for ease of access).

# How to View and Interact with the Notebook
This project is best viewed and interacted with using Google Colab.

* Open the Notebook: Click the following link to open the notebook directly in Google Colab:
[Insert Google Colab Notebook Link Here]

* Run the Cells: Once the notebook is open, you can run each cell sequentially by clicking the "play" button on the top-left of each cell or by selecting `Runtime > Run all` from the menu.

* Explore the Visualizations: The code will generate interactive data visualizations that illustrate the core concepts of the abstract.

# Key Themes Explored

* Accuracy vs. Automation: A visual exploration of the trade-offs between speed and factual correctness when AI is used for news aggregation and generation.

* The Evolving Role of the Journalist: A look at how the role of the human journalist changes in an AI-driven newsroom.

* Bias in AI: Visualizations highlighting potential biases in AI models and their impact on journalistic objectivity.

# Contributions and Contact
This project is a theoretical study and data visualization exercise. We welcome feedback and discussion on the concepts presented.
```
Authored by: Israel Olatunji Tijani
```
```
Affiliation: ChatVE
```

Note: This research abstract was present at the Society for Social Studies of Science (4S) Conference, Seattle 2025 under the theme `Reverberation`. [4S Conference](https://www.4sonline.org/final_program_seattle.php)
