# **Human Resource Management**

| [Employee](#employee) | [On Board](#on-board) | [Leave Management](#leave-management) | [Travel](#travel) | [Employee Retirement](#employee-retirement) | [Loan](#loan) | [Reissue](#reissue) | [Renewal](#renewal) | [Clearance](#clearance) |

<br>

# **[Employee Retirement](#human-resource-management)**

| [Retirement Request](#retirement-request) | [Final Settlement](#final-settlement) |


<br>


> ## **[Retirement Request:](#employee-retirement)**

The Retirement request is initiated from case and task management for EMployee.

| [New Request](#new-request) > [Arco Approval](#arco-approval) > [Customer Approval](#customer-approval) > [Under Processing](#under-processing) > [Customer Clearance](#customer-clearance) > [Arco Clearance](#arco-clearance) > [Waiting for Travel](#waiting-for-travel) > [RejectedRequest](#rejectedrequest) > [Complete](#complete) |

<br>

- ### **New Request:**

    - Initiated request is received from Case and task management for retirement is waiting for process.

      - *In The action field is following to,*

        **1-[Complete](#arco-approval)** - User Complete the Request and refer to [Arco Approval](#arco-approval) stage.


- ### **Arco Approval:**

    - Waiting for get ARCO approval for Employee retirement. once Arco Approval is completed then request to Customer Approval.


       - *In The action field is following to,*

         **1-[Complete](#customer-approval)** - User Complete the Request in this Arco Approval stage and then refer to [Customer Approval](#customer-approval) Stage.

         **2-[Reject](#rejectedrequest)** - User Reject the request and moved to [Rejected Request](#rejectedrequest) stage.

- ### **Customer Approval:**


    - In this stage, Waiting for Customer Approval to process Employee Retirement. Once the Customer Approved then moved to under processing.


      - *In The action field is following to,*

        **1-[Reject](#rejectedrequest)** - User Reject complete the request and refer to [RejectedRequest](#rejectedrequest) stage.

        **2-[Complete](#under-processing)** - User Complete the request and refer to [Under Processing](#under-processing) Stage.

- ### **Under Processing:**

    - In this stage, Employee Final Settlement process will start for employee.
    
    - If the employee request  Travel Arrangements and Visa request from ARCO, and then Travel and Visa process will start for the employee from this stage.

    - If the Employee not requested  Travel Arrangements and Visa from ARCO, then it will move directly to Waiting for travel.


       - *In The action field is following to,*

         **1-[Reject](#rejectedrequest)** - User reject the request and moved to [RejectedRequest](#rejectedrequest) stage.

         **2-[Complete](#customer-clearance)** - User complete the requsest and then refer to [Customer Clearance](#customer-clearance) stage.



- ### **Customer Clearance:**

     - Waiting for Customer Clerance, once clearance is completed by Customer then it will send for ARCO Clearance.


       - *In The action field is following to,*

         **1-[Complete](#arco-clearance)** - User complete and refer the request to [Arco Clearance](#arco-clearance) stage.

         **2-[Reject](#rejectedrequest)** - User Reject the request to [RejectedRequest](#rejectedrequest) stage.

- ### **Arco Clearance:**

  - Waiting For ARCO clearance for Customer, once the ARCO clearance is completed then it will send for Waiting for travel.

       - *In the Action field is Following to,*

          **1-[Complete](#waiting-for-travel)** -  User complete the request and refer to [Waiting for Travel](#waiting-for-travel) stage.

          **2-[Reject](#rejectedrequest)** - User reject and complete the request to [Rejected request](#rejectedrequest) stage.

- ### **Waiting for Travel:**

    - In this stage, the Employee waiting to receive and update on information of travel date, Departure and Airline details. and then user complete the stage, since the employee have properly departured.

    - Sent to travel
      - *In the Action field is Following to,*

        **1-[Complete](#complete)** - User complete the request and then refer to [Complete](#complete) stage.

        **2-[Reject](#rejectedrequest)** - User Reject and complete the request then moved to [Rejected Request](#rejectedrequest) stage.

- ### **RejectedRequest:**

    - In this stage, All rejected request is reject and compete the stage.

       - *In the Action field is Following to,*

          **1-Reject** - reject the request and Complete this stage.

- ### **Complete:**

     - Completed request are received in this stage. and use to track the status of the request.

| [Home](#human-resource-management) | [Main](#employee-retirement) | [Back](#retirement-request) |

<br>

> ## **[Final Settlement](#employee-retirement):**


User initiate the request for **Settlement** in **Employee Retirement** process from case and task management.

| [Requested](#requested)  > [Clearance Process](#clearance-process) > [Approval](#approval) > [Client _ Confirmation](#client_confirmation) > [Payment](#payment) > [Client Rejection](#client-rejection) > [Complete](#complete-1) |

<br>

- ### **Requested:**

     - Waiting to process the initiated request is received from Case and task management for Final settlement.

        - *In The action field is following to,*

           **1-[Move to Clearance](#clearance-process)** - User complete the request and *refer for [Clearance process](#clearance-process) stage.

- ### **Clearance Process:**

  - Waiting for the Clearance on Final Settlement for Employee,
     Once clearnce is completed then it will move to Approval stage.

      - *In The action field is following to,*

          **1-[Complete](#approval)** - User complete the request and refer to [Approval](#approval) stage. for **Final Settlement** Clearance.

- ### **Approval:**

     -  Waiting for Finance Approval from Finanace Department for **Final Settlement** to Employee. after Finance Department approved, then user complete the request.

     - If do not have any Final Settlement payment for Employee, then the request complete with **Move without Payment**.

        - *In The action field is following to,*

          **1-[Complete](#client_confirmation)** - Complete this request and moved For [Client_Confirmation](#client_confirmation) stage.

           **2-[Re Calculate Clearance](#clearance-process)** - User reject and return the request [Clearance Process](#clearance-process) stage. for Re Calculate Clearance amount.

           **3-[Move Without Payment](#complete-1)** - User complete this request and **Move Without Payment** to [Complete](#complete-1) Stage.

- ### **Client_Confirmation:**

    - Waiting to get **Client Confirmation** for process the Settlement **Payment** to Employee.

    - Once the confirmation is complete then it will move to Payment stage.

       - *In The action field is following to,*

         **1-[Confirm](#payment)** - User Complete the request and refer to the [Payment](#payment) stage.

         **2-[Move to Clearance](#clearance-process)** - User complete and refer the request to [Clearance Process](#clearance-process) stage. for Recalculate the clearance.

- ### **Payment:**

    - Payment request will process in Finance Department, Once the Payment is completed in Finance Portal, then request is complete and moved to completed stage.


      - *In The action field is following to,*

        **1-[Complete](#complete-1)** -  complete the request and moved to [Complete](#complete-1) stage.

        **2-[ReCalculate](#clearance-process)** - User reject and return the request to [Clearance Process](#clearance-process) stage. for Recalculate the Clearance.

- ### **Client Rejection:**

    - The Request Rejected by Client is received in this stage and waiting to resend for customer confirmation.

      - *In The action field is following to,*

        **[Resend Customer Confirmation](#client_confirmation)** - User Resend the Request to Customer for [Client confirmation](#client_confirmation) stage.

- ### **Complete:**

     - All completed Request has to moved in **Complete** Stage, After the Final Settltment process is completed. for use and track the request status.

| [Home](#human-resource-management) | [Main](#employee-retirement) | [Back](#final-settlement) |
