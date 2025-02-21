# CORE Skills - Data science in reliability course

## About this course

Reliability analysis on in-service assets uses well-established methods to, for example, determine mean-time-to-failure (MTTF) estimates or identify failure modes. However, the data inputs to these calculations depend on how the raw data from maintenance repair records has been processed. Processes to extract and clean raw maintenance data are often ad hoc and performed differently by each engineer. As a result calculations for asset reliability measures and identification of historical events and failure modes are difficult to replicate. Currently, the process is manual, time-consuming and not scalable. 

The goal of this course is to enable practicing reliablity engineers to use state of the art, open-source code-based tools, to interrogate their maintenance work order data and extract MTBF values and failure mode information.

## Audience for this course

Target participants are involved in maintenance strategy development, day-to-day reliability analysis of existing plant, reliability improvement efforts, or maintenance management metrics.

Participants need to have 1) an understanding of how Weibull parameters are used in characerising failure behaviour (wear in, wear out and random) and for settting intervals in maintenance strategy development and 2) be able to understand simple characterisation of statistical distributions such as mean and variance. 

The material in this course can be applied to all asset classes: rotating equipment, mobile, linear, electrical and computing infrastructure so this is open to all engineering disciplines working in reliability engineering roles.

## Learning outcomes 

At the end of this course participants should be able to:

1. Estimate the parameters for a Weibull distribution on the life of an asset from maintenance work order data.
2. Determine key failure modes for an asset from maintenance work order data.
3. Describe the impact of pre-processing decisions on outputs.

## Getting access

All course content is delivered using a virtual cloud server using Jupyter notebooks. Examples of these notebooks are available on this Gitsite. These are comprised of text and Python code blocks. If you are new to Jupyter notebook please see section [Jupyter notebook fundamentals](#ipynb-fundamentals) at the end of this readme.

The code blocks are used to demonstrate the data processing and calculations. There is no need to be able to code in Python yourself. 

Participants in the course will use three browser windows, one accessing the Notebooks (for content), one for Menti (for anonymised Q&A) and one for Teams (to communicate with the presenters and other participants).

## Acknowledgement of use of the Python Reliability package
We acknowledge use of the open-source python package [Reliability](https://reliability.readthedocs.io/en/latest/) - A package containing utilities for reliability engineering. The reliability package is licensed under the LGPLv3. Under the LGPLv3 license, the use of reliability is FREE and unrestricted for both individuals and commercial users. We have made use of code snippets from this reliability package throughout this course. You can find out more information about this package [here](https://github.com/MatthewReid854/reliability).

## About your presenters

This course has been developed by Tyler Bikaun and Melinda Hodkiewicz. It draws on Melinda's experience as a practicing maintenance engineer and lecturer in asset management, maintenance and reliability over the last 30 years,  the tools and processes developed by Tyler during his PhD study as well as tools and processes developed by the [Centre for Transforming Maintenance through Data Science](https://www.maintenance.org.au/) and the [NLP-TLP group](https://nlp-tlp.org/) at UWA. 

### Tyler Bikaun: 

Industrial Maintenance | Mechanical Engineer - PhD program in Technical Language Processing
</br>
💼 [LinkedIn](https://www.linkedin.com/in/tyler-bikaun/)
📚 [Google Scholar](https://scholar.google.com/citations?hl=en&user=jZpJEnEAAAAJ)

### Melinda Hodkiewicz

Maintenance | Reliability, Risk and Safety | Asset Management - Professor
</br>
💼 [LinkedIn](https://www.linkedin.com/in/melinda-hodkiewicz-b6bbba7/)
📚 [Google Scholar](https://scholar.google.com/citations?hl=en&user=1JGboosAAAAJ)

## About CORE SKILLS and CORE INNOVATION HUB

Supporting the skills pathways from today to tomorrow for Industry 4.0 - [find out more about data science at CORE](https://www.corehub.com.au/data-science)

### Zane Prickett

Director Unearthed and CORE | Engineer
</br>
💼 [LinkedIn](https://www.linkedin.com/in/zaneprickett/)

### Tamryn Barker

CORE Skills lead | Business and innovation strategy and execution
</br>
💼 [LinkedIn](https://www.linkedin.com/in/tamryn-barker-%E8%B0%AD%E7%9D%BF-gaicd-965b4321/)

## Contact details <a class="anchor" id="Contact-details"></a>

All contact should be made to Tamryn at tamryn@corehub.com.au

## License 

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/3.0/">Creative Commons Attribution 3.0 Unported License</a>.

<h2 id="ipynb-fundamentals">Jupyter notebook fundamentals</h2>
This course will be entirely ran out of Jupyter notebooks which are interactive, online, environments that use the Python programming language. Before the course commences, it is strongly recommended that you get acquianted with the basics of using Jupyter notebooks. There are many resources online that cover its usage including <a href="https://www.dataquest.io/blog/jupyter-notebook-tutorial/">Data Quest - Jupyter Notebook Tutorial</a> and <a href="https://realpython.com/jupyter-notebook-introduction/">RealPython - Jupyter Notebook Introduction</a>. Do not worry about the details of setting up these notebooks as they will be set up online and managed by CORE, but an understanding of the ways-of-working will be very beneficial to the flow of this course.
