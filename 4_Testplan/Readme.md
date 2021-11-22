# TEST PLAN:
## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |Invalid Input|  Name:######## Rollno:8888|error|error|Requirement based |
|  H_02       |Check the login details|  Name:Pallavi Rollno:150|0|0|Scenario based    |
|  H_03       |Invalid range of input|  Name:1ab2gc Rollno:17131a|-6|-6|Boundary based    |

## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       |Able to enter details  | Name:Pallavi Rollno:123|0|0|Requirement based |
|  L_02       |Check the results|  Student Result:Pass|Fail if the student gets less marks|Fail if the student get less marks|Scenario based    |
|  L_03       |Insufficient range of marks|marks=90|enter marks less than 90|Enter marks less than 90|Boundary based    |
