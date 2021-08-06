<!--
Name of your teams' final project
-->
# Prior for Value-Aligned Agent
## [National Action Council for Minorities in Engineering(NACME)](https://www.nacme.org) Google Applied Machine Learning Intensive (AMLI) at the `PARTICIPATING_UNIVERSITY`

<!--
List all of the members who developed the project and
link to each members respective GitHub profile
-->
Research Mentor:
- [Md Sultan Al Nahian](https://github.com/sultanalnahian) - `University of Kentucky`

Developed by: 
- [Elizabeth Eyeson](https://github.com/lizagit) - `University of Colorado Boulder`
- [Kavisca Kuruparanantha](https://github.com/Kavisca) - `University of Kentucky` 
- [Steven Aponte](https://github.com/StevenAponte815) - `Stevens Institute of Technology` 

## Description
<!--
Give a short description on what your project accomplishes and what tools is uses. In addition, you can drop screenshots directly into your README file to add them to your README. Take these from your presentations.
-->
Goal-driven AI is susceptible to neglecting ethical concerns due to its blind prioritization of optimization in order to accomplish its goal with maximal performance. This project is a prior to a value-aligned agent that will be taught human values such that it will be trained to take actions that closer align with "normative" human behavior.

Our models accomplish the following tasks: 
1. Classification task where actions are classified as either normative or non-normative.
2. Sequence generation task where sequences describing the intentions behind actions taken are produced.
3. Deep Pyramid CNN were used an an efficient way to represent long-range associations in text for normative and non-normative classification.

## Usage instructions
<!--
Give details on how to install fork and install your project. You can get all of the python dependencies for your project by typing `pip3 freeze requirements.txt` on the system that runs your project. Add the generated `requirements.txt` to this repo.
-->
1. Fork this repo.
2. Change directories into your project.
3. On the command line, type `pip3 install requirements.txt`
4. DPCNN requires Tensorflow 1.14-1.19 and Python 3.6. Refer to README in DPCNN-master folder for more information.
5. Colab or Jupyter is required for the Seq2Seq and Bidirectional LSTM.

## Acknowledgments
1. DPCNN Original Github Repo: https://github.com/HaishuoFang/DPCNN
2. Seq2Seq Tensorflow Documentation and Examples: https://www.tensorflow.org/addons/tutorials/networks_seq2seq_nmt
