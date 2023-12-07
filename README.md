# ENG1585 Final Project - Index Tracking with Sparse Portfolio

## Group:

 - Luisa Compasso
 - Gabriel Alcouffe
 - Matheus Nogueira

## Professor:
 - Davi Valladão

## Description
Final project for the discipline ENG1585 - Intergated Project in Finance and Risk Analysis from PUC-Rio.

Ih this project, we implemented an optimization model in order to track the daily returns of the CAC40 index. The model is a mixed integer programming model, so that it creates a sparse portfolio to select only a few stocks necessary to track the index returns.

It also takes into account transaction costs both as a penalization term inside the model's objective function and as a transaction fee into the portfolio wealth.

This project was implemented entirely in Julia, using it's optimization framework JuMP.
