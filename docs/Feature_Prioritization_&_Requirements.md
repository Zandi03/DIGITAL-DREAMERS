# Feature Prioritization & Requirements: Spam SMS Detection

###  Feature Prioritization (High to Low Impact)

| Feature                            | Priority  |
|-----------------------------------|-----------|
| Text input for SMS message        | High      |
| Spam/Not Spam result + confidence | High      |
| File upload for batch detection   | Medium    |
| Explanation of result             | Medium    |
| Clean, responsive UI              | High      |
| About Page                        | Low       |

---

### Functional Requirements

| ID  | Requirement                                                      | Type        |
|-----|------------------------------------------------------------------|-------------|
| FR1 | The system shall accept a text input from the user.             | Functional  |
| FR2 | The system shall return a spam prediction and confidence score. | Functional  |
| FR3 | The system shall allow .txt file uploads for batch messages.    | Functional  |
| FR4 | The system shall display a simple UI with navigation.           | Functional  |
| FR5 | The system shall explain spam rationale (optional).             | Functional  |

---

###  Non-Functional Requirements

| ID   | Requirement                                  | Type           |
|------|----------------------------------------------|----------------|
| NFR1 | System should respond within 2 seconds.      | Performance    |
| NFR2 | System must handle 1000 messages per hour.   | Scalability    |
| NFR3 | UI should be accessible and mobile-friendly. | Usability      |
| NFR4 | Data should not be stored or shared.         | Privacy        |

