# ZooAnimals

- [WireFrames](https://whimsical.com/zooanimal-FTf5TcJYR6MESVMpREZvee)

#Acceptance Criteria:
- Add dependencies for Navigation Component, Retrofit, coroutines and viewbinding
- Make sure to add proper MVVM architecture,place all classes in their appropriate folder.
- Connect to the api, making sure to have either an object or list of objects as a return type depending on the Json response.
- Use sealed classes, data classes and objects to create a state representation which will represent the states that each page will be in.
- Make sure all network requests are asynchronous using suspend functions and coroutines to make sensible concurrency.
- Use stateflow instead of LiveData for your Observable implementation, be sure to make up for the lifecycle awareness that LiveData automatically handled.
  -Build an adapter for the recyclerview and make sure that each class is only handling work related to its job. (Use Higher Order functions to pass values.)
  
  