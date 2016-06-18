#Step 1: Build Models & AR Associations
- User
  first_name
  last_name
  email
  city
- Opportunity
  job_title
  job_description
  salary_range
  state (from aasm-interest, applied, tech-interview)
- Company
  name
  city
- City
  name

#Step 2: Create controllers for models

#Step 3: Add active model serializers

#Step 4: Add state machine (aasm gem)

#Step 5: Wire up Angular

#Step 6: Add authentication - angular devise

#Step 7: Build angular service to consume job board APIs  
