+++
title = "A Structural Theorem for Local Algorithms with Applications to Coding, Testing, and Delegation"
date = 2020-07-15
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tom Gur", "Oded Lachish"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = [0]

# Publication name and optional abbreviated version.
publication = "In submission"
publication_short = "In submission"

# Abstract and optional shortened version.
abstract = "We prove a general structural theorem for a wide family of local algorithms, which includes property testers, local decoders, and PCPs of proximity. Namely, we show that the structure of every algorithm that makes $q$ adaptive queries and satisfies a natural robustness condition admits a sample-based algorithm with $n^{1- 1/O(q^2 \\log^2 q)}$ sample complexity, following the definition of Goldreich and Ron (TOCT 2016). We prove that this transformation is nearly optimal.\n\nUsing the unified view that our structural theorem provides, we obtain results regarding various types of local algorithms, including the following.\n\n* We strengthen the state-of-the-art lower bound for relaxed locally decodable codes, obtaining an _exponential_ improvement on the dependency in query complexity; this resolves an open problem raised by Gur and Lachish (SODA 2020).\n\n* We show that any (constant-query) testable property admits a sample-based tester with sublinear sample complexity; this resolves a problem left open in a work of Fischer, Lachish, and Vasudev (FOCS 2015) by extending their main result to adaptive testers.\n\n* We prove that the known separation between proofs of proximity and testers is essentially maximal; this resolves a problem left open by Gur and Rothblum (ECCC 2013, Computational Complexity 2018) regarding sublinear-time delegation of computation.\n\nOur techniques strongly rely on relaxed sunflower lemmas and the Hajnal–Szemerédi theorem."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "files/motiondraw-abstract.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Poster", url = "files/motiondraw-poster.pdf"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
