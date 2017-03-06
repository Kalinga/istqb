# QB

# Foundation Level

__1. Fundamentals of Testing [7]__

__2. Testing throughout Software Life cycle [6]__

__3. Static Techniques [3]__

__4. Testing Design Techniques [12]__

__5. Testing management [8]__

__6. Tool support for Testing [4]__

* __Note: Focus Ch. 4, 5, 1, 2__
 
+ K1: remember [20]
+ K2: understand[12]
+ K3: apply[4]
+ K4: analyze[4]

# error, defect, fault, failure,(mistake and bug)

+ [CM Manager/ Developer] error (mistake) [Program Code/ Document]->  defect (fault, bug)
+ defect (fault, bug)-> [Execution] ->Failure [Observed during testing]


    Defects in software, systems or documents may result in failures, but not all defects do so.
    

1. `failure` Something that can be observed during testing.
2. `fault` From the perspective of the configuration adding a wrong version is a
fault, (most probably based on a mistake by the developer / CM manager)
3. `Mistake` The developer misinterpreted: 

+ __Defects occur because:__
  + human beings are fallible 
  + time pressure, 
  + complex code, 
  + complexity of infrastructure, 
  + changing technologies, 
  + many system interactions.

- __Failures can be caused by environmental conditions as well__
  - radiation 
  - magnetism 
  - electronic fields 
  - pollution can cause faults in firmwar

- __Role of Testing in SW Life cycle__
  - reduce the risk of problems occurring during operation
  - quality of the software system
  - meet contractual requirements
  - legal requirements, 
  - industry-specific standards.  


- __Testing Measures__
    - quality of software
        - number of defects found
        - reliability
        - usability,
        - efficiency,
        - maintainability 
        - portability
        - gives confidence in software
        - quality of the software system increases
        - risk of the system will be decreased
        - quality assurance activities

- __quality assurance activities__
    - development standards
    - training 
    - defect analysis
    - testing
    
- __How Much Testing is Enough?__
     
     
     Testing should provide sufficient information to stakeholders to make informed decisions about below points

     
- - level of risk
  - technical
  - safety
  - business risks
  - project constraints such as time and budget     

# 1.2 What is Testing? (K2)

* __These activities__
    - planning and control
    - choosing test conditions
    - designing test cases
    - executing test cases
    - checking results
    - evaluating exit criteria
    - reporting on the testing process
    - reporting on the system under test
    - finalizing or completing closure activities
    - reviewing documents
    - reviewing source code
    - conducting static analysis.
    
* __Testing can have the following objectives:__
    - Finding defects
    - Gaining confidence about the level of quality
    - Providing information for decision-making
    - Preventing defects               
     
* __development testing__
     - component
     - integration
     - system 
     

    as many failures as possible so that defects in the software are identified and can be fixed
    
* __acceptance testing__
    - confirm that the system works as expected
     - to gain confidence that it has met the requirements
     
* __main objective of testing may__
    - be assess the quality of the software
    - with no intention of fixing defects
    - to give information to stakeholders of the risk of releasing the system at a given time
    
* __Maintenance testing__
 - often includes testing that no new defects have been introduced during development of the changes.

* __operational testing__
    - the main objective may be to assess  reliability or availability.     
    
* __Debugging__


    Debugging is the development activity that finds, analyzes and removes the cause of the failure. 

#1.3  Seven Testing Principles
 
 * Principle 1 – Testing shows presence of defects
 * Principle 2 – Exhaustive testing is impossible
 * Principle 3 – Early testing
 * Principle 4 – Defect clustering
 * Principle 5 – Pesticide paradox
 * Principle 6 – Testing is context dependent
 * Principle 7 – Absence-of-errors fallacy
 
# 1.4  Fundamental Test Process
 * 1.4.1 Test Planning and Control 
 * 1.4.2 Test Analysis and Design

    * What is a `test basis`?


        requirements,
        software integrity level1
        risk level,
        risk analysis reports,
        architecture,
        design,
        interface specifications
  
  * 1.4.3 Test Implementation and Execution
  * 1.4.4 Evaluating Exit Criteria and Reporting 
  * 1.4.5 Test Closure Activities
  
  # 1.5 The Psychology of Testing
  # 1.6 Code of Ethics
    
  

  