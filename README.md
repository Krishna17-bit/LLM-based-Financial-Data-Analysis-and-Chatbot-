**LLM-based Financial Data Analysis and Chatbot for Infosys and TCS**

**Overview**

This project uses a Language Learning Model (LLM) to parse and analyze financial data from Infosys and TCS. The model is integrated into a chatbot that provides real-time insights and predictions based on company data, allowing users to ask questions related to financial reports and receive data-driven responses.

**Project Structure**

1.  **Data Integration**:
    
    *   **Sources**: Data is sourced from financial reports and structured datasets from Infosys and TCS.
        
    *   **Preparation**: Data from both companies is loaded, cleaned, and merged to ensure a consistent format.
        
    *   **Splitting**: The unified dataset is split into training and test sets to accurately evaluate model performance.
        
2.  **Model Development**:
    
    *   **Architecture**: A BERT-based model fine-tuned for financial text classification.
        
    *   **Training**: The model is trained using a combination of Infosys and TCS data, with hyperparameters optimized for accuracy.
        
    *   **Evaluation**: Model performance is assessed on test data using metrics like accuracy and loss.
        
3.  **Chatbot Integration**:
    
    *   **Deployment**: The trained model is deployed as part of a chatbot interface.
        
    *   **Functionality**: The chatbot answers user queries related to Infosys and TCS financial data by leveraging the LLM’s insights.
        
    *   **User Interaction**: Users can interact with the chatbot through a web interface, providing real-time, data-driven responses.
        

**Technical Details**

*   **Tokenizer**: Text data is tokenized for BERT model compatibility.
    
*   **Optimizer**: AdamW optimizer is used to fine-tune model weights.
    
*   **Loss Function**: Cross-entropy loss is employed for classification tasks, enhancing accuracy.
    

**Setup and Installation**

1.  git clone https://github.com/Krishna17-bit/LLM-based-Financial-Data-Analysis-and-Chatbot-.git
2.  cd financial-chatbot-llm
    
3.  pip install -r requirements.txt
    
4.  python app.pyAccess the chatbot through http://127.0.0.1:5000 in your browser.
    

**Usage**

*   **Interact with the Chatbot**: Use the web app to input financial queries regarding Infosys and TCS, and receive responses based on the trained LLM’s insights.
    

**Results**

*   The model achieves robust accuracy and effectively answers financial inquiries by leveraging Infosys and TCS data.
    

**Key Features**

*   **Financial Insights**: Combines data from two major companies for comprehensive insights.
    
*   **User-Friendly Chatbot**: Provides real-time responses through an interactive interface.
