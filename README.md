# Code for extracting clauses from complex sentences

1. To execute in command prompt with a jar file, 

     a. Download [stanford-corenlp-2012-07-06-models.jar](https://github.com/evandrix/stanford-corenlp/raw/master/stanford-corenlp-2012-07-06-models.jar) into */lib* folder.
 
     b. Run the command:
   
     	Sample data set
     	
     		java –jar ClauseExt.jar data/in_sample.txt result/out_sample.txt

	Reverb data set

		java –jar ClauseExt.jar data/in_reverb.txt result/out_reverb.txt

	NYT data set

		java –jar ClauseExt.jar data/in_nyt.txt result/out_nyt.txt

	Wikipedia data set

		java –jar ClauseExt.jar data/in_wikipedia.txt result/out_wikipedia.txt


(**Note:** Data sets and ground truth are available at https://www.mpi-inf.mpg.de/departments/databases-and-information-
systems/software/clausie/)
