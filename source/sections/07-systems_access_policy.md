# 7. System Access Policy

Access to Aluna systems and application is limited for all users, including but not limited to workforce members, volunteers, contracted providers, and consultants. Access by any other entity is allowable only on a minimum necessary basis. All users are responsible for reporting an incident of unauthorized user or access of the organization's information systems.

## 7.1 Access Establishment and Modification

1. Requests for access to Aluna Platform systems and applications is made formally using the following process:
  1. A Aluna workforce member initiates the access request by creating an Issue in the Aluna Quality Management System.
     * User identities must be verified prior to granting access to new accounts.
     * Identity verification must be done in person where possible; for remote employees, identities must be verified over the phone.
     * For new accounts, the method used to verify the user's identity must be recorded on the Issue.
  2. The Security Officer or Privacy Officer will grant access to systems as dictated by the employee's job title. If additional access is required outside of the minimum necessary to perform job functions, the requester must include a description of why the additional access is required as part of the access request.
  3. Once the review is completed, the Security Officer or Privacy Officer approves or rejects the Issue. If the Issue is rejected, it goes back for further review and documentation.
  4. If the review is approved, the Security Officer or Privacy Officer then marks the Issue as Done, adding any pertinent notes required. The Security Officer or Privacy Officer then grants requested access.
     * New accounts will be created with a temporary secure password that meets all requirements from [§7.9](#7.12-password-management), which must be changed on the initial login.
     * All password exchanges must occur over an authenticated channel.
     * For production systems, access grants are accomplished by adding the appropriate user account to the corresponding LDAP group.
     * For non-production systems, access grants are accomplished by leveraging the access control mechanisms built into those systems. Account management for non-production systems may be delegated to a Aluna employee at the discretion of the Security Officer or Privacy Officer .
2. Access is not granted until receipt, review, and approval by the Aluna Security Officer or Privacy Officer ;
3. The request for access is retained for future reference.
4. All access to Aluna systems and services is reviewed and updated on a bi-annual basis to ensure proper authorizations are in place commensurate with job functions. The process for conducting reviews is outlined below:
   1. The Security Officer initiates the review of user access by creating an Issue in the Aluna Quality Management System.
   2. The Security Officer is assigned to review levels of access for each Aluna workforce member.
   3. If user access is found during review that is not in line with the least privilege principle, the process below is used to modify user access and notify the user of access changes. Once those steps are completed, the Issue is then reviewed again.
   4. Once the review is completed, the Security Officer approves or rejects the Issue. If the Issue is rejected, it goes back for further review and documentation.
   5. If the review is approved, the Security Officer then marks the Issue as Done, adding any pertinent notes required.
   6. Review of user access is monitored on a quarterly basis using the Quality Management System reporting to assess compliance with above policy.
5. Any Aluna workforce member can request change of access using the process outlined in [§7.1 paragraph 1](#7.1-access-establishment-and-modification).
6. Access to production systems is controlled using centralized user management and authentication.
7. Temporary accounts are not used unless absolutely necessary for business purposes.
   * Accounts are reviewed every 90 days to ensure temporary accounts are not left unnecessarily.
8. Privileged users must first access systems using standard, unique user accounts before switching to privileged users and performing privileged tasks.
   * For production systems, this is enforced by creating non-privileged user accounts that must invoke `sudo` to perform privileged tasks.
   * Rights for privileged accounts are granted by the Security Officer or Privacy Officer using the process outlined in [§7.2 paragraph 1](#7.2-access-establishment-and-modification).
9. All application to application communication using service accounts is restricted and not permitted unless absolutely needed. Automated tools are used to limit account access across applications and systems.
10. Generic accounts are not allowed on Aluna systems.
11. In cases of increased risk or known attempted unauthorized access, immediate steps are taken by the Security and Privacy Officer to limit access and reduce risk of unauthorized access.

## 7.2 Workforce Clearance

1. The level of security assigned to a user to the organization's information systems is based on the minimum necessary amount of data access required to carry out legitimate job responsibilities assigned to a user's job classification and/or to a user needing access to carry out treatment, payment, or healthcare operations.
2. All access requests are treated on a "least-access principle."
3. Aluna maintains a minimum necessary approach to access to Customer data. As such, Aluna, including all workforce members, does not readily have access to any personal information.

## 7.3 Access Authorization

1. Role based access categories for each Aluna system and application are pre-approved by the Security Officer, or an authorized delegate of the Security Officer.
2. Aluna utilizes firewalls to segment data, prevent unauthorized access, and monitor traffic for denial of service attacks.

## 7.4 Person or Entity Authentication

1. Each workforce member has and uses a unique user ID and password that identifies him/her as the user of the information system.

## 7.5 Unique User Identification

1. Access to the Aluna Platform systems and applications is controlled by requiring unique User Login IDs and passwords for each individual user and developer.
2. Passwords requirements mandate strong password controls (see below).
3. Passwords are not displayed at any time and are not transmitted or stored in plain text.
4. Default accounts on all production systems are disabled.
5. Shared accounts are not allowed within Aluna systems or networks.
6. Automated log-on configurations that store user passwords or bypass password entry are not permitted for use with Aluna workstations or production systems.

## 7.6 Automatic Logoff

1. Users are required to make information systems inaccessible by any other individual when unattended by the users (ex. by using a password protected screen saver or logging off the system).
2. Information systems automatically log users off the systems after 15 minutes of inactivity.
3. The Security Officer pre-approves exceptions to automatic log off requirements.

## 7.7 Employee Workstation Use

1. Workstations may not be used to engage in any activity that is illegal or is in violation of organization's policies.
2. Access may not be used for transmitting, retrieving, or storage of any communications of a discriminatory or harassing nature or materials that are obscene or "X-rated". Harassment of any kind is prohibited. No messages with derogatory or inflammatory remarks about an individual's race, age, disability, religion, national origin, physical attributes, sexual preference, or health condition shall be transmitted or maintained. No abusive, hostile, profane, or offensive language is to be transmitted through organization's system.
3. Information systems/applications also may not be used for any other purpose that is illegal, unethical, or against company policies or contrary to organization's best interests. Messages containing information related to a lawsuit or investigation may not be sent without prior approval.
4. Solicitation of non-company business, or any use of organization's information systems/applications for personal gain is prohibited.
5. Transmitted messages may not contain material that criticizes the organization, its providers, its employees, or others.
6. Users may not misrepresent, obscure, suppress, or replace another user's identity in transmitted or stored messages.

## 7.8 Employee Termination Procedures

1. The Human Resources Department (or other designated department), users, and their supervisors are required to notify the Security Officer upon completion and/or termination of access needs and facilitating completion of the "Termination Checklist".
2. The Human Resources Department, users, and supervisors are required to notify the Security Officer to terminate a user's access rights if there is evidence or reason to believe the following (these incidents are also reported on an incident report and is filed with the Privacy Officer):
   * The user has been using their access rights inappropriately;
   * A user's password has been compromised (a new password may be provided to the user if the user is not identified as the individual compromising the original password);
   * An unauthorized individual is utilizing a user's User Login ID and password (a new password may be provided to the user if the user is not identified as providing the unauthorized individual with the User Login ID and password).
3. The Security Officer will terminate users' access rights immediately upon notification, and will coordinate with the appropriate Aluna employees to terminate access to any non-production systems managed by those employees.
4. The Security Officer audits and may terminate access of users that have not logged into organization's information systems/applications for an extended period of time.



## 7.9 Password Management

1. User IDs and passwords are used to control access to Aluna systems and may not be disclosed to anyone for any reason.
2. Users may not allow anyone, for any reason, to have access to any information system using another user's unique user ID and password.
3. On all production systems and applications in the Aluna environment, password configurations are set to require:
   * a minimum length of 8 characters;
   * a mix of upper case characters, lower case characters, and numbers or special characters;
4. All system and application passwords must be stored and transmitted securely.
   * Where possible, passwords should be stored in a hashed format using a salted cryptographic hash function (SHA-256 or equivalent).
   * Passwords that must be stored in non-hashed format must be encrypted at rest pursuant to the requirements in [§17.8](#17.8-production-data-security).
   * Transmitted passwords must be encrypted in flight pursuant to the requirements in [§17.9](#17.9-transmission-security).
5. Passwords are inactivated immediately upon an employee's termination (refer to the [Employee Termination Procedures in §7.10](#7.10-employee-termination-procedures)).
7. All default system, and application passwords are changed before deployment to production.
8. Upon initial login, users must change any passwords that were automatically generated for them.
9. Password change methods must use a confirmation method to correct for user input errors.
10. All passwords used in configuration scripts are secured and encrypted.
11. If a user believes their user ID has been compromised, they are required to immediately report the incident to the Security Office.
12. In cases where a user has forgotten their password, the following procedure is used to reset the password.
    * The user submits a password reset request to the Security Officer. The request should include the system to which the user has lost access and needs the password reset.
    * An administrator with password reset privileges is notified and connects directly with the user requesting the password reset.
    * The administrator verifies the identity of the user either in-person or through a separate communication channel such as phone or Slack.
    * Once verified, the administrator resets the password.
