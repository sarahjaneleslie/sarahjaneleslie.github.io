# sarahjaneleslie.github.io
<b>TENTATIVE SYLLABUS - Spring 2023</b>

<H1>Deep Learning: A Practical Introduction for Humanists and Social Scientists</H1>
<H3>Sarah-Jane Leslie<br>
sjleslie@princeton.edu<br>
www.princeton.edu/leslie</H3>


Machine learning – and in particular, deep learning – is rapidly opening new horizons for research in the humanities and social sciences. However, scholars in the humanities and social sciences can encounter barriers to learning about such techniques – for example, machine learning courses, especially at the graduate level, often require multivariate calculus, linear algebra and prior coding experience, which students in the humanities and less quantitative social sciences may lack. This course offers a practical introduction to deep learning for graduate students, without assuming knowledge of calculus or other college-level math, or any prior experience with coding. By the end of the course, students will: 

<ul><li>be able to code and train a variety of basic deep learning models</li>
<li>develop an appreciation of the range of humanities/social science research questions to which deep learning can be applied</li>
<li>be fluent collaborators on research projects that involve machine learning experts</li>
<li>gain an understanding than will inform theorizing about machine learning (e.g., for research in AI ethics, technology policy, etc)</li></ul>

<b>Readings:</b> The primary text for the course is Francois Chollet, 2021, Deep learning with Python. Simon and Schuster. We will work our way through the book in a lot of detail. In the second half of the course, once we have worked through the basics, there are supplemental readings each week, which give examples of how related models have been used in humanities/social science research. The supplemental readings aim to provide a sense of the breadth of applications, as well as to raise interesting issues for further thought and consideration.

<b>Evaluation and assignments:</b> There are simple weekly coding assignments to cement knowledge and build skills. Students taking the course for credit are required to complete these, though they are ungraded. That is, as long as a reasonable effort is made on them, students receive full credit for the week. In addition, there are three graded projects spaced throughout the semester. For these projects, students will be supplied with a humanities/social science data set and asked to build a model that addresses a research question appropriate to the data set. Students can choose from a list of suggested research questions, or can formulate their own. Evaluation will be based on the appropriateness of the model for the research question and the success of the code used to build/train the model. The three projects will cover the following areas respectively: classification/regression, computer vision, natural language processing. (For philosophy students only: successful completion of the above assignments will constitute a logic unit. Philosophy students wishing to receive a unit other than logic should contact me directly.) 

Final grades are determined in the following way: 20% homework, 20% classification/regression assignment, 30% computer vision assignment, 30% natural language processing assignment. 

<b>Auditing:</b> Graduate students are welcome to audit this course, however I request that even auditors engage with the weekly coding assignments, since the value of this class is largely associated with the development of practical skills. As with any kind of coding, these skills can only be learned by doing. Post-docs and other researchers/faculty are welcome to informally audit the class also.

<H3>Schedule of Topics</H3>

<em>NB: I highly recommend that students who have never coded before review [PYTHON RESOURCE] prior to the first class.</em>

<b>Week 1:</b> Overview of machine learning; crash course in Python basics<br>
Reading: Chollet, chapter 1
[PYTHON RESOURCE]

<b>Week 2:</b> Fundamentals of neural networks<br>
Reading: Chollet, chapter 2

<b>Week 3:</b> Introduction to Keras<br>
Reading: Chollet, chapter 3

<b>Week 4:</b> Classification and regression<br>
Reading: Chollet, chapter 4

<em>Classification/regression project assignment distributed</em>

<b>Week 5:</b> Training, validation, and test sets; evaluation, hyperparameters and regularization<br>
Reading: Chollet, chapters 5 and 6

<b>Week 6:</b> Best practices for model evaluation; introduction to Keras functional API<br>
Reading: Chollet, chapter 7<br>
Supplemental reading: Kapoor, S. & Narayanan, A. (2022), https://arxiv.org/abs/2207.07048 

<em>Classification/regression project due</em>

<b>Week 7:</b> Computer vision I: introduction to convolutional neural networks<br>
Reading: Chollet, chapter 8<br>
Supplemental reading: <a href="https://academic.oup.com/dsh/article/35/1/194/5296356">Melvin Wevers, Thomas Smits, The visual digital turn: Using neural networks to study historical images, Digital Scholarship in the Humanities, Volume 35, Issue 1, April 2020, Pages 194–207.</a>

