# Client Security Hash Calculation Process

The process of calculating Client Security Hash involves a systematic sequence of steps aimed at automating the generation of security hashes for client data within the ACME System 1 environment. Below is a detailed outline of each step involved:

1. **Open the ACME System 1 Web Application:** Access the interface of the System 1 Web Application to initiate the process.

2. **Log in to System 1:** Provide the required login credentials (email and password) to gain access to the dashboard.

3. **Access the Dashboard:** Navigate to the central location where specific menu items can be selected, serving as the starting point for the process.

4. **Access the Work Items listing:** View all available tasks to be performed, including tasks related to retrieving Client Information Details.

5. **For each activity of the WI5 type:**
   - a. **Retrieve Client Information Details:** Open the Details page of the selected activity to retrieve necessary client data.
   - b. **Generate Client Security Hash:** Utilize the SHA1 Online webpage to input [ClientID]-[ClientName]-[ClientCountry] and generate the corresponding Client Security Hash.
   - c. **Retrieve Security Hash:** Obtain the generated Client Security Hash value from the webpage.
   - d. **Update Work Item Status:** Return to Work Item Details and open Update Work Item, setting the status to "Completed."
   - e. **Add Comment:** Include a comment containing the obtained Security Hash for reference.

6. **Continue with the next WI5 Activity:** Proceed with the automation process by moving on to the next WI5 Activity as part of the workflow.

These steps provide a clear and structured guide for efficiently executing the Client Security Hash calculation process within the specified automation framework.
