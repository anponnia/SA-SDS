# SA-SDS
Artifacts related to Stochastic Sequence Analysis of Secondary Data Source
## Content description
### AuditXML2CSV.ipynb
Jupyter notebook to flatten multi-part audit records extracted from three RDBMS database tables into a single flattened CSV. This includes code to parse the XML format audit details where applicable.
### TagAudit.ipynb
Jupyter notebook to parse and assign tags - uses prior heuristic knowledge to determine the sequence and occurence of audit entries to actions observed by an expert. 
### matrix.txt
Sequence analysis of states as observed in audit log.
### HMModel.png
Heuristic Miner Model for the observed process for a period encompassing 60 orders executed in 4 batches.
### OnPromToolChain.png
Tool chain representation as per https://onprom.inf.unibz.it/ : onprom, an Ontology-based Data Association
(OBDA) event log extraction tool suite
### OnpromHM.xes
Baseline XES generated using ONPROM
### OnpromSASDS.xes
Modified XES after manually applying corrections based on SA-SDS analysis.
### RawXES.png
Statistics from baseline XES generated using OMPROM
### SASDSModel.png
Updated process model after manual application of SA-SDS technique.
### histogram.png
Pictorial representation of audit log

