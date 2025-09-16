# Gas Station CRM 🚀

## Overview
The **Gas Station CRM** is a Salesforce-based application designed to streamline and automate daily operations at gas filling stations.  
It replaces manual registers and inconsistent service tracking with a **centralized CRM platform**.  

Key features include:
- Customer registration & management
- Automated fuel booking & approvals
- Payment & receipt tracking
- Real-time fuel stock monitoring
- Reports & dashboards for analysis

---

## Objectives
- Simplify and digitize daily operations at gas filling stations  
- Improve customer handling and service quality  
- Automate booking, billing, and approvals  
- Enable real-time monitoring of fuel usage and inventory  
- Provide data-driven insights through dashboards and reports  

---

## Features
- **Custom Objects**: Customer, Booking, Fuel Request, Payment, Supplier, Gas Station, Buyer, Fuel Details  
- **Automation**: Flows, Approval Processes, and Apex Triggers  
- **Security Model**: Roles, Profiles, Permission Sets, and OWD  
- **UI/UX**: Lightning App, Dynamic Forms, Page Layouts, LWC (for fuel tracking)  
- **Reports & Dashboards**: Daily bookings, stock analysis, customer frequency  
- **Data Migration**: Using Data Import Wizard, Data Loader  
- **Testing**: Apex test classes with >95% coverage  

---

## Tech Stack
- **Platform**: Salesforce CRM  
- **Development**: Apex, Lightning Web Components, Flows  
- **Deployment**: Sandbox → Production via Change Sets  
- **Data Tools**: Data Import Wizard, Data Loader  

---

## Setup Instructions
1. **Create a Salesforce Developer Org**  
   - [Signup here](https://www.salesforce.com/developer-signup)  
   - Activate your account via email  

2. **Deploy the Application**  
   - Import custom objects: Customer, Gas Station, Fuel Details, Buyer, Supplier  
   - Create junction objects & relationships (Fuel Details ↔ Supplier, Fuel Details ↔ Gas Station)  
   - Configure profiles, roles, and permission sets  

3. **Customize the UI**  
   - Build Lightning App: *Gas Station CRM*  
   - Add Tabs: Supplier, Buyer, Fuel Details, Gas Station  
   - Configure Page Layouts and Dynamic Forms  

4. **Enable Security & Sharing**  
   - Setup OWD: Gas Station & Supplier → Public Read-Only  
   - Configure role hierarchy (Manager → Sales Executive → Sales Person)  

5. **Test & Validate**  
   - Run Apex test classes (ensure >95% coverage)  
   - Validate flows, approval processes, and triggers  

---

## Demo Video 🎥
Watch the project demo here:  
👉 [Click to Watch Demo](https://drive.google.com/file/d/1DbmxohugWIsjmjuiq9NZmyKCwsFywTRN/view?usp=sharing)

---

## Future Enhancements
- Integration with WhatsApp alerts for bookings  
- AI-based fuel usage predictions  
- Mobile app integration for on-the-go tracking  

