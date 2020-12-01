# CoPE – COVID-19 Policy Evaluation tool
#
# An agent-based model of the social spread of COVID-19 with a focus on 
# individual-level behavioral responses to policy. 
# 
# Thank you for your interest in CoPE. 
# If your use of CoPE results in a publication, please cite as follows: 
# 
# Rai Group. (2020). CoPE: COVID-19 Policy Evaluation tool
# 	 Version 0.1. [Computer Software].
#
# This project is under active development. If you find something that needs our 
# attention, please send a message to BAMEx.devs@gmail.com. 
# Your feedback and input is extremely valuable. Thank you!
#
# 
# CovidABM7 
# UT Austin, RaiGroup
# Created: 06/12/2020
#
# 

You'll need: 

R
	with libraries:
	rgdal
	profvis
	future
	fastmatch
	spatstat
	sp
	R6
	jsonlite
	RSQLite
	DBI
	ggplot2
	lubridate
	reshape2
	scales
	tidyverse
	dplyr
	ggraph
	tidygraph
	igraph
	gridExtra


python3 (https://docs.python-guide.org/starting/install3/osx/)
	with: 
	PySimpleGUI (https://pypi.org/project/PySimpleGUI/)

a terminal session

From a terminal type 'python3 CovidABM7_configurator.py' to set the settings you want and build a run.

Follow it's instructions and from the same terminal type './RunCovidABM<your model number>.sh' 

