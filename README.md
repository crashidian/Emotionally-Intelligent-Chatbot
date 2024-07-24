# Emotionally Intelligent Chatbot
This project implements an emotionally intelligent chatbot using GPT-2 and Graph Neural Networks (GNN). The chatbot is designed to engage in open-domain conversations while maintaining context and providing empathetic responses.
**Features**

- Open-domain conversation capabilities using GPT-2
- Dynamic knowledge graph for context maintenance
- Graph Neural Network for processing contextual information
- Basic emotion recognition and sentiment analysis
- Empathetic response generation

**Requirements**

- Python 3.7+
- PyTorch
- PyTorch Geometric
- Transformers (Hugging Face)
- NetworkX
- Scikit-learn
- SpaCy
- NumPy

**Installation**

- Clone this repository:
    - Copygit clone https://github.com/crashidian/Emotionally-Intelligent-Chatbot.git

    - cd emotionally-intelligent-chatbot

- Install the required packages:
    - Copypip install torch torch_geometric transformers networkx scikit-learn spacy numpy

- Download the SpaCy English language model:
    - Copypython -m spacy download en_core_web_sm


**Usage**
- Run the chatbot script:
    - Copypython emotionallyintelligentchatbot.ipynb
- Interact with the chatbot via the command line. Type your messages and press Enter to send. The chatbot will respond with generated replies. To end the conversation, type 'quit', 'exit', or 'bye'.

**How It Works**

- The chatbot uses GPT-2 for natural language understanding and generation.
- A knowledge graph is maintained and updated during the conversation to keep track of context.
- A Graph Neural Network processes the knowledge graph to enhance contextual understanding.
- Basic emotion recognition is performed using keyword matching and SpaCy's sentiment analysis.
- The chatbot generates empathetic responses based on the detected emotion and conversation context.

**Limitations**

- The emotion recognition system is basic and may not capture complex or subtle emotions.
- The chatbot's knowledge is limited to its pre-training and the current conversation context.
- No long-term memory between separate runs of the script.

**Future Improvements**

- Enhance the emotion recognition system with more advanced NLP techniques.
- Implement fine-tuning of the GPT-2 model on empathetic datasets.
- Add more sophisticated reinforcement learning for improved adaptability.
- Develop a user interface for easier interaction.

**Contributing**

- Contributions to improve the chatbot are welcome. Please feel free to submit a Pull Request.

**License**

- This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments**

- OpenAI for the GPT-2 model
- PyTorch team for the deep learning framework
- Hugging Face for the Transformers library
- PyTorch Geometric team for GNN implementations

**Contact**

For any queries, please e-mail me at crashid@purdue.edu.
