# Qwen2.5-Attention-Visualize
A simple PyTorch script to visualize the layerwise attention scores of Qwen2.5 model. Here the Qwen2.5 1B model is chosen for answering trivia questions.

========================================

+ **Step 1:** Query the Qwen 2.5 model with the prompt "Who is the president of X?"

  + **Example 1**
    + Query: Who is the president of China?
    + Qwen response: Xi Jingping
    + Remarks: correct
    
  + **Example 2**
    + Query: Who is the president of Rwanda?
    + Qwen response: Ernest Ndayisaba
    + Remarks: incorrect (Hallucination). Its Paul Kagame (president of Rwanda since the yesr 2000)
    + Interestingly 'Ndayisaba' is a popular surname in Rwanda/Burundi
 
+ **Step 2:** Copy/Pase the answer keywords within the response.
  
+ **Step 3:** Visualuize the attention scores using matplotlib abd seaborn

========================================

![visualize](https://github.com/NMS05/Qwen2.5-Attention-Visualize/blob/main/Probing%20into%20the%20attention%20patterns.png)
