<!-- ---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->


# 👋 Hi there, I'm Aryan Atre

🎓 Master's Student in Artificial Intelligence Systems at the **University of Florida**  
📍 Based in Gainesville, FL | Originally from Mumbai, India  
📫 [Email Me](mailto:atrearyan@gmail.com) | [LinkedIn](https://www.linkedin.com/in/aryan-atre)

---

## 🚀 About Me

I'm an AI engineer and software developer passionate about building impactful, intelligent systems. I focus on leveraging Python for deep learning, JavaScript for full-stack applications, and Golang for backend systems. My experience spans across healthcare, finance, and generative AI domains.

---

## 💻 My Preferred Stack

| Priority | Language     | Usage                               |
|----------|--------------|-------------------------------------|
| 🥇       | **Python**    | AI/ML, Deep Learning, Backend APIs  |
| 🥈       | **JavaScript**| Full-stack (MERN), dashboards       |
| 🥉       | **Golang**    | Backend services, system-level apps |

---

## 🛠️ Technical Skills

- **Languages**: Python, JavaScript, Golang, Java, C/C++, R  
- **AI/ML**: PyTorch, TensorFlow, LangChain, Whisper, ResNet-50, YOLOv8, Grad-CAM  
- **Cloud & DevOps**: AWS (EC2, Lambda, S3), Azure, Docker, Kubernetes, Prometheus, Grafana  
- **Databases**: MySQL, Cassandra and postgresql
- **Other Tools**: Git, Unix, MS Office, Google Suite

---

## 🧠 Projects

### 🔍 Context-Based Intelligent Knowledge Retrieval (GenAI)  
_Aug 2024 – Present_  
Built a RAG-based system using LangChain, OpenAI APIs, Pinecone, Whisper, and Flask with multimodal support for text and audio.  
☁️ Dockerized and monitored with Prometheus + Grafana.

### 🫁 Pneumonia Classification with ResNet-50  
_Dec 2023_  
Used deep learning and Grad-CAM to classify pneumonia from chest X-rays, including density region analysis.

---

## 💼 Experience

### 💻 Data Strategy and Machine Learning Intern | Wpp
_Jun 2025 – Aug 2025_ 
- Analyzing shopping engagement and develop data-driven strategies.
- Utilized AI-powered analytics platforms to generate actionable insights.
- Applied advanced ML techniques including neural networks (PyTorch) for synthetic data generation simulate market response scenarios.

### 🧠 Machine Learning Intern | Ernst & Young  
_Jun 2024 – Aug 2024_  
- Enhanced NLP with OCR + LLMs  
- Developed GenAI financial analytics  
- Deployed on AWS Lambda + EC2

### 🎙️ ML Research Intern | Neural Garage Pvt Ltd  
_Jan 2024 – May 2024_  
- Built AI pipelines for lip-syncing  
- YOLOv8 anomaly detection  
- Dockerized for real-time production

<!-- ### 🔐 Software Dev & Cybersecurity Intern | Securizen Pvt Ltd  
_Dec 2023 – Jan 2024_  
- Improved CloudCCTV dashboard (MERN)  
- Conducted white-hat security testing   -->

---

## 🏅 Certifications

- Amazon Bedrock  
- Data Analyst 
- A/B Testing
- DL with CNN, RNN, NLP  
- AWS & Azure Cloud Management  
- Agile Project Management  
- SAP OLAP/OLTP  
- Microsoft Azure Fundamentals  
- Cloud Computing & MLOps

---

<!-- ## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=atrearyan&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=atrearyan&langs_count=8&layout=compact&theme=tokyonight&hide_border=true&hide=jupyter%20notebook" alt="Top Languages">
  <br>
  <img src="https://github-readme-stats.vercel.app/api?username=atrearyan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats">
</p>

--- -->