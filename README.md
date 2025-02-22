# Multimodal-Biometric-Authentication-system
This is a Deep Learning-based Biometric Authentication System leveraging TensorFlow, PyTorch, CNN,
and Hugging Face Transformers using facial recognition integrated with AWS S3 for cloud-based authentication.
#Workflow of the System
User Registration:

The user’s facial image is captured and preprocessed.
A deep learning model extracts facial embeddings and securely stores them in AWS S3.
User Authentication:

The user attempts login with a facial scan.
The system retrieves the stored face embeddings from AWS S3.
A similarity comparison is performed between the new scan and stored data.
If the similarity score meets the authentication threshold, access is granted.
Real-Time Verification & Security Measures:

Uses liveness detection to prevent spoofing attacks (e.g., detecting printed photos or deepfakes).
Logs authentication attempts and failed access attempts for security monitoring.
