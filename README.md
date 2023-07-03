<img src="docs/images/TheBigBarPlot.png">

# HL-NTAC
Defending against Adversarial Machine Learning Attacks using Hierarchical Learning: A case study on Network Traffic Attack Classification.

Cyber security, and the protection of associated computer and network systems, remains a crucial and costly concern for many organisations. It has become impossible to effectively monitor and mitigate against network intrusion threats manually. %Thankfully 
Machine learning is now widely used to automate the detection of malicious network activity.

When machine learning models are trained, they develop a mathematical model to represent the association between numerical input features and their output classifications. Recently, there has been growing interest in the domain of adversarial machine learning, which explores 
how a model 
may be compromised by an adversary to produce false output.

Whilst most focus has been on the visual domain, the challenge translates to many other domains, notably that of cyber security and network traffic attack classification.

The crafting of an adversarial attack is complex, since features must be perturbed so as to fool the classifier, whilst ensuring that the raw input activity maintains the intended purpose.

We refer to this characteristic as \textit{functionality-preserving}, since if malicious functionality of a given input is not preserved, a model might legitimately consider the input as benign because its payload has been neutered.

In this paper, we investigate how to apply adversarial learning within the network intrusion domain. Firstly, we explore the feasibility of manipulating a well-trained classifier such that a malicious attack may pass as benign. We then seek to improve the defensive capability of the classifier against such adversarial examples, through the use of hierarchical learning. Our approach reduces the potential attack surface of the classifier, hence reducing the feasibility of manipulating features such that functionality is preserved. Our results suggest that our hierarchical learning model can provide strong defense against adversarial examples, such that the performance of the hierarchical classifier when under attack is able to achieve similar results to that of the original flat model without the adversarial attack.
