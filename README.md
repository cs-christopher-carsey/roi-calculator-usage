# FSR ROI Calculator

This solution pack demonstrates the usage of the ROI Calculator widget. Using this widget, you can control how ROI is calculated by using time estimates for playbooks and job-code based cost savings.

This SP includes:
1 widget - "ROI Calculator"
1 dashboard - "ROI Calculator - ENG & HR example"
1 playbook collection with 2 playbooks - "99 - ROI Widget Demo"

To see the ROI numbers populate, run the playbooks in the included collection. Each execution of the "Example ENG playbook" adds 30 minutes to the ENG job code, as defined by the roi-eng-30 tag. Each execution of the "Example HR playbook" adds 20 minutes, as defined by the roi-hr-20 tag.
The dashboards are configured to display the ROI cost savings at $75/hr for the ENG job code and $50/hr for the HR job code.

Below is an example after ~100 executions of the ENG playbook and ~50 executions of the HR playbook.

<img width="1738" alt="Screen Shot 2022-08-09 at 16 22 39" src="https://user-images.githubusercontent.com/20133402/183756833-c9bca196-c060-4b79-99f9-5460c4e172ae.png">

# Why is this useful?
Using this system, you can add tags to your existing playbooks to estimate how much time savings each execution provides for each job code. This gives you precise control over your ROI calculation.


# Additional capabilities
You can add multiple tags to a playbook - e.g. roi, roi-eng-20, roi-hr-15 to represent 20 minutes of ENG time and 15 minutes of HR time.

You can add multiple job codes to a single ROI widget configuration to calculate the total of each job code
