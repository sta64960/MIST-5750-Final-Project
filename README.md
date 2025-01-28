# MIST-5750-Final-Project

# Team Members
T.J. Anderson,

Saahil Bapat,

Saniya Bedi,

Hubah Akhtar,

Elyssa Abbott

# Executive Summary
This report details our analysis of the InsureIT Case Scenario, as well as the deconstruction and redesign of the process. The scenario itself illustrates the progression of handling claims from the initial request to the scheduling of the monthly payments. The analysis consists of the existing process model and calculations to gauge cycle time efficiency. Our team deconstructed the existing process into three distinct subprocesses: enter and screen claim, classify claim and authorize request, and trigger and schedule payments. We depicted both the high level and the subprocesses using a Business Process Model via Signavio.
For deliverable two, the report shows our calculations for actual cycle time, theoretical cycle time, and cycle time efficiency. The theoretical cycle time illustrates an ideal process with no wait times, whereas actual cycle time takes into account possible delays. The actual cycle time was then compared to the theoretical cycle time to determine the cycle time efficiency. These various computations helped us to locate areas for process improvement and bottlenecks for the redesign.
In order to ensure we did not miss an area for improvement within the process, the team utilized other quantitative and qualitative tools. The tools we chose include value-added analysis, waste analysis, issue registers, and why-why diagrams. Value-added analysis shows if the activity provides value to the customer, business, or at all. Waste analysis illustrates the wait times in the process that may be excluded from the cycle time calculations. The issue register highlights issues that may discourage people from this process. Lastly, why-why diagrams help to find the root of the problem. The mix of these tools allows for a full analysis in all possible issues, since cycle time does not take into account every factor.
With the combination of analysis tools, the team has concluded that a redesign is necessary for this process to run smoothly in future transactions. We plan to implement changes in each subprocess. The first change will be an automated system that will perform the initial basic check as the junior claims handler enters the customer’s details. Next, the team would like to move the customer authorization to the start of the process to quickly gather all of the necessary information. We also plan to decrease the time it takes for a claim to be terminated after requesting customer authorization. After the allotted time, the customer will be routed to restart the process to increase urgency. The main theme of these changes are automating the process in order to eliminate manual data entry, as well as decreasing wait times. Our hopes are that this will increase cycle time efficiency and allow activities to happen simultaneously. The team included an additional business process model to illustrate these changes.
In conclusion, using sufficient analysis it is clear that the InsureIT claims handling process is not operating as efficiently as possible. With our redesign approach, wait times will decrease and cycle time efficiency will increase. The process will occur smoothly with less frustration and areas for mistakes to be made.

# As-Is Process Model
<img width="1084" alt="Screenshot 2025-01-28 at 4 06 33 PM" src="https://github.com/user-attachments/assets/955460e3-4bbb-463a-a16a-be73637e0d01" />
Above is the high level diagram depicting the InsureIt claims handling procedure. The process is broken into three main steps: entering and screening the claim, classifying the claim and authorizing the request, and scheduling the payments. The process begins when a claim is received, where it will be screened and accepted or rejected. The claim will then be classified as a short-term or long-term claim, where additional authorizations may be necessary. Lastly, payments will be scheduled and triggered, which concludes the process.

# Enter and Screen Claim
<img width="1081" alt="Screenshot 2025-01-28 at 4 07 04 PM" src="https://github.com/user-attachments/assets/2d47f985-bae4-4dab-99f8-907128d15be1" />
This initial subprocess is the beginning of the procedure to handle a claim. It begins when the claim is received from the customer. The junior claims handler will enter the details of the case and perform a basic check to validate if the claim is covered by insurance. The claim will be accepted 98% of the time and move on to the next step. If the claim is rejected, the process will end and the customer will be notified.

# Classify Claim and Authorize Request 
<img width="1080" alt="Screenshot 2025-01-28 at 4 07 37 PM" src="https://github.com/user-attachments/assets/81ad8edd-22b8-4490-bb4d-8690bafff3be" />
If the claim is covered by insurance, the senior claims handler will evaluate it and determine if it is short-term or long-term. It is long-term 80% of the time and will require customer authorization. The customer has 14 days to authorize before it is terminated and the process ends. Once the junior claims handler has received authorization, they will request necessary medical reports. Both short-term and long-term claims will be assessed before payments are scheduled.

# Trigger and Schedule Payments
<img width="1077" alt="Screenshot 2025-01-28 at 4 08 12 PM" src="https://github.com/user-attachments/assets/b870d91f-e214-4d8d-8421-2d50bc997c1e" />
Once the claim is assessed, the senior claims handler will notify the customer with their decision to accept or reject the claim. If the claim is rejected, the process will end. If the claim is accepted, the Chief Financial Officer will schedule the payments and the process will end, as well.

