index_content = """---
layout: default
title: Home
---

# Expert VMS & Technical Solutions
Helping partners master VMS platforms and drive long-term profitability.

## Our Expertise
* **Automated Insights:** Streamlining technical data for better decision making.
* **Strategic Growth:** Cutting expenses through efficient system integration.

[View our Services](/services)
"""

with open("index.md", "w") as f:
    f.write(index_content)