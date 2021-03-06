# COVID-19 Vaccine Distribution
Group members: [Arthur Gao](https://github.com/arthurgao09), [Anthony Mena](https://github.com/antmena), [Michael Lo](https://github.com/lomichael), [Adrian Carrillo](https://github.com/acarrillo889)

## Why is it important or interesting to you?
    
Arthur's COVID-19 lab involvement brings up the pressing concern of who warrants vaccination before others. We created this Distribution program to determine, based on three factors, who should receive the vaccination.

## What languages/tools/technologies do you plan to use?
* C/C++
* CMake
* googletest

## What will be the input/output of your project?

The input is people who will be vaccinated for COVID-19. The output is the person who's next in line for the vaccine. 

## What are the design patterns you will be using? For each design pattern you must:
* The Composite design pattern will be implemented as a DistributionList class, that aggregates People objects. The DistributionList class will maintain the list data structure that holds the People objects. 

* The Strategy design pattern will be implemented as a class that orders the DistributionList according to the desired characteristic. People will be moved around the list according to age, current condition, or number of vaccinations received. There will be Strategy classes that order the list for vaccination according to the age, current condition, or number of vaccinations received. Effectively, the top person of the list will be the next in line for the vaccine.
