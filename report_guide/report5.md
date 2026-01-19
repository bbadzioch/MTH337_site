# Example: Code sequencing


**Bad:** In the code below the function ``ball_height()`` first appears before it is defined.
This code is confusing to read since when one first sees ``ball_height()`` it is not clear what
it is and where it is coming from.


:::{figure}../_static/report_guide_samples/report_sample5a.png
:alt: Bad code sequencing example
:class: report-guide-img
:::

**Also bad:** The code below will work if one executes the bottom code cell before executing
the top one, but anyone reading the report will do it in the opposite order,
from top to bottom, and this will result in an execution error:

:::{figure}../_static/report_guide_samples/report_sample5aa.png
:alt: Another bad code sequencing example
:class: report-guide-img
:::


**Good:**  Code is entered sequentially and it is split into separate cells to better explain its purpose and structure.

:::{figure}../_static/report_guide_samples/report_sample5b.png
:alt: Good code sequencing example
:class: report-guide-img
:::
