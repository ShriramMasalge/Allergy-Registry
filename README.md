Allergy Registry Smart Contract
Description
The Allergy Registry is a decentralized smart contract built on the Aptos blockchain that enables users to securely register, store, and manage their allergy information on-chain. This contract provides a transparent and immutable way for individuals to maintain their medical allergy records, making them accessible to healthcare providers, emergency responders, and other authorized parties when needed.
The contract features two primary functions: register_allergy() for adding new allergies to a user's record, and get_user_allergies() for retrieving all registered allergies for a specific user address. Each user's allergy data is stored in a personal AllergyRecord struct that maintains both the list of allergies and a count of total registered allergies. The system automatically creates new records for first-time users and provides efficient query capabilities for existing records.
Vision
Our vision is to revolutionize healthcare data management by creating a decentralized, patient-controlled allergy registry that empowers individuals to own and manage their medical information. We aim to bridge the gap between patients and healthcare providers by ensuring critical allergy information is always accessible, verifiable, and under the patient's control.
By leveraging blockchain technology, we envision a world where:

Patients have complete ownership of their medical allergy data
Healthcare providers can instantly access accurate allergy information during emergencies
Medical records are interoperable across different healthcare systems globally
Privacy and security of sensitive medical information is guaranteed through cryptographic protocols
Healthcare costs are reduced through efficient data sharing and reduced medical errors

Future Scope
The Allergy Registry smart contract serves as a foundation for a comprehensive decentralized healthcare ecosystem. Our roadmap includes:
Short-term Enhancements (3-6 months)

Allergy Severity Levels: Implement severity classifications (mild, moderate, severe, life-threatening)
Allergy Categories: Organize allergies by type (food, environmental, drug, etc.)
Emergency Contact Integration: Link emergency contacts to allergy records
Healthcare Provider Access Controls: Implement permission-based access for medical professionals

Medium-term Developments (6-12 months)

Integration with Healthcare APIs: Connect with existing Electronic Health Record (EHR) systems
Mobile Application: Develop user-friendly mobile apps for easy allergy management
QR Code Generation: Create scannable QR codes for quick emergency access
Multi-language Support: Expand accessibility with international language support
Allergy Testing History: Track and store allergy test results and dates

Long-term Vision (1-3 years)

AI-Powered Allergy Predictions: Implement machine learning for allergy risk assessment
Cross-chain Interoperability: Expand to multiple blockchain networks
Insurance Integration: Connect with insurance providers for coverage verification
Research Data Contribution: Enable anonymous data sharing for medical research
Global Healthcare Network: Build partnerships with international healthcare organizations
IoT Device Integration: Connect with wearable devices and medical monitoring equipment

Contract Address
Devnet: "0xfdfa94d72facecffb1b872af4bec7fae060ebb9e59b6bce7e6cd47b5e55965a0"
Module Name: MyModule::AllergyRegistry
<img width="1877" height="837" alt="image" src="https://github.com/user-attachments/assets/eeca4724-ef41-4922-b950-7bfeb124eec3" />


eracting with the contract.
