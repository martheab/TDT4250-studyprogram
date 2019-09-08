# TDT4250-studyprogram
Repository for exercises in the subject TDT4250 Advanced Software Design

This purpose of this repo is to create a model of a study program so that the user can model different study programs consisting of different specializations and courses. The repo contains four different plugins that contributes in defining the model created. These are the followings: 
* Model
* Edit
* Editor
* Test

In exercise 1 we were to start designing the model, add derived features and some constraints.   
The model can be found in studyprogramsmodel -> model -> studyprograms.ecore  
The derived feature (SemesterCode: getSemesterCode) can be found in studyprogramsmodel -> src -> studyprograms.impl -> SemesterImpl.java.  
The constraint (available_Courses) can be found in studyprogramsmodel -> src -> studyprograms.util -> StudyprogramsValidator.  
