# Code for extracting clauses from complex sentences

1. To execute in command prompt with a jar file, 

     a. Download [stanford-corenlp-2012-07-06-models.jar](https://github.com/evandrix/stanford-corenlp/raw/master/stanford-corenlp-2012-07-06-models.jar) into */lib* folder.
 
     b. Run the command:
   
     	java –jar ClauseExt.jar data/in.txt result/out.txt

	Reverb data set

		java –jar ClauseExt.jar data/in_reverb.txt result/out_reverb.txt

	NYT data set

		java –jar ClauseExt.jar data/in_nyt.txt result/out_nyt.txt

	Wikipedia data set

		java –jar ClauseExt.jar data/in_wikipedia.txt result/out_wikipedia.txt


2. To use the source
 
  a. Software Required:

                         edu.mit.jwi_2.1.4.jar
  
                         edu.sussex.nlp.jws.beta.11.jar

                         jaws-bin.jar

                         stanford-corenlp-2012-07-06-models.jar

                         stanford-corenlp-2012-07-09.jar
 
                         xom.jar
 
   b. Input: **/data/in.txt**

   c. Output: **/result/out.txt**
 
   d. Run the source file **ClauseExt.java**
