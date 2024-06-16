# Project Title: Random-User-API-Performance-Test


## What is Performance Testing:
Performance Testing is defined as a type of software testing to ensure that software applications will perform well under their expected workload.

It focuses on certain factors of a Software Program such as:
Speed – It Checks whether the response of the application is fast.
Scalability – It determines the maximum user load.
Stability – It checks if the application is stable under varying loads.

## Technology used: Apache JMeter
### characteristics:
- Open source application – Apache JMeter is an openly available free tool & it facilitates users or developers to use the code for other development or modification purpose.
- Platform independent – It can run on any platform & also it is capable enough to check the load & performance of any server requests.
- User friendly GUI – Its user-friendly, simple & easy to understand.
- Installation – It’s easy to install on different OS.
- Record & Run: JMeter provides the facility to record the steps by using Blaze master add-on & run with any number of threads & listeners.

  ## Server Url
  https://demoqa.com/BookStore/v1/Books

  ## Test Method
  
 - I have done performance testing including Load Testing and Stress Testing.

 - Load Testing: This testing is used to check the extreme load of a system that can be aimed to handle.

   I started with 166 requests in 60 seconds and finally I executed with 3333 requests in 1200 seconds. I got almost expected TPS (2.7) for every test iteration.
   
  ### Output(Load Test)
  
   ![Load test scrnsht](https://github.com/Sudipto971/Random-User-API-Performance-Test./assets/132764259/a9d1de9f-149d-4f3f-b397-debdd4759c34)

 - Stress Test: This test tries to break the system by crushing its resources.

    I checked it in 20 Minutes (1200 seconds) considreing 4333, 3700, 3500, 3400 requests. This server successfully run with these requests except 3700 requests in 1200 seconds. It shows an error 0.65% that is called as bottleneck point.
   and we found a little amount of error with 3500 request but found 0% error with 3400 requests in 1200 second so that is our Capasity Value.

   ### Output(Load Test)
   
   ![Stress test screenshot](https://github.com/Sudipto971/Random-User-API-Performance-Test./assets/132764259/c9f603a2-116c-4715-b8f9-8a098ed4f71c)

