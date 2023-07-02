In .NET's dependency injection there are three major lifetimes:  

Singleton which creates a single instance throughout the application.  
It creates the instance for the first time and reuses the same object in the all calls.  

Scoped lifetime services are created once per request within the scope.   
It is equivalent to a singleton in the current scope. For example, in MVC it creates one instance for each HTTP request, but it uses the same instance in the other calls within the same web request.  

Transient lifetime services are created each time they are requested. This lifetime works best for lightweight, stateless services.
