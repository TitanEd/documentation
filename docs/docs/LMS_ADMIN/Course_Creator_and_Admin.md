# User Roles and Permissions

This document outlines the roles, access levels, and capabilities of Course Creators and Platform Administrators (Admins) within the platform.

---

## 1. Course Creator (Instructor / Staff / Studio Role)

### Access
- Limited to Studio (Course Authoring Tool).
- Only sees and manages courses they are assigned to.

### Capabilities
- Create and design courses using Studio.
- Add units, sections, videos, quizzes, and assignments.
- Set up course grading and pacing (self-paced or instructor-paced).
- Manage course content release schedules.
- Add or remove instructors and team members within that course.
- Monitor course progress via Instructor Dashboard (in LMS).
- Send emails to enrolled learners.

### Typical Users
- Instructors  
- Course developers  
- Instructional designers

---

## 2. Admin (Platform Administrator / Superuser)

### Access
- Full access to both LMS and CMS (Studio).
- Can access the Django Admin Panel (`/admin` URL).
- Can manage all site-wide settings and all courses.

### Capabilities
- Add and remove users globally.
- Assign roles such as staff, superuser, or course instructor.
- Manage platform-wide configurations (branding, email, integrations).
- Enable or disable features (certificates, SSO, payments, etc.).
- Control advanced settings (site security, analytics, storage).

### Typical Users
- System administrators  
- Platform maintainers

---

## Summary Table

| Feature/Capability                 | Course Creator       | Admin (Superuser)     |
|-----------------------------------|-----------------------|------------------------|
| Access to Studio                  | Yes                   | Yes                    |
| Access to Django Admin Panel      | No                    | Yes                    |
| Can create and edit courses       | Yes (assigned ones)   | Yes (all courses)      |
| Manage user roles platform-wide   | No                    | Yes                    |
| Manage only their own courses     | Yes                   | No (has all access)    |
| Platform configuration/settings   | No                    | Yes                    |
