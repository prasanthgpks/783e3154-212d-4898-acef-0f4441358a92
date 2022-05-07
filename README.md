# About

The aim of this .Net project is to 
1. Create C# functions to calculate the first result of possible longest increasing subsequences of a given input
2. Create unit tests to test the possible scenarios and test cases
3. Use containerisation to run these tests inside a container and output the results
4. Build a CI pipeline to execute all the tests
 
# Getting Started

### Pre-Requisites

1. Make sure Docker is installed in your workstation. If not follow the instructions to install [Docker](http://docker.com)

2. Execute the following commands in command prompt with elevated permissions
   - `git clone https://github.com/prasanthgpks/783e3154-212d-4898-acef-0f4441358a92.git`
   - `cd 783e3154-212d-4898-acef-0f4441358a92`
   - `docker-compose -f docker-compose.yml run --rm unittests`
      
   This will run all the tests found in the unit test and display results in the console
   
   [![Console-Results.jpg](https://i.postimg.cc/63wtnHCh/Console-Results.jpg)](https://postimg.cc/d7WbKjH7)
   
3. A CI pipeline is also created through Git Hub actions workflow file. The actions trigger a CI build and perform some checks when ever there is a Push or pull request    to the master/main branch


