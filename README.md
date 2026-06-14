# guidance-R-pref
Section preferences on R packages and code, organized by topic below.

# Style
Follow the [tidyverse style guide](https://style.tidyverse.org/).
The link has very detailed information.

# Data frames
Use data.tables ([data.table package](https://cran.r-project.org/package=data.table)), tibbles ([tibble package](https://cran.r-project.org/package=tibble) or [readr package](https://cran.r-project.org/package=readr) or the [tidyverse set of packages](https://cran.r-project.org/package=tidyverse)), or base R data frames.
But do not mix them within a repository.
These three are all quite different.
If possible, stick to a single approach withing your groups of regular collaborators.

# Combining multiple ggplot2 plots
Use the patchwork package for this task.
It is the simplest and most modern option.