# Cycle Time Efficiency
<img width="810" alt="Screenshot 2025-01-28 at 4 08 59 PM" src="https://github.com/user-attachments/assets/4c1dd19a-5924-46bd-ad19-495f930cdb59" />
Total TCT = 105.84 minutes
Total Actual Cycle Time = (3 days * 0.20) + (22 days * 0.80) = 18.2 days or 8,736 minutes (8 hour work days)
CTE: 105.84/8,736 = 12.12%

# Process Bottlenecks and Areas for Improvement
Based on the cycle time calculations, we were able to identify some areas where potential bottlenecks could exist. For a more comprehensive look at possible improvement areas, the team combined four different qualitative and quantitative analysis tools. The first tool we implemented was Value Added Analysis. This helped us to determine which steps of the process provided value to the customer or business, and which provided no value. By identifying the non-value adding steps, we could work towards different approaches in the process to ensure value throughout the claims handling procedure. Next, we used Waste Analysis, a counterpart to Value Added Analysis. Identifying areas where time and resources are wasted led us towards our redesign recommendations to eliminate excess waiting times. This allows the process to become more efficient with less wasted resources and more opportunity to improve. The third tool we utilized were Issue Registers. Initially, when we looked at the process, issues were not clear to the team. With the use of cycle time calculations, Value Added Analysis, and Waste Analysis, we were able to identify problems. The Issue Register allowed us to prioritize the issues that needed a solution and determine their impact. Lastly, when designing our to-be process, we often found we could not find the root of the problem. The Why-Why Diagram gave us the ability to pinpoint the cause of the problems. We determined several problems and by continually questioning why the problem was occurring gave us insight into how we can create a more efficient process. The combination of these analysis tools allowed us to see the full picture of the process with its various complications.

# Value Added Analysis
<img width="807" alt="Screenshot 2025-01-28 at 4 09 27 PM" src="https://github.com/user-attachments/assets/2c09354d-4ba2-407c-aa98-b8141ec8b67d" />
The value added analysis explains each step in the process and characterizes it by performer and a classification. The classification has three options: Value-adding (VA), Business value-adding (BVA), or Non value-adding (BVA). During the analysis, it was found that most of the steps performed were Business value-adding. There were a few Non value-adding steps that are important to take note of when discussing a redesign. The Non-value adding steps increase wait time and delay the completion of the process. Therefore, when creating the redesign, NVA steps will be reduced.

# Waste Analysis
<img width="810" alt="Screenshot 2025-01-28 at 4 09 46 PM" src="https://github.com/user-attachments/assets/869b9e1e-8eff-43b4-a7cc-e938f9eba41c" />
Waste analysis, a counterpart to value-added analysis, scrutinizes processes from a negative perspective, seeking inefficiencies throughout. DOWNTIME is an acronym that represents the eight wastes in continuous improvement: Defects, Overproduction, Waiting, Non-Utilized Resources, Transportation, Inventory, Motion, and Excessive Processing. By addressing these sources of waste, organizations can streamline their operations, reduce processing times, and improve overall efficiency in health insurance claims handling. In this project only one category of waste is present. There are three instances of waste and they all fall under the same category of hold, the more specific type of waiting. The first one involves any delays or inefficiencies in obtaining authorization from the customer. This may include waiting for customer responses, approvals, or additional information. The second one focuses on any delays or inefficiencies in requesting medical reports from healthcare providers. This could involve waiting for medical facilities to respond to requests, waiting for reports to be delivered, or waiting for clarification on medical information. The third one involves identifying delays or inefficiencies in the assessment process. This could include waiting for claims adjusters to review and process claims, waiting for additional information or documentation, or waiting for approvals from supervisors or other stakeholders.

# Issue Register
<img width="807" alt="Screenshot 2025-01-28 at 4 10 01 PM" src="https://github.com/user-attachments/assets/c63c6b64-1686-41ec-883e-6de394d753c4" />
<img width="808" alt="Screenshot 2025-01-28 at 4 10 32 PM" src="https://github.com/user-attachments/assets/50b4cd55-9959-4262-80dd-3b2485337414" />
The issue register highlights three priority concerns affecting claim processing efficiency at the organization. The delay in obtaining medical reports from health providers, customers failing to provide authorization within the specified timeframe, and invalid basic checks all pose challenges that can lead to increased processing time, potential backlog of claims, and customer dissatisfaction. Addressing these issues promptly is crucial to maintain operational efficiency, minimize delays, and uphold customer satisfaction. Delay in obtaining medical reports from health providers and customers failing to provide authorization for obtaining medical reports within the specified timeframe are both identified as top priorities (Priority 1 and 2, respectively). These delays lead to customer dissatisfaction, potential backlog of claims, increased processing time, and possible financial penalties for delayed claim processing. Additionally, errors made by customers in providing accurate information, categorized as Priority 3, contribute to increased workload and cause backlog to process further claims. Addressing these issues promptly is crucial to maintain operational efficiency, mitigate delays, and ensure a positive customer experience.

