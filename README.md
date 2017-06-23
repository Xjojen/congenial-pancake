# BAM_Statistician
*A simple, combination of python and samtools, BAM file statistical tools*<br/>
BAM_Statistician is a simple and fast python file to count some important statistical indicators. Upon loading a BAM file, BAM_Statistician will convert the BAM format to SAM format, and act as a statistician to count some important statistical indicators of alignments/reads as it walk through the file. If you only want to summarize BAM by few indicators, BAM_Statistician is probabyly the fastest and simplest one, particularly if run under PyPy.<br/>
# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
# Prerequisites
# Installing
# Running the tests
# Deployment
# Built With
# Contributing
# Versioning
- v1.0.0-beta: The primitive version, exists lots of bugs and syntax in a mess. Use python to compile and excute the program in the cluster of Beijing genome institue for a 9.4G BAM file spend spend 2:25:56s.
- v1.0.1: Uniformize the syntax of the program by Camel case. Fix some bugs that are already known.
- v1.1.0: Replace python compiler with Just-in-Time compiler which make the program twice as quick as the old one.
- v2.0.0: Current version, change the parameter and return value of most functions to improve the efficiency. In this version, use pypy to compile and excute the program in my mac(2.7 GHz Intel Core i5 & 8 GB 1867 MHz DDR3) for the same 9.4G BAM file only takes 12:45s
# Authors
Jojen Shaw - Undergraduate of Computer Science  - [Jojen's blog](www.jojen.com)
Keen in Data mining, Machine Learning and Deep Learning, welcome to comunicate with me(q614562018@gmail.com)!
# License
This project is licensed under the GNU General Public License v3.0 - see the [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) file for details
# Acknowledgments
- Thanks for those people who discusse with me and provide the new idea.
- Thanks for some open source packages and softwares, for instance, samtools and pypy.
