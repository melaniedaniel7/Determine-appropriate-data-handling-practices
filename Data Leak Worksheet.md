# Data Leak Worksheet

Disclaimer: This project was created as part of my learning journey through the Google Professional Cybersecurity Certificate offered on Coursera. Some activities and content within this project were provided by the course as part of my coursework. All credit for such content belongs to Google and Coursera, and I acknowledge their role in supporting the completion of this project.

### Incident summary: 
A sales manager shared access to a folder of internal-only documents with their team during a meeting. 
The folder contained files associated with a new product that has not been publicly announced. 
It also included customer analytics and promotional materials. 
After the meeting, the manager did not revoke access to the internal folder, but warned the team to 
wait for approval before sharing the promotional materials with others.

During a video call with a business partner, a member of the sales team forgot the warning from their manager. 
The sales representative intended to share a link to the promotional materials so that the
business partner could circulate the materials to their customers. 
However, the sales representative accidentally shared a link to the internal folder instead. 
Later, the business partner posted the link on their company's social media page assuming that it was the promotional materials.

| Control       | Least privilege       |
| -------------- | -------------- |
| Issue(s)  | The factors that contributed to the information leak was the manager not revoking access to the internal folder after the meeting, a member of the sales team forgetting the warning the manager gave about sharing the promotional materials with other people, and the business partner sharing the  folder based off of assumptions. |
| Review  | NIST SP 800-53: AC-6 addresses data security and Protections against data leaks in relation to the principle of least privilege. NIST SP 800-53 addresses a set of guidelines for securing the privacy of information systems. AC-6 addresses the control that only the minimal access and authorization should be granted to complete a required task or function. |
| Recommendation(s)  | The principle of least privilege might be improved at the company if they: Automatically revoke access to information after a period of time and restrict access to sensitive resources based on user role.  |
| Justification  | These improvements might address the issue because, firstly, even if an employee was granted access to information their access would be revoked after a certain period of time which may have prevented the sales employee from being able to share the folder after they forgot what the manager said. And, secondly, if the company restricts access based on an employees role then they would have not been able to access and share the folder. |

- What factors contributed to the information leak?
- What does NIST SP 800-53: AC-6 address?
- How might the principle of least privilege be improved at the company?
- How might these improvements address the issues?

### Resources

<img src="https://github.com/melaniedaniel7/Determine-appropriate-data-handling-practices/blob/3a40e5cc663e9b1c08573c2a94fc260feb006f9d/Screenshot%202024-10-22%20at%2014.43.13.png" width="600" />

<img src="https://github.com/melaniedaniel7/Determine-appropriate-data-handling-practices/blob/550cafb1ad1112bd60c439269c12c390583a70b6/Screenshot%202024-10-22%20at%2014.43.50.png" width="600" />

### Memo

<img src="https://github.com/melaniedaniel7/Determine-appropriate-data-handling-practices/blob/07f87ece84b65a64e7e205896616477644e76e2c/Screenshot%202024-10-22%20at%2014.42.54.png" width="600" />
