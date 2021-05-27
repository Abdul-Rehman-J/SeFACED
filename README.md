# SeFACED
SeFACED: Semantic-based Forensic Analysis and Classification of E-Mail Data using Deep Learning

The dataset used in this study is an amalgamation of five different datasets. The dataset contains Normal e-mails from Enron Corpora[1], Fraudulent e-mails provided by Phished
e-mails corpora [2] which contain misleading information, Harassment messages selected from “Hate Speech & Offensive Dataset"[3] and Suspicious e-mail messages taken from
Hillary Clinton E-mail Dataset[4]. We enhanced the dataset of Email Forensics. We extends the emails data from our personal email sources, and twitter source. 
To the best of our knowlegde this is the only kind of email forensic dataset which is available for public use. The suspicious dataset contains some terrorism-related messages collected from
Twitter by API. These different datasets are merged into a structural file to make the multiclass E-mail classification possible. We have extracted features from the E-mail body
using TF-IDF,Word2vector, andWord Embedding to classify them. Normal,Fraudulent,Harassment, and Suspicious emails are 9001, 9001, 9138, and 5287 in numbers. E-mails. All the header information such
as sender, subject, CC, and BCC are removed; only the Email body’s content is used for analysis. The dataset after composition contains about 32,427 messages. 
The dataset can be used to enhance the security measure of the email servers and the end users. We will feel honored if you will cite our framework, code, or dataset in your study to avoid any unwanted situation created by unreliable email communication. 
please refer the following paper: 



References:

[1] kaggle, “The enron email dataset,” 2020. Last accessed 16 December
2020.

[2] D. Radev, “Clair collection of fraud email, acl data and code repository,”
ADCR2008T001, 2008.

[3] https://www.kaggle.com/mrmorj/hate-speech-and-offensive-language-dataset?select=labeled_data.csv

[4] https://www.kaggle.com/kaggle/hillary-clinton-emails

