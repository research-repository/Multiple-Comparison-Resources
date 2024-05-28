# Multiple-Comparison-Resources

This directory contains a file that presents the results of an inferential analysis on the allocation of resources from the Ministry of Agriculture, Livestock and Supply (MAPA) between the states of Brazil.

The "Results_Multiple_Comparison_States.xlsx" file contains the results of the Dunn test, a statistical analysis used to compare multiple groups and identify significant differences between them. In this case, the groups are the Brazilian states and the variable analyzed is the value referring to the allocation of MAPA resources.

The file is in XLSX (Excel Open XML Spreadsheet) format and has the following columns:

.y.: Variable for the values of resources allocated by MAPA to the states

group1: Name of the first state being compared

group2: Name of the second state being compared

n1: Sample size of the first state

n2: Sample size of the second state

statistic: Value of the Dunn test test statistic

p: p-value associated with the Dunn test

p.adj: p-value with Bonferroni correction p-value associated with Dunn's test

p.adj.signif: Indicates whether the difference between states is statistically significant (*) or not (ns)