# Why-Why Analysis
<img width="810" alt="Screenshot 2025-01-28 at 4 10 48 PM" src="https://github.com/user-attachments/assets/c382a1a9-6df4-46ec-b98e-7ada44f663e2" />
The Why-Why diagram is meant to diagnose the causes for why certain bottleneck areas may be occurring. It is a way to comprehensively view the underlying causes for, in this case, contributors to delays in insurance processing for long-term claims. Different issues are questioned, and then the reason for their occurrence is further questioned to get a complete overview of why delays appear in the process. Analyzing the factors for why certain delays may be occurring, and why those factors are occurring is helpful in eventually determining potential changes to certain process elements to increase efficiency. This specific diagram breaks down which delays may occur in obtaining medical reports in nested bullet-point form.. Differing reasons for why these delays may occur are highlighted, such as the amount of time it takes for claims handlers to manually request authorization and reports as well as variability of customers and medical providers. Seeing why each factor contributes to delays is crucial in diagnosing potential solutions to increase efficiency. For example, automated request responses would
decrease the delays associated with manually sending requests. Another example of this is looking at the variability in customer responsiveness for receiving claim authorization. Knowing that customers may be waiting till the end of their allotted time to send authorization could lead to shortening the allowed time, instilling more urgency into the customer. Alternatively, improving communication with the customer about the importance of receiving swift authorization could help decrease delays. These potential solutions become more clear after performing a why-why analysis and seeing increasingly specific reasons for delays, which allow for a comprehensive view for why delays may be occurring in the process. The diagram becomes a helpful guide when suggesting different improvements to the process to potentially implement into a to-be diagram.

# Process Redesign Recommendation
To improve the current process, several specific recommendations can be made,
addressing people, process, and technology components. Firstly, it is essential to implement automation and streamline data entry processes to reduce manual errors and expedite claim handling. This aligns with the design principle of "automation" , as it enhances efficiency and reduces reliance on manual input. Implementing a system where junior claims handlers can review data entered by customers rather than manually inputting it themselves will significantly reduce processing time. Additionally, integrating a feature that automatically converts entered data into claim details will further accelerate the process, as it allows for activities to be performed in parallel as opposed to one after another. To address the issue of delayed medical reports, a stricter timeline will be enforced. Customers must submit their medical report authorization within 48 hours of initiating the claim process. If this deadline is not met, the claim process should automatically halt, prompting the customer to resubmit the required documentation. This recommendation aligns with the design principle of "time-based competition," as it emphasizes the importance of timely execution to gain a competitive edge. By putting the authorization request on the front-end of the process, it eliminates the need for customers to return to the process later, which may increase delays. Moreover, restructuring the
process flow by placing the customer authorization form at the beginning will facilitate the swift gathering of essential information, eliminating unnecessary delays. This adjustment adheres to the design principle of "customer focus," as it prioritizes the needs and convenience of the customer throughout the process. Creating the To-Be Process Model based on these recommendations would involve visualizing a streamlined workflow where data entry is automated, customer authorization forms are prioritized at the outset, and strict timelines are enforced for the submission of medical reports. This model would depict a more efficient and customer-centric process, reducing processing times and improving overall satisfaction. In conclusion, the team implemented a transactional redesign approach by tackling problems and resolving them one step at a time. The solutions occur at each part of the process, but the automation using a system transforms the claims handling procedure by optimizing the claims handlers.

# To-Be Process Model
<img width="805" alt="Screenshot 2025-01-28 at 4 26 10 PM" src="https://github.com/user-attachments/assets/e27ad93d-a2c6-4d11-92ba-17462c03611a" />

# Enter and Screen Claim
<img width="804" alt="Screenshot 2025-01-28 at 4 26 49 PM" src="https://github.com/user-attachments/assets/568865b8-6fd3-4857-b62b-705c70157e0f" />

# Classify Claim and Authorize Request
<img width="801" alt="Screenshot 2025-01-28 at 4 27 05 PM" src="https://github.com/user-attachments/assets/f6d310ec-2ca1-4822-92cd-b9201b589405" />

# Trigger and Schedule Payments
<img width="804" alt="Screenshot 2025-01-28 at 4 27 25 PM" src="https://github.com/user-attachments/assets/2346141f-9eb4-4778-b560-9ea6a171cd5b" />
