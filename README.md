# React-Lab-Exercise-2-Using-Props-Step-by-Step
# Name: Dakshinamurthy.V
# Roll no: 2305001006
# Department: CSE
# AIM
To create a React application that demonstrates how to pass data from a parent component to a child component using Props.
# PROGRAM
i) App.jsx
import Employee from "./Employee";
function App() {
return (
<div>
<h1>Employee Information</h1>
<Employee
name="Dakshinamurthy.V"
id="101"
department="CSE"
designation="Software Developer"
/>
<Employee
name="Hariharan S"
id="102"
department="IT"
designation="Web Developer"
/>
<Employee
name="Moulishwar G"
id="103"
department="AIDS"
designation="Data Analyst"
/>
</div>
);
}
export default App;
# OUTPUT
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/8af3b182-db3d-4e1d-89c9-e3d963c8a411" />
# RESULT
The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.

