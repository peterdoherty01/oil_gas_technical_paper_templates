The way in which engineers report and publish technical papers hasn't changed much over the past several decades.

At Computation Hub, we have peer-reviewed some novel work involving Machine Learning. It got us thinking about the whole review process when we reviewed the paper.

One of the main reasons to publish work at a conference is to share knowledge so that it can benefit others in the industry. The main issue that I find is that, one cannot easily take the work presented, validate it, test it or build upon it. Basically, I cannot copy and paste algorithms into the format I'm working in.

## Fast Forward

Normally, we use tools like Excel or Python to analyze data and generate results. These results are then transferred as tables and figures into Word documents. This is **a painful, manual way** to 1) perform analysis and 2) validate work as from a quality control perspective.

Thanks to research by [Alfonso R. Reyes](https://www.linkedin.com/pulse/evolution-data-science-machine-learning-artificial-petroleum-reyes/), we can deduce that Python and R are the languages increasingly used amongst engineers for Machine Learning and Data Science. Moreover, more and more papers are being published with Machine Learning and Data Science methodologies. It can also be deduced from the popularity of open online courses and competitions proposed by [Kaggle](https://www.kaggle.com/), that new engineers to the industry prefer working with these languages.

**A streamlined way** to make papers more useful to your organization and the industry is required. Performing data analysis and presenting results tables and figures in one centralized place is a good solutions. This could be done with Juypter Notebooks and source control (GitHub). When ready for publication, one can compile the notebook for PDF or other. Thus, reducing tedious hand checks.

## Practices Beyond Oil & Gas

You might be asking yourself: "Where else is this done?"

I've gathered some examples from the Finance, Mathematical and Scientific communities hereafter:

* Finance: https://nbviewer.jupyter.org/github/vincentarelbundock/Reinhart-Rogoff/blob/master/reinhart-rogoff.ipynb

* Mathematics: https://nbviewer.jupyter.org/github/fonnesbeck/multilevel_modeling/blob/master/multilevel_modeling.ipynb

* Physics: https://nbviewer.jupyter.org/github/waltherg/notebooks/blob/master/2013-12-03-Crank_Nicolson.ipynb

## Getting Onboard

Is a big effort required to adopt this method? No. Simply put, the industry already uses languages like Python and R for their analysis work anyway. Writing reports in this way does not require a big upheaval in any way.

I haven't looked at all the limitations but some barriers could age and culture. 

Currently, in the draft template proposed, there is no automatic figure or table numbering. But this might be addressed by using LaTex. Moreover, if another markup format is used, PanDoc could be a solution to offer a **zero cost alternative** to current methods.

**One more reason** to get onboard with this idea, it's compelling for new engineers to the industry. **Second**, it offers a truly collaborative channel among team members to ensure a quality paper is proposed for review. Focusing on the content instead of repetitve, manual tasks such as copying and pasting into Word.

## Example Template - A Way Forward

To get a clearer picture of what I'm discussing in this article, I've set up an example Jupyter Notebook draft template and published it here. It could be adapted for R too.
These notebooks could be easily put behind a paywall to maintain revenue channels for the conference organizers.

The template can be updated via [GitHub](https://github.com/
) and is **open to contributions** from the industry.

**The idea is to allow the industry to build upon this template through open collaboration under the GNU General Public License v3.0.**

## Conclusion

This is not a "game changer" for the industry. As working in the browser becomes more mainstream in oil & gas, programming in the browser to report our learnings should be adopted too. An improvement like this, with not-so-much effort, can contribute to:

1. Boosting the quality of the industries work
2. Encouraging young engineers to publish their work

## Further Reading

1. [Intro to Anaconda]()
2. [Intro to Jupyter Notebooks]()
3. [Intro to R]()
4. [Publishing Jupyter Notebooks, Documentation](https://ipypublish.readthedocs.io/en/latest/)
5. [A Gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
6. [A Gallery of interesting Jupyter Notebooks in languages other than Python](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks#notebooks-in-languages-other-than-python)
7. [Markdown Explanation](https://en.wikipedia.org/wiki/Markdown)
8. [Rmarkdown Journal templates](https://github.com/rstudio/rticles/tree/master/inst/rmarkdown/templates/rjournal_article)
9. [Rstudio Gallery](https://rmarkdown.rstudio.com/gallery.html)

## Share Your Thoughts & Contribution

Did you find this article interesting? If you're interested in supporting or contributing to this proposal please contact me at: peter@computationhub.com. By doing so, would help move this idea to the next step.