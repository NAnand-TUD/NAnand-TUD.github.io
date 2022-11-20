---
title: 'A Unified Geometry Parametrization Method for Turbomachinery Blades'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - R Agromayor
  - N Anand
  - JD Müller
  - M Pini
  - LO Nord

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Elsivier
publication_short: Computer Aided Design Journal

abstract: Turbomachinery design is increasingly carried out by means of automated workflows based on high-fidelity physical models and optimization algorithms. The parametrization of the blade geometry is an essential aspect of such workflows because it defines the design space in which an optimal solution can be found. Currently, parametrization methods used for this purpose are often tailored to one particular type of turbomachinery blade, do not provide shape derivatives required for gradient-based optimization, or are not suited to re-parametrize a baseline blade geometry defined by a set of scattered point coordinates in a systematic way. This paper thus presents a general blade parametrization method for axial, radial, and mixed flow blades based on typical turbomachinery design variables and NURBS curves and surfaces. The shape derivatives are computed by means of the complex-step method, allowing the integration of the parametrization into gradient-based shape optimization workflows. In addition, the method enables the re-parametrization of a blade geometry defined by a cloud of points by solving a two-step optimization problem. The capabilities of the method are demonstrated by replicating eight blade geometries in two and three dimensions with an accuracy comparable to the tolerances of current manufacturing technologies.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0010448520301809'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
