---
layout: default
title: Home
seo:
  type: Course
  name: {{ site.title }}
nav_order: 1
---

# {{ site.tagline }}

<!--{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}-->

This course provides a broad and deep treatment of modern statistical machine learning topics.  Students entering the course are assumed to have foundational working knowledge in statistics, probability, and basic machine learning concepts, though the course has been designed to provide a broadly accessible treatment of the topics covered.  

The course starts with a quick review of linear regression and classification, error metrics, and the bias-variance tradeoff.  We then delve into decision trees and deep learning techniques for non-linear regression and classification tasks.  The subsequent modules move beyond regression and classification tasks and turn to discovering patterns and low-dimensional structure via unsupervised learning.  Topics include clustering, dimensionality reduction and autoencoding methods, and matrix factorization.  The last module considers time series and sequential data sources via state space models and deep learning methods. 

## Teaching team

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Logistics
&nbsp;

**When**: Class is Tuesdays and Thursdays 9:45-11:15am PST.

**Where**: Class will be in person at
[NVDIA Auditorium](https://campus-map.stanford.edu/?id=NVIDIAAUD).

**Links**:
- [Ed](TODO):
  This is the main way that you and the teaching team should communicate:
  we will post all important announcements here, and you should ask
  all course-related questions here.
  For personal matters that you don't wish to put in a private Ed post, you can
  email the teaching staff at [TODO@lists.stanford.edu](mailto:TODO@lists.stanford.edu).
- [Canvas](#TODO): The course Canvas page
  contains links and resources only accessible to students ([Zoom link](TODO) for
  remote classes).
- [Gradescope](TODO): We use Gradescope
  for managing coursework (turning in, returning grades).  Please use your
  @stanford.edu email address to sign up for a Gradescope account.

**Prerequisites**: A well-prepared student will have knowledge of:
  * Math:
    * Linear algebra (matrix/vector operations, orthogonality, etc.)
    * Multivariate calculus (gradients, partial derivatives)
  * Probability:
    * Random variables, expectations, Gaussian distribution, conditional and marginal distributions
  * Statistics / machine learning basics:
    * Linear regression and classification and, ideally, overfitting and bias-variance tradeoff
    * Parameter estimation, including via maximum likelihood estimation
  * Programming proficiency in:
    * Python (preferred for this course), or
    * R, Julia, etc. with an ability to (i) pivot to Python with starter code or (ii) code independently in selected language

From experience, eager students with a strong quantitative background are able to catch up and fully participate.  

**Course Grade**: The course grade will be based on the following components.

- 5 Homework Assignments (45%): HW0 (5%), HW1 - HW4 (40%)
- Concept Quizzes (15%)
- Final Project (40%): Project midway (8%), Project report (24%), Project presentation (8%)