<em>Computer vision project assignment distributed</em>

<b>Week 8:</b> Computer vision II: classification, segmentation and object detection<br>
Reading: Chollet, chapter 9<br>
Supplemental reading: <a href="https://www.sciencedirect.com/science/article/pii/S0305440321000455">Leszek M. Pawlowicz, Christian E. Downum, Applications of deep learning to decorated ceramic typology and classification: A case study using Tusayan White Ware from Northeast Arizona, Journal of Archaeological Science, Volume 130, 2021, 105375.</a>

<b>Week 9:</b> Natural Language Processing I: uses of NLP; word embeddings<br>
Reading: Chollet chapter 11, sections 1-3<br>
Supplemental reading: <a href="https://tessaescharlesworth.files.wordpress.com/2022/07/charlesworth_hist-embeddings_published.pdf">Charlesworth, T.E.S., Caliskan, A., & Banaji, M.R., (2022) Historical representations of social groups across 200 years of word embeddings from Google Books. Proceedings of the National Academy of Sciences, 119(28).</a><br> 
<a href="https://www.nature.com/articles/s41562-022-01316-8">Grand, G., Blank, I.A., Pereira, F. et al. Semantic projection recovers rich human knowledge of multiple object features from word embeddings. Nat Hum Behav 6, 975–987 (2022).</a> <br>
<a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4433545/">Eichstaedt, J. C., Schwartz, H. A., Kern, M. L., Park, G., Labarthe, D. R., Merchant, R. M., ... & Seligman, M. E. (2015). Psychological language on Twitter predicts county-level heart disease mortality. Psychological science, 26(2), 159-169.</a><br>

<em>Computer vision project due</em>

<b>Week 10:</b> NLP II: transformers<br>
Reading: Chollet chapter 11, sections 4-5<br>
Supplemental reading: <a href="https://www.nature.com/articles/s41586-022-04448-z?utm_campaign=The%20Batch&utm_medium=email&_hsmi=222428230&_hsenc=p2ANqtz-_kr0H_rGJOIJRXWpDlGwP298BuR5SoKbROhB05hKXLpwXYaktKDQq3fq7RfNIXxV4DSCytHhkc_T2aCIlnx-SWBivzg1GfDrQFM5c4bz-0KgE_Low&utm_content=222428230&utm_source=hs_email">Assael, Y., Sommerschield, T., Shillingford, B. et al. Restoring and attributing ancient texts using deep neural networks. Nature 603, 280–283 (2022).</a> 

<b>Week 11:</b> NLP III: automatic text generation; introduction to Hugging Face<br>
Reading: Chollet chapter 12, section 1<br>
Supplemental reading: <a href="https://www.scientificamerican.com/article/we-asked-gpt-3-to-write-an-academic-paper-about-itself-mdash-then-we-tried-to-get-it-published/">Osmanovic Thunström, A. (2022). We Asked GPT-3 to Write an Academic Paper about Itself—Then We Tried to Get It Published. Scientific American, June 30 2022.</a> <br>
<a href="https://hal.archives-ouvertes.fr/hal-03701250/document"> Gpt Generative Pretrained Transformer, Almira Osmanovic Thunström, Steinn Steingrimsson. Can GPT-3 write an academic paper on itself, with minimal human input?. 2022. hal-03701250.</a><br>
<a href="https://www.nature.com/articles/d41586-021-00530-0">Hutson, M. (2021). Robo-writers: the rise and risks of language-generating AI. Nature 591, 22-25.</a>

<em>NLP project distributed</em>

<b>Week 12:</b> Review; new horizons in machine learning<br>
Supplemental reading: <a href="https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/building-machines-that-learn-and-think-like-people/A9535B1D745A0377E16C590E14B94993">Lake, B., Ullman, T., Tenenbaum, J., & Gershman, S. (2017). Building machines that learn and think like people. Behavioral and Brain Sciences, 40, E253.</a> <br>
	<a href="https://www.cambridge.org/core/services/aop-cambridge-core/content/view/98F5E24BEADE585050B773D2CBEB1F39/S0045509121000230a.pdf/whats_wrong_with_automated_influence.pdf">Benn, C., & Lazar, S. (2022). What’s wrong with Automated Influence. Canadian Journal of Philosophy, 1-24.</a>


<em>NLP project due on appropriate date based on University calendar</em>
