# Outline

- Come up with a new evaluation task
	- Should not be in BIG-Bench or OpenAI Playground Examples
- Should be something that you can fairly easily generate O(100) prompts so that we can get reasonable distribution on accuracy
- You should use the BIG-Bench template and either a simple JSON or programmatic task
- You will need to write code to query the OpenAI GPT-3 models using the python API driven by the BIG-Bench template/code
- You should also fill in the template for description of the task, what is being measured, the motivation, design considerations, etc.
- You should workout with your classmates how to come up with the “human level performance” on the same tasks
Benchmark on text-Davinci-002, text-Curie-001, text-Babbage-001, and text-Ada-001
- Produce plots for different models
- Extra Credit.  Work out how to evaluate other models 

