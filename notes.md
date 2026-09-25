Project life - intitation planning executing monitoringncontrolling then close

sys development == execute and monitoring controlling


Waterfall - sysm req soft req analsys program dsign coding testing operations

adv-- disiplince - has start and end -- emphasis on requirments 
dsv-- testing done at the end. stakeholders dont know what they want.

agile exampler - tdd test driven development 

most use scrum for agile -- pm


scrum framework-

product backlog - spriunt planning - splint backock - scrum team daily scrum then sprint review

Pillars of screum

Transparancy - core pillar - give good and bad news - give facts collectively
Inspection- if working iterative improve and get the facts from being transparancy 
Adaptation- continious improvement 


functional requirments -- things we need to do  specfic to sys
non func-- operations and contraints -- timeframe accessabiliy - performance security reliability maitainility usability accesabiliy  legal and compliance

requirment elication-
obsercation
 workshops
 interviews
 docanaluss
 brainstorming
 survey n questionare
 protoyping

user stories- as a "type of user" i want "goal" so that "reason"
-promise of future conversation eg valisation error handling data intergery terms and privacy

business- tester -developer - 3 ppl wfor user stories
product owner end user developer tester secutiyy operations scrum master - maginicent 7

good user story - understandable , follow - ACK -invest independant negotiable valuable estimable small testable

Three C-
    Card
    Conversation
    Confirmation

Acceptance Criteria - interestest subpath and failed logins
product backlog is put in user stories

story points - agile teams estimate effors in varioys forms

mOSCOW /MVP minimum viable product

definions and done n ready--
short checklist
prerequisiters DoR
necessary actions Dod

--------------------------------------------













Ai notes:
Ai is simulation of human inteligence about patterns



Ai then machienge leaning then deep learning then genetive ai

Brain of Ai is making computer as intellingent as humans
3 approaches to ML is decision trees == learn rules
neural networks == learn patterns
statistical models == learn relationships

to train model is by machiene learning - supervised learning - train model and get answers 

unsupervised learning is when models learn without being given correct answers

reinforumced learning is incentised to think correctly

rethink a model == when inaccurate or out of date
 convoualation neural network = best for images use python

cnns can be customised for colour augmentatiosn

-- understanding modern ai=
intro to LLM

Large language models - specilaised neutral network trained on vast dataset
useful for patterns - some syntax are like SQL ,javascreiot or C
LLM spelriased neurtal network trained on vast amount of text dataset to understand and generate text.
LLMs gets data from webs langauge videos code data charts images audio academic reseach news articles books and journals

How LLMs work-

text inputs - tokenisation - embedding - transformer - output

transformer is to comprehend what user wants and what would be the best tokens to put foward as high probabilities.

text = what is cap of france
toekmsation = [w] [s] [c]
embedding = [w] = [0.12,0.34,0.81]
tranformer = compare tokens against the context [capital] = [0.42,-1/17]
    Break early= it doen wg idenity key tokens such as what capital france ?
    middle = recognise factual questions understand capital
    late = paris predomairy reporested in token vectors
output = token paris prob = highest probability = it uses greedy approach which is probabilities

another optimisation is inference paraments
temperature- setting for randomness - deterministsic[greedy] ideal for writing academia
top k sampling nucleus samplig also named top p- both elimate on certain criteria. top k keeps top 20 likely tokens. nucleus sampling looks at most likelt tokens and keeps adding untill cumality probaility

open LLM transaparncy and personlsisation
''''
from openai import Open AI

#chose open ai one
client = Openai()

promt generate slogan

experiate === do priorise experiment
'

high temperature introduces defree of randomness

limitations of Ai- LLMs are largelty reliable but prone to error.

Due to the fact all reponses are built probailistcally.

context window size how much info it can take

model collapse theory -lose their connection to the real world data by feeding on their own ouputs

risk mitigations

hallucinations - double check all the references producted By LLM
BIAS - be mindful
tokenisation limitaions - get the LLM spel out
context window- manga context
model collpase - requets percenrag human generated content


RAG - risk mitigations
Rag is retrieval augmented Generation
knowledge cutoff - stopls learning when training finish
enterprise data -doesnt knoe internak docujents
hallucations - can generate inaccurate responses

another limiation is asking more usuch as word it like count for me
