# becks-cognitive-triad-classification-language-models: 
In this repository, we have demonstrated the application of cost-efficient language models for classification of aspect-sentiment as per Beck's cognitive triad by testing seven models using 900 data points from the gold standard Cognitive Triad Dataset (CTD) test set using various prompting strategies. Models were accessed through the OpenRouter API. 

**Project Structure**
project/
│── src/
│   ├── prompts/
│   ├── classifiers/
│   ├── utils/
│── notebooks/
│── configs/
│── README.md
│── requirements.txt
│── LICENSE

**Environment Setup (Cloud only)**
This project is designed to run on the RunPod GPU environment. It cannot be executed locally due to computing requirements.
1. Start a GPU instance on RunPod.
2. Clone this repository inside /workspace.
3. Install dependencies using requirements.txt.
4. Set your API keys as environment variables.
5. Run the notebook or pipeline script.

**API Keys**

