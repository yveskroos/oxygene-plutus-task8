# Haskell Custom Types and Records Exercises

## Table of Contents

1. [Type Synonyms and Transaction Generation](#type-synonyms-and-transaction-generation)
2. [Custom Types with Multiple Constructors](#custom-types-with-multiple-constructors) 
3. [Shape Type with Area Calculation](#shape-type-with-area-calculation)
4. [Record Syntax for Employee](#record-syntax-for-employee)
5. [Person Record with Employment Status](#person-record-with-employment-status)
6. [Shape with Record Syntax](#shape-with-record-syntax)
7. [Animal Type with Description](#animal-type-with-description)
8. [Type Synonyms for Greeting](#type-synonyms-for-greeting)
9. [Transaction Record Type](#transaction-record-type)
10. [Book Type with Derived Show](#book-type-with-derived-show)

## Type Synonyms and Transaction Generation

Defines type synonyms `Address` (as String) and `Value` (as Int) to improve code clarity. Implements a `generateTx` function that takes sender address, recipient address, and transaction amount, returning a formatted transaction string combining these values.

## Custom Types with Multiple Constructors

Creates a `PaymentMethod` type with three constructors (Cash, Card, Cryptocurrency) and a `Person` type containing name, address (as tuple), and payment method. Demonstrates creating a specific person instance "Bob" who uses cash payments.

## Shape Type with Area Calculation

Defines a `Shape` algebraic data type with `Circle` and `Rectangle` constructors. Implements an `area` function that calculates the area for each shape type, with examples calculating areas for a circle (radius 5) and rectangle (sides 10 and 5).

## Record Syntax for Employee

Demonstrates using record syntax to define an `Employee` type with `name` (String) and `experienceInYears` (Float) fields. Creates an employee instance "Richard" with 7.5 years of experience.

## Person Record with Employment Status

Defines a `Person` record with fields for name (String), age (Int), and employment status (Bool). Shows creating two person instances - one employed ("Alice") and one unemployed ("Bob").

## Shape with Record Syntax

Extends the Shape concept using record syntax with different fields for each constructor. Circles have center coordinates, color, and radius while rectangles have center, color, width and height. Provides examples of both shape types.

## Animal Type with Description

Creates an `Animal` type with `Dog` and `Cat` constructors, each containing a name. Implements a `describeAnimal` function that generates different descriptions for each animal type, with examples for a dog and cat.

## Type Synonyms for Greeting

Uses type synonyms `Name` (String) and `Age` (Int) to make function signatures more readable. Defines a `greet` function that takes name and age to generate a personalized greeting message.

## Transaction Record Type

Defines a complete `Transaction` record type with sender address, recipient address, amount, and transaction ID fields. Includes a `createTransaction` helper function for constructing transaction instances.

## Book Type with Derived Show

Creates a `Book` record type with title, author, and publication year fields. Uses automatic deriving of the `Show` typeclass to enable easy printing of book instances, with an example book demonstrating this functionality.
