# AlgoritmCYK
Scope


This application allows you to create a grammar that it's in CNF (Chomsky Normal Form) and from it check if a given string input it's generated from it using CYK algorithm.


Instructions

1. Clone this repository into your eclipse work-space.</b>

2. Import this repository into your eclipse IDE.

3. Run program from main

4. Once it is open, the GUI will be shown with the following elements: 

![image](https://user-images.githubusercontent.com/81060348/142103368-7b530ace-b59e-4afb-92fa-74fb91785c1f.png)
![image](https://user-images.githubusercontent.com/81060348/142103558-a5fd2fa8-7721-4ace-b1ef-631d9790b00d.png)

On screen you can see different tabs. The "Grammar" tab presents an interactive form where it is listed all necessary fields to create the grammar and add its production rules. The "CYK resume" tab presents the result of applying the CYK algorithm with an input string and the grammar it was created previously on the "Grammar" tab.

When you decide it is time to close the application you must click the "door out" icon.

5. Let's start by entering the main information for the grammar:

![image](https://user-images.githubusercontent.com/81060348/142106000-ddd4d8d2-6f69-4578-b63e-bff7f08f03a1.png)
![image](https://user-images.githubusercontent.com/81060348/142107371-1b918e88-9da8-40de-a61a-113cd6b7853b.png)
![image](https://user-images.githubusercontent.com/81060348/142107888-4747335d-e372-4d31-b97c-fc8d2caee91c.png)

In the first section, you must need to enter the following:

​ The input string (a non empty string to be checked from the grammar and that it's required for the CYK algorithm) If you want to check the lambda symbol you must type "lambda".

​ The initial symbol (this specifies which is the first symbol that starts the production rules for the grammar. It's usually "S")

​ The set of terminals (this specifies which elements made up part of the terminals set for the grammar, separate each terminal by "," the program will do the rest. Remember "lambda" can be a terminal).

​ The set of symbols (this specified which elements made up part of the symbols set for the grammar, separate each symbol by "," the program will do the rest) Remember 'S' is also part of the symbols set.

If everything is right you can click on the button "add" to start adding the production rules. Once added you cannot overwrite the information you entered, be careful!

6. To add production rules:

![image](https://user-images.githubusercontent.com/81060348/142108671-dfcae0c9-6409-4cc6-a225-71f0f3d9a563.png)
![image](https://user-images.githubusercontent.com/81060348/142108959-abef2f45-97d1-420a-ab53-83dbc1cc71d1.png)
![image](https://user-images.githubusercontent.com/81060348/142109411-d8b1cdc5-d399-4cb5-be66-f394286049e6.png)

In the second section, you must need to enter the head of the particular production you're adding, then in the body section you need to specify each body of the different productions rules. Look at the example above. You can add as much productions rules as the grammar contains,Once you have entered all your production rules you can now run the CYK algorithm.

7. To start the CYK algorithm:

![image](https://user-images.githubusercontent.com/81060348/142113187-067bfeca-d5b4-49e4-ad9b-66ecd598a77d.png)
![image](https://user-images.githubusercontent.com/81060348/142113908-6a08014e-ec58-449d-8854-0a1bbddb7a07.png)
To run the CYK algorithm, you just need to press the button "Start CYK decision algorithm" once done, on the CYK resume tab you will see the results of the execution.

8. To start with a new Grammar:
![image](https://user-images.githubusercontent.com/81060348/142114290-91c770dc-6ca6-476c-a630-783800cf91ce.png)

Once you have created your grammar and added its production rules, you can choose if you want to add a new grammar, once you have run the algorithm over the data you entered the form is restablished again, so you can enter new information.

