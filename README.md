# NCAA_2024_Article_Data
# Journal Article Data
## Reference data for the journal article, 
## "VIETNAMESE SENTENCE FACT CHECKING USING THE INCREMENTAL KNOWLEDGE GRAPH, DEEP LEARNING AND INFERENCE RULES ON ONLINE PLATFORMS"

Figure 5 below shows the proposed model for verifying the accuracy of Vietnamese sentences by integrating a Knowledge Graph with a Logic Programming Language, leveraging the Triple Classification task based on the KG-BERT model. As depicted in Figure 5, the proposed model not only performs fact-checking based on trained knowledge but also verifies new information not previously encountered. By integrating supplementary knowledge from internet sources, the model can effectively verify misinformation circulating on Vietnamese and global media and online platforms.
 
![image](https://github.com/vhho/NCAA_2024_Article_Data/assets/30404000/ab11cb9f-a7e9-4bdc-8740-e7d59a052762)
 
                           (a) Stage 1

![image](https://github.com/vhho/NCAA_2024_Article_Data/assets/30404000/782870cb-c727-4547-992f-b2a7d0955b44)

                           (b) Stage 2

![image](https://github.com/vhho/NCAA_2024_Article_Data/assets/30404000/8f86b792-c44b-4187-857c-d2a04a33252e)

                           (c) Stage 3

![image](https://github.com/vhho/NCAA_2024_Article_Data/assets/30404000/31c8ba53-c73b-4553-b75c-afa70cb26f46)

                           (d) Stage 4

![image](https://github.com/vhho/NCAA_2024_Article_Data/assets/30404000/34e0c252-8d5d-4385-981a-2b74296d5dcd)

                           (d) Stage 5

               Figure 5: The proposed fact-checking model

The data used in this paper includes the following files:

**1) Original KG:** This is a repository of Vietnamese-based triples used as evidence to verify information.

**2) Logical Rules:** This contains the Logical Rules used by Algorithm 2 to infer new triples, Inferred Triples, in the Datalog language.

**3) Complete KG:** This contains the complete dataset, Complete KG, which includes the original dataset, Original KG, plus the newly inferred and conflict-tested triples, Validated Triples.

**4) Translated FEVER:** This contains claims that had been translated into Vietnamese from the FEVER dataset with labels belonging to the SUPPORTS and REFUTES categories.

**5) Claim Sentences:** This contains the sentences for fact-checking.

**6) TriplesForFalseClaim** This comprises files containing triples collected from the internet related to False Claims, which will be combined with the triples in the 'Complete KG' dataset and the triples generated based on inference rules to create the 'Comprehensive KG' dataset.

