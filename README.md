# Data Filtering Program - ReadMe
## Overview
Welcome to the Data Filtering Program! This application reads data from an external JSON file, performs various filtering operations using LINQ queries and Lambda statements, and outputs the results to the console. The JSON file contains location information for properties in Manhattan.

## Program Specifications
Input File
The program uses the data.json file, located in the solution root folder, as the input data source.

## Questions and Answers
The program answers the following questions, each building on the previous one:

Output all of the neighborhoods in the data list.
Filter out all the neighborhoods that do not have any names.
Remove the duplicates from the list of neighborhoods.
Rewrite the queries from the previous questions and consolidate them into one single query.
Rewrite at least one of the questions using the opposing LINQ method (e.g., LINQ query statement to LINQ method calls or vice versa).
## Dependencies
The program uses the Newtonsoft.Json NuGet package (Newtonsoft.Json) to handle JSON serialization and deserialization.

## Implementation
The program reads the JSON file using JsonConvert.DeserializeObject to deserialize the data into appropriate classes. It then uses LINQ queries and Lambda statements to perform the filtering operations on the data.

## Usage
Ensure you have installed the Newtonsoft.Json NuGet package in your C# project.
Place the data.json file in the solution root folder.
Run the program in a compatible C# development environment (e.g., Visual Studio).
The program will process the data and output the answers to the console.
