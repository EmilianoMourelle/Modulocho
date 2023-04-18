# Modulocho
Ejercicio del modulo 8 para yo programo. Primer Master class
Luego de seguir los pasos de la masterclass, inicié la app pero falla la iniciacion. hay algún problema en el archivo de personaService, en le "repoServ"

Error starting ApplicationContext. To display the condition evaluation report re-run your application with 'debug' enabled.
2023-04-18T11:01:02.073-03:00 ERROR 14768 --- [  restartedMain] o.s.b.d.LoggingFailureAnalysisReporter   : 

***************************
APPLICATION FAILED TO START
***************************

Description:

Field persoServ in com.modulocho.modulocho.controller.Controller required a bean of type 'service.IPersonaService' that could not be found.

The injection point has the following annotations:
	- @org.springframework.beans.factory.annotation.Autowired(required=true)


Action:

Consider defining a bean of type 'service.IPersonaService' in your configuration.
