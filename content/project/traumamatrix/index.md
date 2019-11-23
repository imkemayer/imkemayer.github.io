+++
# Project title.
title = "TrauMatrix"

# Date this page was created.
date = 2019-02-20T00:00:00

# Project summary to display on homepage.
summary = "A decision support tool for critical care management."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["critical-care", "personalized-medicine", "machine-learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

<p align="justify">This interdisciplinary project has been jointly initiated by Julie Josse, Jean-Pierre Nadal, the <a href="http://www.traumabase.eu/en_US/projects/in-progress" target="_blank">Traumabase Group</a>, APHP (Public Assistance - Hospitals of Paris) especially Tobias Gauss and Sophie Hamada in 2016. I have joined this project in the context of my PhD thesis in October 2018.<br>
Since January 2019, the TrauMatrix project is supported as well by the <i>Data4Good</i> initiative of <a href="https://www.capgemini.com/service/invent/" target="_blank">CapGemini Invent</a>.<br>
Click <a href="https://www.capgemini.com/fr-fr/news/traumatrix-lintelligence-artificielle-au-service-des-soins-aux-patients-gravement-traumatises/" target="_blank">here for a short video</a> introducing the TrauMatrix project.</p>

<h3>Context</h3>
<p align="justify">Major trauma is defined as any injury that endangers the life or the functional integrity of a person. The Global Burden of Disease working group of the WHO has recently shown that major trauma in its various manifestations, from road traffic accidents, interpersonal violence, self-harm to falls, remains a public health challenge and major source of mortality and handicap around the world. Hopefully, it has also been shown that management of major trauma based on standardized and protocol based care improves prognosis of patients especially for the two main causes of death in major trauma i.e., hemorrhage and traumatic brain injury.  The classic pathway of a traumatized patient takes place in several stages : from the site of the accident where the patient is taken care of by the ambulance to the transfer to an intensive care unit (ICU) for immediate interventions and finally to the comprehensive care at the hospital. To be effective, patient management protocols require adjustments to the individual patient and clinical context on one hand and to the organizational context and trauma system on the other hand.
However, evidence shows that patient management even in mature trauma systems often exceeds acceptable time frames, and despite existing guidelines deviations from protocol-based care are often observed. These deviations lead to a high variability in care and are associated with bad outcome such as inadequate hemorrhage control or delayed transfusion. Two main factors explain these observations. First, decision-making in trauma care is particularly demanding, because it requires rapid and complex decisions under time pressure in a very dynamic and multi-player environment characterized by high levels of uncertainty and stress. Second, being a complex and multiplayer process, trauma care is affected by fragmentation. Fragmentation is often the result of loss or deformation of information. This disruptive influence prevents providers to engage with each other and commit to the care process.</p>

<p align="justify">In order to respond to this challenge, our program has set the ambitious goal to develop a trauma decision support tool, the TrauMatrix. The program aims to provide an integrative decision support and information management solution to clinicians for the first 24 hours of major trauma management. This program is divided into three steps.<br>
Based on a detailed and high quality trauma database, <b>Step 1</b> consists in developing the mathematical tools and models to predict trauma specific outcomes and decisions. This step raises considerable scientific and methodological challenges.<br>
<b>Step 2</b> will use these methods to apply them to develop in close cooperation with trauma care experts the decision support tool and develop a user friendly and ergonomic interface to be used by clinicians.<br>
<b>Step 3</b> will further develop the tool and interface and test in real-time its impact on clinician decision making and patient outcome.</p>

<h3>Hypothesis</h3>
<p align="justify">The global program TrauMatrix stands for the hypothesis that an integrative, interactive decision support tool relying on advanced machine learning based on detailed and heterogenous clinical data can considerably improve patient care and survival in major trauma.</p>

<h3>Objectives</h3>
<p align="justify">The objective of the global project is to develop an integrative solution for trauma management during the first 24 hours, the TrauMatrix. TrauMatrix will be an adaptive information management platform providing ergonomic, real-time decision-support to a broad range of clinicians. TrauMatrix will make use of advanced statistical tools and machine learning algorithms and articulate these with existing clinical recommendations in order to enhance clinician-driven decision-making. The platform will streamline the care process to make it patient-centered and facilitate information sharing among all professionals involved (dispatchers, nurses, anesthetists, radiologists, surgeons, blood bank specialists, etc). Such a tool is not intended to become a substitute to human-decision making but accompany clinicians and professionals to create a synergy.</p>

<h3>Originality</h3>
<p align="justify">Firstly, the proposal relies on an unlimited access to a unique database: the <a href="http://www.traumabase.eu/en_US" target="_blank">Traumabase</a>. With the objective of evaluating and improving the care of trauma patients, 15 French Trauma centers have decided to collaborate to collect detailed, high quality clinical data from the scene of the accident to discharge from the hospital. The resulting database, the Traumabase has prospectively gathered more than 20,000 trauma admissions data, and new cases are permanently recruited. The granularity of the collected data makes this observatory unique in Europe. The present consortium takes strategic advantage of an unrestricted access to this database to propose an innovative response to the public health challenge of major trauma.<br>
Secondly, to the best of our knowledge, such a trauma information platform currently does not exist. To develop and design an interactive, real-time, probabilistic decision-support and information management platform constitutes a major conceptual and scientific innovation. No proof of concept study exists that evaluates this approach on a large scale for complex medical decisions such as trauma care.<br>
Thirdly, handling trauma patients requires complex and multiplayer strategies and the medical community recognizes the need to adopt and develop new methods to eliminate preventable deaths and disabilities. Thus, the community is willing to make use of a large amount of data for diagnosis, decision-support and treatment.<br>
Lastly, from the statistical point of view, the proposal will develop innovative methods to tackle the important scientific challenge of handling highly heterogeneous data, with a large number of missing data. Indeed, despite the high quality of the Traumabase, since data collection is carried out by data technicians, there are many missing values that occur for different reasons (impossibility to make the measurement for technical issues or because of the patient’s state, no time to record the measure, etc.). Current data analysis tools and predictive models cannot be applied with restrictions. To develop innovative methods allowing exploitation of missing data, heterogenous coding and complex structure is an important scientific contribution. Any development in this field will be useful and applicable to a large array of scientific sectors.</br>
The project provides thus a unique opportunity for trans-disciplinary research and collaboration bringing together mathematical, methodological, technological, cognitive and medical expertise to design innovative methodological solutions to respond to complex challenges and improve patient care.</p>


