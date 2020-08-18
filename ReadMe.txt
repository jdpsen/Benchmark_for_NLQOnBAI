This Repo contains the benchmarks we used to validate Natural Language Querying on BAI (Business Automation Insight) data.
Each benchmark consists of the following:
	a) An Ontology in .owl format as derived from the actual event logs as JSON documents.
        b) A set of natural language queries as tried by business users on this domain. We also provide a high level
	categorisation of the queries in terms of their complexity.
The references of the domains used are:
1. BPI-Application/offer: We used the data released as part of BPI 2017 Challenge. It contains events pertaining to loan applications and offers created for these applications.
2. Statechart: It has software event logs obtained through running a process mining program over a data dump. The data was first used here "Statechart Workbench and Alignments Software Event Log"
3. BPM service for workflow automation on case activities:  This is an IBM internal  BPM process deployed for IBM workflow automation to track case activities.
4. ODM service on loan validation: This BAI data set is generated from ODM decision running on Loan Validation. Data available at https://github.com/IBM-DBA/bai-ai-samples/tree/master/decisions/data.

Please contact Jaydeep Sen (jaydesen@in.ibm.com) from IBM Research AI, India Lab for any queries on the benchmarks.
