# eacl2017

Data employed in experiments in the following publication:

> Yvette Graham, Qingsong Ma, Timothy Baldwin, Qun Liu, Carla Parra, Carolina Scarton. 2017. Improving Evaluation of Document-level MT Quality Estimation. To appear in Proceedings of the 15th European Chapter of the Association for Computational Linguistics (EACL), Valencia, Spain. 
> [PDF](https://www.computing.dcu.ie/~ygraham/grahametal-eacl17.pdf)

Experiments involved collection of human judgments of the adequacy of translations using direct assessment on Mechanical
Turk in two separate experiment runs (Run A and Run B). All files have been anonymised to avoid linking back to specific MTurk worker accounts. Human assessment is done on the sentence level and combined into a human score for documents to be employed for the prupose of evaluating MT document-level quality estimation systems.

The following is an explanation of what files can be found where:

  * ```./batched-hits``` &#8594; Batch files downloaded from Mechanical Turk for runs A and B.

  * ```./data```  &#8594; Source sentences, MT output translations and reference translations.
  
  * ```./n``` &#8594; Downsampling experiment data for runB
  
  * ```./runA``` &#8594; Data analysis for runA
  
  * ```./runAB-enes.csv```  &#8594; Final scores for documents from runs A and B where A1.Z ==scores from run A; A1.N==number of judgments used to produce final score for document; A2.Z & A2.N are equivalent run B files
  
  * ```./runB``` &#8594; Data analysis for runB
  
  * ```./seg-key-enes``` &#8594; Key linking the human judgments back to the original documents by line number

