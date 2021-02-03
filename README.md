# Unit1
Didier Dzib, Fernando Castillo, Miguel Bastarrachea
<br>Investigation.

About algorithms
Being superficial, only using general logic to connect the concepts, we can say that algorithms are involved in every single action in our dairy life, from when we awake in the morning till when we go to sleep; following the definition that is in the dictionary that is correct because those are defined like a systematical group of steps for doing something and that includes what do we often to do. Being more professionals, algorithms are solutions, in other words, these are the defined and analyzed steps for solve problems, for example applied to the industry can be the actions taken for get copper wires, templated glass, encrypted documents, etc. 
Algorithms have some characteristics for being clear and useful; The first is “Algorithms must be accurate” we cannot take the luxury of left steps for “see what happens” all the steps have to be to the point. Next we have “Algorithms must be defined” in other words, every time that we follow an algorithm we have to get the same result, these need to be designed to work in the same way for  a specific problem no matter what. Then we have “Algorithms must be finites” we cannot have infinite sequence of steps, these have to end in a moment for getting the results, having an infinite algorithm is the same that not have a solution. “Algorithms must be legible” this is some obvious but is not much mention that, if we cannot comprehend anyone is the same that we do not have one. Finally, the body of an algorithm is the same every time, we have an entry, process and the end. If your algorithm do not follow all these steps, it must be wrong or the results will not be how you expect.
The graphic representation of algorithms are flowcharts, we can talk about them in a moment but the important here is the flowcharts can show us the algorithm physically, then we can visualize their control structures; these are parameters that allow us to modify the flow of algorithms and depend what do we want to do, could for example: Executing a group of sentences depending a condition in case of the structure If-then-else, executing sentences only when a condition is followed , in the Do-while structure, or even executing a group of sentences in a determined number of times in the For. All of them are classified in selective, repetitive and nested structures, let’s talk about them: First we have the selective structures, we use them for taking logical decisions for example when we want to execute instructions  based on a previous condition; we have four types. Simple, when we evaluate a condition, if it is true it executes one or more instructions, if it is false it continues the normal execution of the program.
Example: Check if a customer's credit is enough to make a new purchase and calculate their new available credit.
If Precio < CreditoDisponible Then
    Cargo = "Aprobado" 
    CreditoDisponible = CreditoDisponible - Precio
End If
The double structure (IF-ELSE-IF) is used for take a decision when we have two options, for example what to do if a condition is followed and what to do if not. See it in the following example:
Example: Know if the user is an adult ot not.
If vEdad >= 21 Then
        MessageBox.Show("Es mayor de edad")
Else

        MessageBox.Show("Es menor de edad")
End If
Multiple selective is used when we have various kinds of sentences to evaluate, it is denotated like “Sleect Case” we have a list of expressions for a case and a group of instructions if the condition given is in the list and with Else we can add another list with their respective onstructions.
Example: Know if a number has one or more digits.
Dim numero, digitos As Integer                                         
Dim myString As String
numero = 53
    If numero < 10 Then
        digitos = 1
    ElseIf numero < 100 Then
         digitos = 2
    Else
         digitos = 3
    End If
    If digitos = 1 Then
         myString = "El número tiene un dígito"
    Else
        myString = "El número tiene mas de un dígito"
    End If

Finally we have the composed selective structure (Elseif) and it works for chain if sentences in the way that a negative if could evaluate another expression. For example.

Example: Here we show the user the month matched to the number given in the input box.
Dim N As Integer
N = InputBox("Ingrese N?")
Select Case N
    Case 1 : MessageBox.Show("Enero")                          
    Case 2 : MessageBox.Show("Febrero")
    Case 3 : MessageBox.Show("Marzo")
    Case 4 : MessageBox.Show("Abril")
    Case 5 : MessageBox.Show("Mayo")
    Case 6 : MessageBox.Show("Junio")
    Case 7 : MessageBox.Show("Julio")
    Case 8 : MessageBox.Show("Agosto")
    Case 9 : MessageBox.Show("Septiembre")
    Case 10: MessageBox.Show("Octubre")
    Case 11: MessageBox.Show("Noviembre")
    Case 12: MessageBox.Show("Diciembre")
    Case Else
        MessageBox.Show("Error de datos")
End Select
The repetitive sentences are used for executing a group of instructions many times according to the logical expression given. These are also known like loops and there are three kinds of them. First, we have the While cycle; it is a repetitive control structure that can prevent the execution of a set of instructions, if the evaluation of the relational and / or logical expression is false. This means that it becomes repetitive only when the condition evaluation is true.

Example: 
while ( condition is true ) 
    do something 
    % Note: the "something" should eventually result 
    % in the condition being false 
  End
The For cycle is known for contain the initialization of variables, as well as the increment or decrement variables, necessary in a cycle. In this cycle the sequence of actions takes place while an initial value reaches a final value.
Example: Print numbers from 1 to 10
// Print numbers from 1 to 10
#include <stdio.h>
int main() {
  int i;
  for (i = 1; i < 11; ++i)
  {
    printf("%d ", i);
  }
  return 0;
}
Finaly we have the Do-While cycle, it is known for execute a set of statements without first performing expression evaluation. In other words in Do-While structures the sequence is executed at least one time despite having a false value.
Example.
class DoWhileLoopExample {
    public static void main(String args[]){
         int i=10;
         do{
              System.out.println(i);
              i--;
         }while(i>1);
    }
}

Sometimes we need to use structures within structures. This is often very useful as a way to organize data structures more efficiently, in that cases we use nested structures.
Example: A nested structure in Go.
type Ciudad struct {
    Nombre    string
    Poblacion int
}

type Pais struct {
    Nombre    string
    Capital   Ciudad
    Idioma    string
    Poblacion int
}
For the representation of each one of the previous structures we can use flowcharts, these are the visual representation of algorithms in the purest state, we can also show the structures of programming algorithms for example, with pseudocode or even directly in the code of any programming lenguaje. 
Variables and constants in algorithms.
Both of them are data with value during the process in the algorithm, values are important information for the process in an algorithm. In the case of variables have to be declared before using it in a sequence but this one can change during the execution; constant values are information as the variables are but these do not change their value because is predefined and, no matter where, have the same value in the process for example some common variables in math are π, e, ϕ etc.
Also, we have classifications in the computational data, basically is the kind of value that are you working, for example: The numeric data is all the information, how the name suggest, with numbers, that includes integer numbers, decimal and constant numbers. The logic information is the kind of parameters used, for example, to compare data. The logic values are discrete variables and only can bring you two possible results, true or false. The strings are groups of symbols that are treated like plane text, depending the program it could includes alphanumeric characters, symbols and punctuation marks. 
These information not only are stored, the algorithm requires information because it is going to work with them; the operations that we can do with the information depends at first time how is our algorithm designed , then what kind of information we need and what kind of information we have. The operations that we can do are for example the arithmetic that is the basic math operator, it works with numbers or even with letters but treated like number variables in order to do math process like additions, subtractions, etc. Then we have the logic operators, as we mentioned previously, this operator can decide between true and false for take a logic decision.
In algorithms we can have all the kinds of information, operators, structures, etc. For solving problems is very important define as clear as possible the specific structure and information in order to avoid problems or fails in the outcoming of your own process.
