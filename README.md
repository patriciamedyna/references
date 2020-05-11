Publication repository whose main goal is the keep all references used by KnEDLe Project members.

# Instructions for the bib file

**Please check your BIB entries**

Entries generated automatically at **Google Scholar usually have mistakes**, such as:
* Bad entry type, e.g. a technical report is in the form of "@Article" instead of "@TechReport", papers in conferences included as "@Miscelaneous" instead of "@InProceedings", etc.
* Missing information, e.g. PhD thesis without school name, missing year, missing publisher, missing conference name, etc.
* Repeated information, e.g. publication year appears in the field year and also in the conference name. The publisher appears in the name of the conference and in the field publisher, etc.
* Several other mistakes. Again, please check your references instead of simply copying from Google.

Give as much information as possible. If possible, include the abstract.

Please follow a fixed standard for the search key. Teo's suggestion: 
A_B_C_D_E
where
* A: last name of the first author. In the case of compound names, use camel case, e.g. "deCampos".
* B: last name of the second author. If there are more than two authors, use the word "etal"
* C: one key word from the title of the paper, e.g. "DeepLearning", "LSTM".
* D: Acronym of the conference or journal where this was published, e.g. "CVPR", "arXiv".
* E: Publication year.

# Summarising each reference

This is based on Vinicius' strategy. For each paper that you read, please write a little LaTeX file (with a couble of paragraphs) with the same code as the bib entry, for instance, name it A_B_C_D_E.tex (following the convention above). In this file, please write the following:
* The first sentence tells very briefly what was proposed by the authors (cite the paper with \cite{A_B_C_D_E}).
* The second sentence should mention the problem at hand and what motivated the proposed method.
* Write between 2 and 4 sentences about the steps of the proposed method.
* Write 1 or 2 sentences about the experiments and results, including the dataset and some (quantitative and/or qualitative) relevant results. 
* Finish by discussing the pontential next steps, i.e., how can the method be applied (in ways that have not yet been exploited by the authors) or what can be improved.

## Examples
* [Pedro's "broad and shallow" review @GitLab](https://gitlab.com/UnBVision/master-thesis/-/tree/master/papers/paper-readings-and-impressions). This works very well if your focus is on reading and cataloguing a large number of papers. Note: his repository is private, but it's worth asking Pedro for access.
* [Fred's templat for "deep" summaries of papers, here in directory `paper_review_template`](paper_review_template)
