<h1>Path Parameters </h1>

![[Pasted image 20220101163843.png]]

<h3>Type Validation of the parameter:</h3>

![[Pasted image 20220101164235.png]]

- FastAPI uses `Pydantic` to validate the conversion types of the parameters we pass at the backend.
- So to solve the problem of getting errors on same paths & validations we need **Order/ Arrange** the functions accordingly.


<h3>Predefined Values</h3>

![[Pasted image 20220101165346.png]]

- We can define the set of predefined values by making a "Enum" class , defining the values for the varaibles & Pass them to the paramters for validation.


<h3> Query parameters </h3>

![[Pasted image 20220101170023.png]]

- Any parameters which are not in the part of PATH are known as query parameters.
- we can also define the default values for the Query parameters by directly assigning them into the function parameters.
- **Optional Query parameters**
- ![[Pasted image 20220101170709.png]]



