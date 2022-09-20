# Index of the study

1. Abstract
2. Introduction (what is serverless, microservicios)
	introduction what is serverless and microservicios
	wether the initial state is a monolith maybe
	
3. Background and motivations (advantages and adoption of serverless -> migrate legacy software trouble -> serverless)
	3.1 Advantages and adoption of serverless (it does not fit for all use cases)
	3.2 Migrate legacy software trouble
	3.3 Cloud provider options, why AWS and consecuences of choose one or other...
	
4. Related work (from microservices to Fargate -> to AWS lambda)
	Showcase and relate the made experiments
	iterative{
		partir de un caso sencillo demostrando que aun siendo sencillo hay dificultades
		pasarlo a fargate
		pasarlo a AWS lambda
		probar performance y analisis de costes
		añadir complejidad (persistencia, interaccion entre los servicios, comunicacion asincrona ...) y repetir
	}
	
5. Observations obtained during the process (cuestiones mas criticas / dolores de cabeza / consejos / guidelines / decisiones tomadas)
	- Facing initial obstacles (program language, too large services, ...)
	- Where to start (reachitecting, too large services, local storage of code, ... )
	- Critical concerns (state management, comunication, quality attributes, ...)
	- Persistence layer
	- Logs, monitoring, performance ...
	- Tools in different stages of the migration
	- Maintainability and technical debt
	- Changes in the development team
	- Data and security
	- Miscelaneous
	
6. Benefits and drawbacks of the migration (performance , costs, serverless advantages, serverless drawbacks)
7. Future directions / Conclusion
8. Acknowledgements
9. References
