<h1 align="center">Fake News Detection Using Deep Learning</h1>

<h2>Paper</h2> Paper : https://github.com/user-attachments/files/18223153/FakeNewsDetectionUSingDeepLearningSample.1.docx

<h2>Objective</h2>
<p>
  The primary goal of this project is to develop a robust fake news detection system leveraging transformer-based models, addressing the limitations of traditional approaches, and achieving higher accuracy for identifying false information on social media platforms.
</p>

<h2>Introduction</h2>
<p>
  With the rise of social media platforms like Facebook, Twitter, and TikTok, the dissemination of fake news has become a critical issue, eroding trust, distorting public opinion, and threatening democratic processes. This project explores state-of-the-art transformer models such as BERT, ALBERT, RoBERTa, and XLNet for addressing the challenges of detecting fake news. These models excel in processing and understanding large amounts of textual data, making them well-suited for this task.
</p>

<h2>Workflow</h2>
<p>
  The workflow involves preprocessing the dataset, tokenizing text data using transformer-specific tokenizers, and fine-tuning pre-trained models for fake news detection. The process includes:
</p>
<ul>
  <li>Dataset preprocessing (handling Title, Text, Subject, and Date columns).</li>
  <li>Training transformer-based models like BERT, ALBERT, and RoBERTa.</li>
  <li>Evaluating performance using metrics such as accuracy, precision, recall, and F1-score.</li>
</ul>
<p align="center">
  <img src="https://github.com/user-attachments/assets/47e00169-9619-4e42-8aa8-9b32747ed88a" alt="Workflow" />
</p>

<h2>Models and Performance</h2>
<table align="center">
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>BERT</td>
    <td>92%</td>
    <td>BERT uses bidirectional training to understand context deeply, making it effective for fake news detection.</td>
  </tr>
  <tr>
    <td>RoBERTa</td>
    <td>97%</td>
    <td>RoBERTa improves upon BERT with more training data and dynamic masking, enhancing detection accuracy.</td>
  </tr>
  <tr>
    <td>ALBERT</td>
    <td>98%</td>
    <td>ALBERT optimizes BERT by reducing parameters, making it more memory-efficient while maintaining high accuracy.</td>
  </tr>
  <tr>
    <td>DistilBERT</td>
    <td>98%</td>
    <td>DistilBERT is a compact version of BERT, offering faster inference while retaining high accuracy.</td>
  </tr>
  <tr>
    <td>XLNet</td>
    <td>96%</td>
    <td>XLNet combines autoregressive and bidirectional training for capturing nuanced dependencies in the text.</td>
  </tr>
</table>

<h2>Key Findings</h2>
<ol>
  <li>
    ALBERT and DistilBERT achieved the highest accuracy of 98%, making them the most efficient models for fake news detection.
  </li>
  <li>
    RoBERTa followed closely with an accuracy of 97%.
  </li>
  <li>
    BERT and XLNet, while slightly less accurate, demonstrated strong performance with accuracies of 92% and 96%, respectively.
  </li>
</ol>

<h2>Conclusion</h2>
<p>
  The results demonstrate the efficacy of transformer-based models in detecting fake news. ALBERT and DistilBERT stand out for their combination of high accuracy and resource efficiency. These findings highlight the potential of such models to combat misinformation effectively.
</p>

<h2>Future Scope</h2>
<ul>
  <li>Incorporating multimedia data (images and videos) to enhance detection capabilities.</li>
  <li>Deploying the model as a scalable, real-time web application for social media platforms.</li>
  <li>Collaborating with fact-checking organizations to refine model accuracy further.</li>
</ul>

<h2>References</h2>
<ol>
  <li>
    Sadiq Muhammed T and Saji K. Mathew, <b>"The Disaster of Misinformation: A Review of Research in Social Media,"</b> <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8853081/" target="_blank">Read Here</a>
  </li>
  <li>
    Álvaro Ibrain Rodríguez, Lara Lloret Iglesias, <b>"Fake News Detection Using Deep Learning,"</b> <a href="https://arxiv.org/pdf/1910.03496" target="_blank">Read Here</a>
  </li>
  <li>
    Femi Olan et al., <b>"Fake News on Social Media: The Impact on Society,"</b> <a href="https://link.springer.com/article/10.1007/s10796-022-10242-z" target="_blank">Read Here</a>
  </li>
  <li>
    Shaina Raza & Chen Ding, <b>"Fake News Detection Based on News Content and Social Contexts: A Transformer-Based Approach,"</b> <a href="https://link.springer.com/article/10.1007/s41060-021-00302-z" target="_blank">Read Here</a>
  </li>
  <li>
    Jawaher Alghamdi et al., <b>"Towards COVID-19 Fake News Detection Using Transformer-Based Models,"</b> <a href="https://www.sciencedirect.com/science/article/pii/S0950705123003921" target="_blank">Read Here</a>
  </li>
</ol>

<h2>Connect with Me</h2>
<p>Find me on LinkedIn: 
    <a href="https://linkedin.com/in/mohammed-aadhil-144245259" target="_blank">
        <img src="https://github.com/user-attachments/assets/a388191c-6399-4689-b05f-8e8fbf565b76" width="20" height="20" alt="LinkedIn Logo">
        Mohammed Aadhil
    </a>
</p>
