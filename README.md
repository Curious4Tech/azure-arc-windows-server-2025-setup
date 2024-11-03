# azure-arc-windows-server-2025-setup
Guide and setup instructions for enabling Azure Arc on Windows Server 2025, including steps to activate monitoring. This repository provides a comprehensive walkthrough for onboarding Windows Server 2025 to Azure Arc, making it manageable directly from the Azure portal with full monitoring capabilities.

 # Enable Azure Arc on Windows Server 2025 and Activate Monitoring

This guide provides step-by-step instructions to enable Azure Arc on Windows Server 2025 and activate monitoring.

## Prerequisites
1. **Windows Server 2025:** Ensure that your server is up to date and meets all the necessary requirements for Azure Arc.
2. **Azure Arc Setup Feature:** The Azure Arc setup feature is included as a Feature on Demand in Windows Server 2025. Make sure it's installed.

## Steps to Enable Azure Arc

### 1. Launch Azure Arc Setup
   - Locate the **Azure Arc** system tray icon on your server.
   - Click on it and select **Launch Azure Arc Setup**.  
   - Alternatively, you can access it through the **Server Manager** or the **Start menu**.

     ![image](https://github.com/user-attachments/assets/38c0b25b-7202-41a2-937d-76b22973fb20)


### 2. Follow the Setup Wizard
   - The setup wizard will guide you through the onboarding process, checking for prerequisites and installing the **Azure Connected Machine agent**.


      ![image](https://github.com/user-attachments/assets/5ce39346-ae7e-4f86-b24b-f5c95c765fed)


   - After installation, configure the agent by providing:
      - **Azure credentials**
      - **Subscription** and **Resource Group** details.


   ![image](https://github.com/user-attachments/assets/744f5529-9a4c-4f59-8eb0-607d8f0e4b77)


### 3. Complete the Onboarding Process
   - After configuration, select **Finish** to complete onboarding.

     ![image](https://github.com/user-attachments/assets/2502e8fe-0be4-44fe-8658-f9d83afe917c)


   - You can verify that your machine is onboarded by checking the **Local Server** tab in **Server Manager**. The status should show as **Enabled**.

      ![image](https://github.com/user-attachments/assets/bdeb7cf7-d894-411f-a876-a327c27a3919)


## Activating Monitoring

Once your server is onboarded to Azure Arc, you can enable monitoring through the Azure portal:
   - Navigate to **Azure Arc** > **Servers** in the Azure portal.
   - Select your server, go to **Insights** or click on **Monitoring Insights**
     
     ![image](https://github.com/user-attachments/assets/b608ccd0-179b-4ad7-b2aa-e36b6cd077cf)

 - And then click on **Enable** to enable monitoring.

    ![image](https://github.com/user-attachments/assets/31df5da9-e8fa-402d-b985-ebbfb9644ec7)

This process will allow you to manage and monitor your Windows Server 2025 directly from the Azure portal using Azure Arc.


![image](https://github.com/user-attachments/assets/8af09261-4e07-415c-b3ad-6134739258f3)


## Additional Resources

- [Azure Arc Documentation](https://docs.microsoft.com/azure/azure-arc/)
- [Windows Server 2025 Prerequisites](https://docs.microsoft.com/azure/azure-arc/windows-server-2025)

---

This README file provides all the necessary steps to enable Azure Arc on Windows Server 2025 and  activate monitoring.
