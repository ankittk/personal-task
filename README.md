# Problem Statement: Developing a Finance Management System

## Objective  
Build a comprehensive **Finance Management System** similar to Splitwise. The system will allow users to track expenses, split bills, and settle dues with others. The project will include **frontend, backend API development, deployment, monitoring, and testing**, providing a hands-on full-stack learning experience.

---

## Requirements

### 1. Frontend  
- A user-friendly web interface.  
- **Features:**
  - Add, view, update, and delete expenses.  
  - Split bills among users with flexible ratios.  
  - Display a dashboard showing balances (who owes whom).  
  - Settling payments between users.

### 2. Backend  
- A RESTful HTTP API.  
- **Features:**
  - CRUD operations for expenses and users.  
  - Logic to calculate balances dynamically.  
  - API for retrieving transaction history and settlement status.  
- **Authentication:** Token-based authentication (e.g., JWT).  
- **Testing:** Basic tests for all API endpoints.

### 3. Database  
- Use a relational database (e.g., PostgreSQL).  
- **Tables:**
  - `users` (user information).  
  - `expenses` (expense details like amount, payer, participants).  
  - `balances` (track who owes whom).  

### 4. Deployment  
- Containerize the application using Docker.  
- Deploy the application to a cloud platform (e.g., AWS, GCP, Azure, or Minikube locally).  
- Use Kubernetes for orchestration.  
- Implement CI/CD using GitHub Actions.

### 5. Metrics and Monitoring  
- **Metrics to monitor:**
  - Total expenses tracked.
  - Average response time of APIs.
  - Error rates and API latencies.  
- Use Prometheus + Grafana for dashboards.  

### 6. Testing  
- **Tests to include:**
  - Unit tests for backend calculations (e.g., splitting logic).  
  - Integration tests for APIs.  
  - End-to-end tests for user flows (e.g., adding an expense, settling dues).  

### 7. Features to Extend (Optional)  
- Allow group creation and expense tracking within groups.  
- Add notifications for pending payments or settlements.  
- Integrate with payment gateways for direct settlement (e.g., PayPal or Stripe).  

### 8. Documentation  
- Document the API using OpenAPI/Swagger.  
- Write a README with setup instructions, architecture details, and usage examples.

---

## Deliverables  
- A deployed, functional application accessible via a browser.  
- Metrics dashboard for monitoring application health.  
- Comprehensive test suite and results.  
- Deployment pipeline and Kubernetes YAML files.  
- API documentation.  
