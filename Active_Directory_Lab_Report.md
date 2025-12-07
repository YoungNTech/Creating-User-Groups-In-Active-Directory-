# Active Directory Lab Report

## Objective
Perform basic Active Directory (AD) management tasks on a Windows Server: create a user, create a group, and reset a user password.


## Environment
- Windows Server (Domain Controller)
- Tool: Active Directory Users and Computers (ADUC)
- Access: Administrator account via RDP

---

## Steps Performed

1. Create a user
   - Opened Active Directory Users and Computers (ADUC).
   - Navigated to the target Organizational Unit (OU).
   - Right-clicked the OU → New → User.
   - Entered first name, last name, and desired logon name, then completed the creation wizard.

   <img width="760" height="640" alt="Create user screenshot 1" src="https://github.com/user-attachments/assets/892d244b-7517-419d-a1fe-1d1b6725384b" />
   <img width="760" height="640" alt="Create user screenshot 2" src="https://github.com/user-attachments/assets/003dc59e-a3cf-4dc2-b413-98321b916015" />
   <img width="760" height="640" alt="Create user screenshot 3" src="https://github.com/user-attachments/assets/98ee401c-8e98-4717-86e3-08e98eabb568" />
   <img width="760" height="640" alt="Create user screenshot 4" src="https://github.com/user-attachments/assets/d2f67540-3ef9-4617-816e-fe38caed5efd" />

2. Create a group
   - In ADUC, navigated to the desired OU.
   - Right-clicked the OU → New → Group.
   - Provided a group name, selected Group scope (e.g., Global) and Group type (Security), and created the group.

   <img width="760" height="640" alt="Create group screenshot 1" src="https://github.com/user-attachments/assets/fc671c5b-110c-4e5f-a3f4-59b64700a787" />
   <img width="1386" height="1262" alt="Create group screenshot 2" src="https://github.com/user-attachments/assets/1a12f15c-feca-4e2a-8661-e5f3658fe647" />

3. Reset a user password
   - Located the user account in ADUC.
   - Right-clicked the user → Reset Password.
   - Entered and confirmed a new password and optionally checked "User must change password at next logon."

   <img width="760" height="640" alt="Reset password screenshot 1" src="https://github.com/user-attachments/assets/724dc551-ea63-4b4a-8d0c-ca467d596e26" />
   <img width="450" height="400" alt="Reset password screenshot 2" src="https://github.com/user-attachments/assets/8f215754-b435-4376-ad90-d6f145fe59b9" />
   <img width="600" height="550" alt="Reset password screenshot 3" src="https://github.com/user-attachments/assets/29ff743e-6e59-49a1-86dc-5fc9121b9273" />

---

## Outcome
- A new user account was created successfully.
- A new security group was created with the specified scope and type.
- The user's password was reset and configured according to the selected options.


```
