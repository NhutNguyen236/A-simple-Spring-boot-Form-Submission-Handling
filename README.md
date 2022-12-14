# A simple Handling Form Submission
- In this example, we are about to focus on handling form submission
- In Spring boot there are some points that you need to pay attention to:
  - On the client side (Thymleaf template), `th:object` will be the object template for the form collection 
  - `th:field="*{something_here}"` will be our collected fields then those will be sent to the POST route of the form