# ZooAnimals

- [WireFrames](https://whimsical.com/zooanimal-FTf5TcJYR6MESVMpREZvee)
- [Project Board](https://www.notion.so/ravebizz/f839b67c52c14e3c847bcebbb82575ea?v=3e58c1f6027b44f5a9f23a8f6b1b79f1ø)

# Acceptance Criteria:

- Add dependencies for Navigation Component, Retrofit, coroutines and viewbinding
- Make sure to add proper MVVM architecture,place all classes in their appropriate folder.
- Connect to the api, making sure to have either an object or list of objects as a return type
  depending on the Json response.
- Use sealed classes, data classes and objects to create a state representation object which will contain
  all the possible data values that each page could hold.
- Make sure all network requests are asynchronous using suspend functions and coroutines to make
  sensible concurrency.
- Use stateflow instead of LiveData for your Observable implementation, be sure to make up for the
  lifecycle awareness that LiveData automatically handled.
- Build an adapter for the recyclerview and make sure that each class is only handling work related to its job. 
  (Use Higher Orderfunctions to pass values.)
  
  
