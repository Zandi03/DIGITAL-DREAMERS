# System Decomposition 

## Modules 
- User Management
- SMS Upload and Parsing
- Spam Detection
- Feedback & Results Display
- Messaging Integration (WhatsApp)
- Admin Dashboard 


## Component Responsibilities
- **User Management**: Handle registration, login, and profiles.
- **SMS Upload and Parsing**: Allows users to upload or manually enter SMS messages. Preprocesses the input before classification.
- **Spam Detection**: Uses a trained machine learning model to classify messages as "spam". Interfaces with backend for model inference.
- **Feedback & Results Display**: Shows users the classification result and allows them to submit feedback (e.g., if the prediction was incorrect). Feedback data can be stored for model retraining.
- **Messaging Integration**: WhatsApp API communication.
- **Admin Dashboard**: Manage verifications and reports.
