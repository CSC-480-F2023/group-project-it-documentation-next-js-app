# Requirements

### User Stories:

1. **As a System Administrator,**
   - I want the ability to reset user passwords and manage account lockouts for security purposes.
   - I want to receive notifications when a user account is created or deactivated.

2. **As an IT Staff Member,**
   - I want to be able to create folders or categories to organize documents within my access scope.
   - I want to have version control for documents, allowing me to revert to previous versions if needed.

3. **As a Manager,**
   - I want the ability to delegate document editing permissions to specific IT Staff members for collaborative projects.
   - I want to set expiration dates for certain documents or document categories.

4. **As a User,**
   - I want the option to export documents in different formats (e.g., PDF) for offline use or sharing.
   - I want to provide feedback or suggestions on documents through a commenting system.

5. **As a Collaborative Group,**
   - We want to have a discussion forum or chat functionality linked to specific documents to facilitate communication among team members.
   - We want the ability to link related documents for easy navigation and reference.

### Formal Requirements:

1. **Authentication and Authorization Enhancements:**
   - The system shall implement account lockout mechanisms after a specified number of unsuccessful login attempts.
   - The system shall provide a secure mechanism for password reset requests.

2. **Document Organization and Version Control:**
   - The system shall support the creation of folders or categories for organizing documents.
   - Document versions shall be stored, allowing users to revert to previous versions as needed.

3. **Delegation and Expiration:**
   - Managers shall have the ability to delegate document editing permissions to specific IT Staff members.
   - The system shall allow managers to set expiration dates for individual documents or entire document categories.

4. **Export and Feedback:**
   - Users shall have the option to export documents in different formats, including PDF.
   - The system shall provide a commenting system for users to provide feedback or suggestions on documents.

5. **Collaborative Features:**
   - The system shall integrate a discussion forum or chat functionality linked to specific documents.
   - Users shall have the ability to create and navigate links between related documents.

### Constraints for the Given Requirements:

1. **Security Constraints:**
   - All authentication and authorization mechanisms must comply with industry-standard security practices.
   - Password reset mechanisms should follow secure protocols and include multi-factor authentication where possible.
   - Account lockout mechanisms must be designed to prevent brute force attacks without causing denial of service for legitimate users.

2. **Document Management Constraints:**
   - The system should adhere to data protection regulations, ensuring that access to documents is restricted based on user roles and permissions.
   - The document organization and version control system must be scalable to handle a potentially large number of documents and versions.

3. **Delegation and Expiration Constraints:**
   - Delegation of document editing permissions must be granular and adhere to the principle of least privilege.
   - Expiration dates for documents should be configurable within reasonable limits and be enforced by the system reliably.

4. **Export and Feedback Constraints:**
   - Document export functionality should consider potential file size constraints and format compatibility.
   - The commenting system should have moderation features to prevent misuse and maintain a professional environment.

5. **Collaborative Features Constraints:**
   - The discussion forum or chat functionality should support real-time communication and be scalable to accommodate multiple users simultaneously.
   - Links between related documents should be maintained even if documents are moved or renamed, ensuring consistency in references.

6. **Compatibility Constraints:**
   - The system should be compatible with common web browsers and devices to ensure a seamless user experience.
   - Exported documents should be compatible with widely used software for the chosen formats.

7. **Performance Constraints:**
   - Document retrieval, version control operations, and collaboration features should be optimized for performance to provide a responsive user experience.
   - The system should handle concurrent user activities, such as editing documents or participating in discussions, without significant performance degradation.

8. **Regulatory Compliance Constraints:**
   - The system must comply with relevant data protection and privacy regulations, ensuring the secure handling of user data and documents.
   - Any data retention policies, especially regarding expired documents, should align with legal and regulatory requirements.

9. **User Training and Adoption Constraints:**
   - The user interface should be intuitive and require minimal training for users to effectively utilize the document management and collaboration features.
   - Changes in permissions and document statuses should be communicated clearly to users through notifications or other means.

10. **System Maintenance Constraints:**
    - Regular maintenance activities, such as backups and updates, should be scheduled to minimize disruptions to users.
    - The system should provide mechanisms for system administrators to monitor user activities and system health for maintenance purposes.

### Categorized Requirements:

#### Functional Requirements:

1. **Authentication and Authorization Enhancements:**
   - Stakeholders: User
2. **Document Organization and Version Control:**
   - Stakeholders: User
3. **Delegation and Expiration:**
   - Stakeholders: User
4. **Export and Feedback:**
   - Stakeholders: User
5. **Collaborative Features:**
   - Stakeholders: User

#### Non-Functional Requirements:

1. **Security Constraints:**
   - Stakeholders: System Administrator (User), Regulator
2. **Document Management Constraints:**
   - Stakeholders: IT Staff Member (User), Regulator
3. **Delegation and Expiration Constraints:**
   - Stakeholders: Manager (User), Regulator
4. **Export and Feedback Constraints:**
   - Stakeholders: User, Regulator
5. **Collaborative Features Constraints:**
   - Stakeholders: Collaborative Group (Users), Regulator
6. **Compatibility Constraints:**
   - Stakeholders: User
7. **Performance Constraints:**
   - Stakeholders: User
8. **Regulatory Compliance Constraints:**
   - Stakeholders: Regulator
9. **User Training and Adoption Constraints:**
   - Stakeholders: User 
10. **System Maintenance Constraints:**
    - Stakeholders: User

#### Additional Stakeholders

1. **IT Department:**
   - Acquirer, User
2. **Documenation App Developers:**
   - Producers, User
3. **University Institution:**
   - Acquirer, User