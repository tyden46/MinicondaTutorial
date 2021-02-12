# Miniconda Tutorial
## What is Miniconda?
Miniconda is a smaller version of Anaconda. Anaconda, in turn "is a distribution of the Python and R programming languages for scientific computing (data science, machine learning applications, large-scale data processing, predictive analytics, etc.), that aims to simplify package management and deployment." </br> </br>
Put simply, Miniconda is tool that allows you to easily install and use command line tools. It manages a lot of ugly things in the background so you don't have to worry about them! </br> </br>
## Prerequisites
This tutorial assumes you are on Pegasus, GW's Computing Cluster. </br></br> 
## Installing Miniconda
Watch this video for help installing miniconda https://youtu.be/B5jWDIN4B20 </br> </br>
## Your First Miniconda Environment
Run the following command:</br>
``conda create -n rahLabTutorial python=3.7`` </br></br>
Then:</br>
``conda activate rahLabTutorial``</br>
You just created your first environment, now let's install some tools!</br>
Run:</br>
``conda install -c bioconda mafft fastqc`` </br>
And finally run:</br>
``pip install omeClust``</br>
We just installed three tools. If we want to see all tools we have we can run:</br>
``conda list``</br>
Why are there so many more things listed? Conda manages dependencies so it also grabbed the extra things we needed to run our tools.</br></br>

## Three Tools For Three Data Formats - FASTQ, FASTA, and Distance Matrices
Run:</br>
