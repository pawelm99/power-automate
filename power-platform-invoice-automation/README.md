🌍 Projekt: Invoice Processing Automation (Power Platform)

Opis:
Automation of invoice processing using:

- Power Automate
- Power Apps
- Microsoft Dataverse
- AI Builder

⚙️ What the system does

1. Retrieves an invoice from SharePoint
2. Extracts data using AI Builder
3. Validates data (Expressions)
4. Saves data to Dataverse
5. Sends notifications (Email)
6. Enables editing in Power Apps

🏗️ Architektura
Power Automate → AI Builder → Dataverse → Power Apps

📸 Screenshots
Flow (Power Automate)
![alt text](image-1.png)
![alt text](image-2.png)

💡 Challenges

- mapping nested JSON from AI Builder
- inserting a new contact into the standard customer field. I had to add a custom expression.

🔮 Possible extensions

- Azure Functions (C# fallback)
- CI/CD (ALM)
- ERP integration
