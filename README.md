# Spam-SMS-Message-Detector
<h3>Instructions for Execution of Flask application:</h3><br />
1)Open app.ipynb file(better use Jupyter).<br />
2)Run all the cells.While running if it is taking ling time just Interupt the kernal.<br />
3)The you will able to the local host link generated click on it or use http://127.0.0.1:5000/.<br />
Like this you will get :
<img width="606" alt="image" src="https://user-images.githubusercontent.com/75380495/162500775-101df623-2d1a-4aab-b1bc-2a4f2fc6df93.png"><br />
4)After opening the link you will be able to see the Simple UI designed for the user check SMS is a spam or not.ENter your message and click on button 'Predict' to check<br/><br/>

<h3>Vectorizer:</h3>I have used CountVectorizer becuase it implements both tokenization and occurrence counting in a single class.his implementation produces a sparse representation of the counts.<br /><br />
<h3>Model:</h3>I have use Naive Bayes classifiers because Naive Bayes classifiers are a popular statistical technique of e-mail filtering. They typically use bag of words features to identify spam e-mail.Also Naive Bayes spam filtering is a baseline technique for dealing with spam that can tailor itself to the email needs of individual users and give low false positive spam detection rates that are generally acceptable to users.
