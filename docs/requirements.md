# EduProctor Requirements

## Key Functional Requirements

### 1. User Registration and Login
- Students and proctors can:
  - Register with email verification
  - Login with multi-factor authentication
  - Reset passwords securely

### 2. Exam Scheduling
- Admins can:
  - Create/schedule exams with time windows
  - Assign proctors to exam sessions
  - Set exam parameters (duration, attempts, etc.)

### 3. Exam Participation
- Students can:
  - Join exams with live webcam/mic streaming
  - Navigate through exam questions
  - Request technical support during exams

### 4. AI-Based Monitoring
- System automatically detects:
  - Unauthorized persons (face mismatch)
  - Suspicious noises (background voices)
  - Screen sharing attempts
  - Unusual eye movements

### 5. Proctoring Dashboard
- Proctors can:
  - View up to 16 candidates simultaneously
  - Receive real-time AI alerts
  - Send warnings/terminate suspicious sessions
  - Initiate live chat with candidates

### 6. Exam Submission & Results
- Automated processes for:
  - Secure exam submission
  - Anti-tampering validation
  - Result generation with audit logs
  - Score reporting to LMS integration
## Technical Requirements (Tech Stack)

### Frontend
- **Framework**: React.js with TypeScript
- **Real-Time**: WebRTC for video/audio streaming
- **UI Components**: Material-UI or Ant Design
- **State Management**: Redux

### Backend
- **Core**: Node.js with Express/NestJS
- **AI Processing**: Python (OpenCV, TensorFlow)
- **Realtime**: WebSocket communication

### Database
- **Relational**: PostgreSQL (exam data, user profiles)
- **Unstructured**: MongoDB (monitoring logs)
- **Caching**: Redis

### Infrastructure
- **Cloud**: AWS/Azure
- **Containerization**: Docker/Kubernetes
- **CI/CD**: GitHub Actions