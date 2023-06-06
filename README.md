# AirflowAssignment

Ques 1. Create a dag with following tasks:<br />
$~~~~~~~~~~~~~~~~~$ a. Task to create a simple table <br />
$~~~~~~~~~~~~~~~~~$ b. Task to insert few custom values in to the created table in previous step. <br />
$~~~~~~~~~~~~~~~~~$ c. Task to select the values from the table <br />

#### dag graph for database_processing

<img width="549" alt="Screenshot 2023-04-28 at 11 58 41 AM" src="https://user-images.githubusercontent.com/123542137/235075598-26dc5275-f0e3-430a-9ae2-9bd76dd33649.png">

#### selecting values from table

<img width="511" alt="Screenshot 2023-06-06 at 6 06 39 PM" src="https://github.com/Rajkeshav12/Airflow_assignment/assets/123532501/5ab05778-77c5-4d5c-9dee-267f4681cf16">


Ques 2. Create a dag with following tasks: <br />

$~~~~~~~~~~~~~~~~~$ a. A dummy task which always succeeds <br />
$~~~~~~~~~~~~~~~~~$ Upon successful completion of the task your setup of airflow environment should be
such that it sends an email alert to your <br />  $~~~~~~~~~~~~~~~~~$  sigmoid mail id. Schedule the dag to run daily.

#### dag graph for email_processing!

<img width="1143" alt="Screenshot 2023-06-06 at 6 10 05 PM" src="https://github.com/Rajkeshav12/Airflow_assignment/assets/123532501/ac58d20e-02ce-4858-ab94-f5feb5b5f574">


#### email alert on my email id


<img width="788" alt="Screenshot 2023-06-06 at 6 13 01 PM" src="https://github.com/Rajkeshav12/Airflow_assignment/assets/123532501/dfd14e71-fc5c-4dde-82a6-784c8e11107f">


Ques 3. Create a dag with following tasks: <br/>
$~~~~~~~~~~~~~~~~~$ a. A dummy task which can succeed/fail.<br/>
$~~~~~~~~~~~~~~~~~$ b. Upon success/failure send an alert message to slack workspace


#### dag graph for slack_processing


<img width="1136" alt="Screenshot 2023-06-06 at 6 14 10 PM" src="https://github.com/Rajkeshav12/Airflow_assignment/assets/123532501/e0f9ae95-3b2b-48f4-83a3-514a8cb78190">


#### alert message on slack


<img width="827" alt="Screenshot 2023-06-06 at 6 15 32 PM" src="https://github.com/Rajkeshav12/Airflow_assignment/assets/123532501/3aa19b80-0fdc-4a0d-9fa4-b1734401c6f0">

