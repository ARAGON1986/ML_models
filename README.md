# ML_models

AI 900 MACHINE LEARNING FOR AZURE

ML Model
	Prediction engine to forecast the future
	Program that can be used to recognize a pattern in data
	
DESCRIBE AI WORKLOADS

AI WORKLOADS
	PREDICTION AND DEMAND FORECAST
	ANOMALY DETECTION
	IMAGE RECOGNITION 
	NATURAL LANGUAGE PROCESSING
	KNOWLEDGE MINING
	CONTENT MODERATION
	GENERATIVE AI 
	
GUIDING PRINCIPLES IN AI
	Moral and ethical considerations
	Decisions that are illegal,cannot be explained,harmful 
	Fairness
		Decisions made on innacurate parameters 
	
	Reliability and Safety
		Build trust
	
	Privacy and security
		protect data of citizens
	
	Inclusiveness
		Everyone should benefit from intelligent technology
	
	Transparency
		How were the AI decisions made, impacts on people's lives
	
	Accountability
		People who design and deploy AI must be accountable
		
FUNDAMENTAL PRINCIPLES OF MACHINE LEARNING ON AZURE
	REGRESSION
		Supervised learning, result is numeric
	CLASSIFICATION
		BINARY CLASSIFICATION
		MULTICLASS CLASSIFICATION 
		Supervised learning, assigns odds of cluster
	CLUSTERING
		Unsupervised learning, find groups of related things in data 
	
DEEP LEARING
	Subset of machine learning where neural networks with layers (RNN - Recurrent neural networks)
	
CORE MACHINE LEARNING CONCEPTS
	FEATURES: Input
	LABELS: Output
	TRAIN DATA
	VALIDATION DATA 
	MEAN SQUARE ERROR
	CONFUSION MATRIX
		True Postive, False Negative
		TPR - True Positive rate, sensitivity
		FPR - False positive rate, fallout rate 
		ROC - Receiver Operating Characteristic TPR vs FPR 
		AUC - Area under the curve TPR vs FPR 
		
		Recall - TP/(TP+FN)
		Accuracy - (TP+TN)/Total number of cases.
		Precision - TP/(TP+FP)
		F1 Score- 2TP/(2TP+FP+FN)
		Selectivity  - TN/(TN+FP)
		
		
	NO CODE ML
		Azure Machine Learning 
		AutoML 
 		Azure Machine Learning Designer
			Drag and drop
			Training pipeline converted to production
			
		AZURE ML WORKSPACE
			create workspace
			launch studio
			compute instance to model set new
			compute cluster to train
			Option1: Automated ML 
			Option2: Azure ML Designer -more liberty
			
		COMMON WORKFLOWS AZURE
		COMPUTER VISION
			IMAGE CLASSIFICATION
			OBJECT DETECTION
			SEMANTIC SEGMENTATION
				Boundaries of objects
			OCR
			FACIAL DETECTION AND RECOGNITION
			
			TOOLS
				COMPUTER VISION SERVICE
					Pretrained ML model
					Identify 10^4 objects 
					captions
					detect faces 
				CUSTOM VISION SERVICE
					Build/Train your model
				AZURE COGNITIVE SERVICES
					Umbrella under all services
				FACE SERVICE 
					Recognize human face 
					Can recognize celebrities
					Train on your data 
				AI VIDEO INDEXER
					Deep search: Audio to text, visual to keywords
				
				NLP
					Understanding written and spoken language
					SERVICES 
						key phrase extraction
						Entity Recognition
						Sentiment Analysis - prebuild 
						Language Modeling -Build industry dictionary
						Speech Recognition and Synthesis(speech to text)
						Translation 
						Utterances: Entities (keywords), intents
						Speech Service: Text to speech, speech to text 
						Translator Service 
		
GENERATIVE AI 
	Identify
	Measure
	Mitigate: Metaprompt or grounding data to steer away from offensive 
	Operate: Track telemetry to determine user satisfaction
			
		
　AZURE AI SERVICES 
	Multi-Service resource: Single API for multiple services 
	Single-Service resource: Single Azure Service 
	
COMPUTER VISION 	
	Image encoder: Filter to classify
	text encoder 
	multi modal FLORENCE
	classification 
	object detection
	captioning
	tagging
	AZURE AI SERVICE 
	AZURE AI VISION 
		OCR->page,lines,words API
	AZURE AI VIDEO INDEXER 
	AUZURE AI FACE 
	AZURE AI LANGUAGE 
		NLP
			speech to text 
			Machine translation
			Text classification 
			Entity extraction 
			Text summarization
			question answering
		Language Studio
	AZURE AI BOT SERVICE 
	AZURE AI SPEECH 
	AZURE AI DOCUMENT INTELLIGENCE
	AZURE AI SEARCH 
	
NATURAL LANGUAGE PROCESSING
	Language Understanding 
		Utterances
		Entities
		Intents
		
AZURE AI STUDIO 
	AZURE AI HUB 
		PROJECT
PROMPT FLOW
	LLM LIFECYCLE
		INITIALIZATION
		EXPERIMENTATION
		EVALUATION AND REFINEMENT
		PRODUCTION
		
	FLOW
		inputs
		nodes
		outputs
		
		standard flow
		chat flow
		evaluation flow 
		
	TOOLS
		llm
		python
		prompt tool

METRICS FOR LLM
	accuracy
	coherence
	fluency
	GPT similarity
	groundedness
	relevance
	
CONTEXT OPTIMIZATION
	RAG
MODEL OPTIMIZATION
	FINE TUNE
	
DEALING WITH HARM
	model layers
	safety layer 
	metaprompt layer 
	user experience layer 
	
