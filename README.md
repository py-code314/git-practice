### Screenshots

It's readme file

## 🚀 Features

### 1. Authentication & Session Handling:
      
  - `passport-local` for authenticating login by email & password.
  - `passport-jwt` for authenticating subsequent requests by validating JWT.
  - Login sessions are handled via JWT with an expiration time of 1 day.

### 2. Post & Comment Management:

  - Full CRUD (Create, Read, Update, Delete) operations for blog posts reserved for authors.
  - Status management for posts (e.g., Published Posts vs Drafts)
  - Read-only access for published posts for readers.
  - Commenting option on posts which is limited to users logged in.
