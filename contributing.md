# How to contribute

Thanks for wanting to contribute code to the I3 shared data processing scripts repository! The focus of this repository is scripts used broadly on innovation data, but if you have general scripts too feel free to add them. These aren't strict guidelines, and we'll accept submissions in any format -- but the better documented the code you submit is, the more likely it is to be used and shared.

This repository is for 2 different kinds of contribution:

* **link to an external repository: (recommended)** you or someone else have your code hosted on GitHub, and you'd like to link it. This option is recommended anyway, but it's particularly important if you plan to update your code regularly, you plan to maintain the code, or you're submitting code that's maintained by someone else
* **the scripts/files themselves:** you'd like to host your code in this repository, and it doesn't live publicly anywhere else. You could choose this option if you're not planning to change the code at all, and would like us to look after it

## Instructions

This repository accepts contributions in the form of pull requests. If you've not made one of these before, this process is documented [here](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

* if you are submitting a link to an external repository:
	* add a link to the [README](./README), along with a short description of the code + the dataset it applies to
* if you are submitting a set of code files:
	* create a new folder with the name of your project, containing:
		* your files
		* a README that documents the code (take a look at the Social Science Data and Code Sharing Guidelines [Template README](https://github.com/social-science-data-editors/template_README/blob/releases/README.md))

## Guidelines

In all cases, your pull request should:
* reference code that is broadly related to *processing innovation data*. 'process' in this context could refer to a number of different operations, including (but not limited to):
	* normalisation
	* disambiguation and entity reconciliation
	* web scraping
	* parsing web-scraped data
	* transformation/merging different datasets together
	* standardising datasets
	* deduplication
* contain a link to the dataset(s) that the code is intended to be run on, or a description of how to obtain them if they are not open-access. (while you're here, you might also want to add the dataset URL to our [Innovation Datasets Index](https://docs.google.com/spreadsheets/d/1bdyhGrj0oNz-_qW3Rv2GNGqhZZ73rgj-DYWePLA_1Ms/edit#gid=1389884911))
* any code in your pull request should be thoroughly documented with a README file. You can use the Social Science Data and Code Sharing Guidelines [Template README](https://github.com/social-science-data-editors/template_README/blob/releases/README.md) file to guide the submission process

This is *not* the place to submit:
* datasets themselves (instead, add them to our [Innovation Datasets Index](https://docs.google.com/spreadsheets/d/1bdyhGrj0oNz-_qW3Rv2GNGqhZZ73rgj-DYWePLA_1Ms/edit#gid=1389884911))
* data processing scripts that are specific to *non* innovation-related datasets (though general scripts that you have found useful for data workflows are warmly invited)
