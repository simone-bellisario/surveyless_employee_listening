# surveyless_employee_listening

Example use of a fine-tuned RoBERTa large to classify employee opinions into meaningful topics

The core of this method consists of a RoBERTa large, fine-tuned on a dataset of individual sentences representing employee's opinions on their company (pros and cons). Such dataset had been previously labeled using BERTopic.

This tool is able to identify the following topics: 
	miscellaneous / undefined (outlier sentences)
	culture and values
	occupational wellbeing & work/life balance
	leadership style
	career development and advancement opportunities
	group dynamics
	employer brand
	compensation and benefits
	customer relationships
	workplace perks
	training and development
	workplace location and commute
	structure, processes and tools
	overall employee experience
	performance management and decision-making
	physical work environment and conditions
	communication and meeting culture
	collaboration, team structure and work distribution
	lack of pros
	workplace atmosphere
	employee value and recognition
	workforce planning

 It can also classify whether a sentence is a pro or a con.

 Performance for topic identification during training are Accuracy 0.87 and	F1 0.86; as for the pro vs cons, I got a .95 for both accuracy and F1.

 Before using it, please make sure you download all the needed files and reference them accordingly in the code (in my case, I used google drive).

 This project is licensed under the [CC BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/).  

 Happy listening!




