# Data Engineering Undercurrents: Security, Privacy & Data Quality

## 1. Security

Security in data engineering focuses on protecting systems and data from unauthorized access.

### Key Concepts

#### Authentication
Verifies the identity of a user.

> Example: Logging in with username/password or IAM credentials

#### Authorization (Access Control)
Determines what actions a user is allowed to perform.

> Example: Read-only access vs admin access

#### Principle of Least Privilege
Users should only have the minimum permissions required.

> Example: A junior engineer should not have full admin access

---

### Important Note
Security is not absolute.

> It is about reducing risk through multiple layers of protection.

---

## 2. Privacy

Privacy focuses on protecting sensitive user data.

### Why it matters
- Increasing digital data generation
- Frequent data breaches
- Regulatory requirements (GDPR, etc.)

### Key Concept

#### Personally Identifiable Information (PII)
Data that can identify an individual.

Examples:
- Name
- Email
- Phone number

---

### Best Practices
- Minimize collection of sensitive data
- Protect stored data
- Control access strictly

---

## 3. Data Quality

Data quality is one of the most critical aspects of data engineering.

> It is all about **trust**.

If users lose trust in data:
- They stop using dashboards
- They rely on raw data instead

---

## Key Insight

> Data fails silently.

Unlike software systems:
- Applications crash visibly
- Data pipelines may fail without obvious signs

---

## Why Data Quality is Hard

- Issues may not be obvious
- Problems can occur without code changes
- Requires continuous monitoring

---

## Data Quality vs Software Quality

### Software
- Issues occur during deployment
- Bugs are easier to detect

### Data
- Issues can occur anytime
- Often involves subtle statistical changes

---

## Example Scenarios

### Case 1: Sudden spike in sales
Possible reasons:
- Real business growth
- Pipeline bug

### Case 2: Zero sales
Possible reasons:
- No customer activity
- Pipeline failure

---

## Key Techniques

### 1. Validation
- Check data correctness
- Example: Null checks, constraints

### 2. Testing
- Ensure pipeline logic works
- Example: Unit tests for transformations

### 3. Observability
- Monitor pipeline health
- Detect anomalies

---

## Final Takeaways

- Security protects access
- Privacy protects sensitive data
- Data quality ensures trust

> Without trust, data engineering fails.
