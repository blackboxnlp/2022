# BlackboxNLP 2022

There will be a fifth edition of BlackboxNLP! 
It will be collocated with EMNLP 2022.

## News

- We started a YouTube channel: [https://www.youtube.com/@blackboxnlp](https://www.youtube.com/@blackboxnlp). Subscribe to be informed of all upcoming content. You can already watch this year's keynotes. 

## Program

Our [workshop program](/program) is now online.

## Invited speakers

### [Lena Voita](https://lena-voita.github.io/)
<img src="https://lena-voita.github.io/img/people/orange_lena-min.jpg" width="250px" align="right">
Elena (Lena) Voita is a Research Scientist joining Facebook AI Research. She is mostly interested in understanding what and how neural models learn. Her analysis works so far include looking at model components, adapting attribution methods to NLP models, black-box analysis of model outputs, as well as information-theoretic view on analysis (e.g., probing). Previously, she was a PhD student at the University of Edinburgh supervised by Ivan Titov and Rico Sennrich, was awarded Facebook PhD Fellowship, worked as a Research Scientist at Yandex Research side by side with the Yandex Translate team. She enjoys writing blog posts and teaching; a public version of (a part of) her NLP course is available at [NLP Course For You](https://lena-voita.github.io/nlp_course.html).

**The Two Viewpoints on the NMT Training Process**

In this talk, I illustrate how the same process (in this case, NMT training process) can be viewed from different perspectives: from the inside of the model and from the outside, i.e. in a black-box manner. In the first view, we look at the model’s inner workings and try to understand how NMT balances two different types of context, the source and the prefix of the target sentence. In the second view, we look at model outputs (i.e. generated translations) at different steps during training and evaluate how the model acquires different competences. We find that NMT training consists of the stages where it focuses on the competences mirroring three core SMT components: target-side language modeling, lexical translation and reordering. Most importantly, the two views show the same process, and we will see how this process is reflected in these two types of analysis.

### Catherine Olsson
<img src="https://raw.githubusercontent.com/blackboxnlp/blackboxnlp.github.io/main/catherine.jpeg" width="250px" align="right">
Catherine Olsson is a research engineer at Anthropic, and the lead author on the recent mechanistic interpretability paper "In-context Learning and Induction Heads". She has previously worked in technical research roles at Google Brain and OpenAI, and as a grantmaker at Open Philanthropy Project funding academic research in ML robustness.


### David Bau
<img src="https://s32615.pcdn.co/wp-content/uploads/2022/04/Bau-David-2991-inline.jpg" width="250px" align="right">

David Bau is Assistant Professor at the Northeastern University Khoury College of Computer Science. He received his PhD from MIT and AB from Harvard. He is known for his network dissection studies of individual neurons in deep networks and has published research on the interpretable structure of large models in PNAS, CVPR, NeurIPS, and SIGGRAPH.  Prof. Bau is also coauthor of the textbook, Numerical Linear Algebra.

**Direct Model Editing**

Can we understand large deep networks well enough to reprogram them by changing their parameters directly?  In this talk I will talk about Direct Model Editing: how to modify the weights of a large model directly by understanding its structure.  We will consider examples in computer vision and NLP: how to probe and rewrite computations within an image synthesis model to alter compositional rules that govern rendering of realistic images, and how the ROME method can edit specific factual memories within a large language model, directly tracing and modifying parameters that store associations within GPT.  I will talk about how causal mediation analysis can serve as a key to unlock the secrets of a huge model; the specificity-generalization trade-off when evaluating knowledge changes in a large model; and how recent results in our MEMIT work suggest that direct editing in huge models may scale orders-of-magnitudes better than traditional opaque fine-tuning.

## Important dates

- July 15, 2022 -- ARR submission deadline (via [ARR](https://openreview.net/group?id=aclweb.org/ACL/ARR/2022)).
- September 7, 2022 -- Direct submission deadline (via [OpenReview](https://openreview.net/group?id=EMNLP/2022/Workshop/BlackboxNLP))
- October 2, 2022 -- ARR commitment deadline (via [OpenReview](https://openreview.net/group?id=EMNLP/2022/Workshop/BlackboxNLP)).
- **October 11, 2022** -- Notification of acceptance. (This was delayed by two days to make sure emergency reviews are taken into account. Extended abstracts were reviewed by the program chairs and only have a decision.)
- **October 18, 2022** -- Camera-ready papers due. (Please read below for instructions.)
- **November 16, 2022** -- Upload poster (poster presenters) or video recording (only papers #31, #32, #39, #73). Read below for poster instructions.
- December 8, 2022 -- Workshop (hybrid).

All deadlines are 11:59pm UTC-12 ("anywhere on earth").

### Onsite Poster info (Updated Oct 23)

- The onsite poster panels are 3.28’ (1m wide) x 8.20’ (2.5m tall). We recommend to have posters that are portrait in orientation.
- Virtual posters will be available in GatherTown throughout the conference. Apart from the scheduled virtual poster session, posters can be viewed and commented on at any time. We ask you to be virtually present at your poster at the virtual poster session as will be advertised on the schedule.

Please read the [Poster and Talk Accessibility, Quality, and Inclusivity](https://2022.naacl.org/blog/poster-talk-accessibility-quality-inclusivity/) guidelines.

## Workshop description

Many recent performance improvements in NLP have come at the cost of understanding of the systems. How do we assess what representations and computations models learn? How do we formalize desirable properties of interpretable models, and measure the extent to which existing models achieve them? How can we build models that better encode these properties? What can new or existing tools tell us about systems’ inductive biases?

The goal of this workshop is to bring together researchers focused on interpreting and explaining NLP models by taking inspiration from machine learning, psychology, linguistics, and neuroscience. We hope the workshop will serve as an interdisciplinary meetup that allows for cross-collaboration.

The topics of the workshop include, but are not limited to:
- Explanation methods such as saliency, attribution, free-text explanations, or explanations with structured properties
- Probing methods for testing whether models have acquired or represent certain linguistic properties
- Applying analysis techniques from other disciplines (e.g., neuroscience or computer vision)
- Examining model performance on simplified or formal languages
- More interpretable model architectures
- Open-source tools for analysis, visualization, or explanation;
- Evaluation of explanation methods
- Opinion pieces about the state of explainable NLP

Feel free to reach out to the organizers at the email below if you are not sure whether a specific topic is well-suited for submission.

## Call for Papers
All submissions should use the ACL [templates](https://github.com/acl-org/acl-style-files) and formatting requirements specified by [ACL Rolling Review](https://aclrollingreview.org/), and should be fully anonymized. Submissions of both types can be made through [OpenReview](https://openreview.net/group?id=EMNLP/2022/Workshop/BlackboxNLP).

### Submission Types
- **Archival papers** of up to 8 pages + references. These are papers reporting on completed, original and unpublished research, and can be submitted **either with or without ARR reviews** by selecting the appropriate box on the submission form. An optional appendix may appear after the references in the same pdf file. If you do not include ARR reviews with your submission, it will be reviewed by reviewers specific to the BlackBoxNLP workshop. Accepted papers are expected to be presented at the workshop and will be published in the workshop proceedings of the ACL Anthology, meaning they cannot be published elsewhere. They should report on obtained results rather than intended work. Broader Impacts/Ethics and Limitations sections are optional and can be included on a 9th page.
- **Non-archival extended abstracts** of 2 pages + references. These may report on work in progress or may be cross submissions of work that has already appeared (or is scheduled to appear) in another venue in 2021-2022. Abstract titles will be posted on the workshop website but will not be included in the proceedings.

Accepted submissions will be presented at the workshop: most as posters, some as oral presentations (determined by the program committee).

### Dual Submissions and Preprints
Dual submissions are **not** allowed for the archival track. Papers posted to preprint servers such as arxiv can be submitted without any restrictions on when they were posted.

### Camera-ready information
Authors of accepted archival papers should upload the final version of their paper to the submission system by the camera-ready deadline. Authors may use **one extra page** to address reviewer comments, for a total of nine pages + references. Broader Impacts/Ethics and Limitations sections are optional and can be included on a 10th page.

## Contact
Please contact the organizers at blackboxnlp@googlegroups.com for any questions.

## Previous workshops

- [BlackboxNLP 2018](https://blackboxnlp.github.io/2018/) (at EMNLP 2018)
- [BlackboxNLP 2019](https://blackboxnlp.github.io/2019/) (at ACL 2019)
- [BlackboxNLP 2020](https://blackboxnlp.github.io/2020/) (at EMNLP 2020)
- [BlackboxNLP 2021](https://blackboxnlp.github.io/2021/) (at EMNLP 2021)

## Sponsors

Blackbox NLP 2022 is sponsored by:

<img src="https://raw.githubusercontent.com/blackboxnlp/blackboxnlp.github.io/main/Google%20Logo.png" height="100px" alt="Google logo" />

## Organizers

You can reach the organizers by e-mail to <a href="mailto:blackboxnlp@googlegroups.com">blackboxnlp@googlegroups.com</a>.

### Jasmijn Bastings
Jasmijn Bastings is a researcher at Google in Amsterdam. 
She got her PhD from the University of Amsterdam on Interpretable and Linguistically-informed Deep Learning for NLP. 
Jasmijn's current research focuses on interpretable NLP models and predictions, and she authored two BlackboxNLP papers (2018, 2020) on generalisation and saliency methods, as well as an ACL paper (2019) on interpretable neural predictions using differentiable binary variables.

### Yonatan Belinkov
Yonatan Belinkov is an assistant professor at the Technion. 
He has previously been a Postdoctoral Fellow at Harvard and MIT.
His recent research focuses on interpretability and robustness of neural network models of language. 
His research has been published at leading NLP and ML venues. 
His PhD dissertation at MIT analyzed internal language representations in deep learning models.
He has been awarded the Harvard Mind, Brain, and Behavior Postdoctoral Fellowship and the Azrieli Early Career Faculty Fellowship.
He co-organised BlackboxNLP in 2019, 2020, and 2021, as well as the 1st and 2nd machine translation robustness tasks at WMT.

### Yanai Elazar
Yanai Elazar is a postdoctoral researcher at AI2 & UW. 
His research focus is interpretability and analysis methods for NLP.
His research showed how demographics and linguistics phenomena are encoded in models’ representations, and how more abstract capabilities, such as commonsense and reasoning, are manifested, and being used by models.

### Dieuwke Hupkes
Dieuwke Hupkes is a research scientist at Facebook AI Research.
The main focus of her research is understanding how neural networks  generalise, considering specifically on how they can understand and learn grammar, structure and compositionality. 
Developing methods to interpret and interact with neural networks has therefore been an important area of focus in her research.
She authored many articles directly relevant to the workshop and has co-organised the previous three editions of BlackboxNLP. 

### Naomi Saphra
Naomi Saphra is a postdoc at New York University. 
Their research is on understanding the training dynamics of language models, from the standpoint of linguistic structure acquisition. 
Their relevant work has been published at NAACL and EMNLP, and they have served on the organizing committee for the Workshop on Representation Learning for NLP (RepL4NLP). 

### Sarah Wiegreffe
Sarah Wiegreffe is a postdoctoral researcher at the Allen Institute for AI (AI2).
Her research focuses on improved modeling and analysis of explanations from neural models along the axes of faithfulness and human acceptability, with a recent focus on free-text explanations. 
Her research on interpretability has been published at leading ML and NLP conferences. 
She served as a publicity chair for NAACL 2021 and frequently serves on conference program committees.

## Anti-Harassment Policy
BlackboxNLP 2022 adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).
