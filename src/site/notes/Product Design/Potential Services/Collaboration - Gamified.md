---
{"dg-publish":true,"permalink":"/product-design/potential-services/collaboration-gamified/"}
---

This one is very similar to the [[Product Design/Potential Services/Collaboration\|Collaboration]] service, but this time I led my imagination flow a bit more. It could be a great tool for decentralized companies, where almost random people could subscribe to a task, where their contributions are partly awarded automatically by the system and partly by other contributors. In theory, it could work not only exclusively for software development.

### MVP

- possibility to make tasks, which can consist of subtasks (TMO ontology)
- possible parts:
	- bool: backend or frontend (functional and user test)
	- functionality conditions
		- backend/frontend functional: input-output mapping (unit tests)
			- generate RDF by chat^^ 
		- frontend user test: some questionnaire? 
	- var: finished/unfinished/under review/etc
	- submission date
	- last edited date
	- dates for all state changes 
	- backlog-item (containing state-changes)
	- project defined labels
- a user should be able to assume a task, and submit a task submission
	- reference to task
	- contents
	- state (finished, only after successful test)
	- backlog
	- user defined labels

If all subtasks are successfully finished, then the super task can be tested too

If a original task is set to deprecated, then developers working on it should get a notification - or maybe also when there is discussion on the whole part.

### Risks

- **A lot of redundancy, not very efficient with manpower**
    - Possible solution: Only forward an idea to the next round if it's deemed sufficiently promising (who decides that?)
        
- **Fragmentation without a concrete end result**
    - Possible solution: An expert panel could be helpful here.
        
- **Too much focus on a single proposed but popular solution, due to lack of manpower**
    - Possible solution: Involve critics as a fixed part of the process. If they have serious objections, they could call for an alternative; these could be, for example, hackers.
        
- **People become demotivated if their solution isn’t eventually chosen**
    - Possible solution: Following a gamification and "all contributions are valuable" philosophy, always give some kind of reward.
        
- **People feel it's too reductionist of an approach**
    - Possible solution: I think people should be able to decide when code should be addressed. This can be proposed by a user by establishing the input-output mapping.
        

### Additional ideas:

- People should be able to vote on which areas need improvement.
    - Experts would get a separate status.
    - This should focus on different types of improvements (list from Chat):
        - Functionality
        - Security
        - Efficiency (scalability)
        - Architectural integrity
        - Maintainability
        - Observability (check for errors, etc.)
        - Portability/compatibility
        - Reliability
        - Testability
        - Compliance (legal/ethical)
        - Documentation
        - External impact
            
- What else is needed: A similar setup for interpreting the code.
    - This is necessary when discussing the impact on communities.
        
- Sometimes, you'd want to have a round for code improvement or even just migrate everything to a different (more specific) form (cleaning up).


#service