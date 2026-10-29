<p align="center">
  <sub>WEB INTERFACES · APPLICATION DEVELOPMENT · LEARNING WORKFLOWS</sub>
</p>

<h1 align="center">E-learning Web Application</h1>

<p align="center">
  <em>Exploring the interfaces behind courses, enrollment, and administration.</em>
</p>

<p align="center">
  Academic application
  <br>
  C# / ASP.NET Web Forms / .NET Framework
</p>

<p align="center">
  <a href="#inside-the-application"><strong>Explore the application ↓</strong></a>
  &nbsp; · &nbsp;
  <a href="#implementation">Browse the implementation</a>
  &nbsp; · &nbsp;
  <a href="https://www.sandesh.design/">My portfolio ↗</a>
</p>

<br>

## Learning experiences have an operational side.

An e-learning application connects several kinds of activity: exploring courses, managing an account, enrolling, accessing content, and administering the information behind those experiences.

This academic project explores those workflows through an ASP.NET Web Forms application. The repository contains page layouts, C# code-behind files, shared page templates, and application configuration.

It complements my product-design work by showing the application structure behind web interfaces.

<br>

## Inside the application

### 01 / Explore courses
**Give learning content a place to begin.**

The application includes home, course, and content pages that form the browsing side of the experience.

[Explore the home page ↗](HomePage/HomePage.aspx)
&nbsp; · &nbsp;
[Explore course pages ↗](HomePage/course.aspx)
&nbsp; · &nbsp;
[Explore content ↗](HomePage/content.aspx)

---

### 02 / Manage an account
**Support the steps around the main task.**

Registration, sign-in, profile, and password-update pages provide the account-related interfaces surrounding the learning experience.

[Explore registration ↗](HomePage/Register.aspx)
&nbsp; · &nbsp;
[Explore sign-in ↗](HomePage/login.aspx)
&nbsp; · &nbsp;
[Explore profile pages ↗](HomePage/userprofile.aspx)

---

### 03 / Connect enrollment and coursework
**Extend the experience beyond browsing.**

The source includes enrollment and assignment-related pages, connecting course discovery with further learning activities.

These files document the implemented application structure; their current end-to-end behavior has not yet been revalidated.

[Explore enrollment ↗](HomePage/Enroll.aspx)
&nbsp; · &nbsp;
[Explore assignments ↗](HomePage/Assignment.aspx)

---

### 04 / Support administration
**Consider the interfaces behind the content.**

Administrative pages include course creation, content entry, student enrollment, and assignment management.

This adds a second perspective to the project: the people maintaining the learning environment.

[Explore administration ↗](HomePage/adminpanal.aspx)
&nbsp; · &nbsp;
[Explore course creation ↗](HomePage/AddCourses.aspx)
&nbsp; · &nbsp;
[Explore assignment management ↗](HomePage/ManageAssignment.aspx)

<br>

## Implementation

The checked-in project uses **C# and ASP.NET Web Forms**, targeting **.NET Framework 4.7.2**.

Pages use `.aspx` markup with associated C# code-behind files. Master pages provide shared page structure. The inspected source also includes SQL Server access code.

| Area | Where to look |
| :--- | :--- |
| **Visual Studio solution** | [`HomePage.sln`](HomePage/HomePage.sln) |
| **Project definition** | [`OnlineLearningCourse.csproj`](HomePage/OnlineLearningCourse.csproj) |
| **Home-page markup** | [`HomePage.aspx`](HomePage/HomePage.aspx) |
| **Home-page code-behind** | [`HomePage.aspx.cs`](HomePage/HomePage.aspx.cs) |
| **Shared page structure** | [`First.Master`](HomePage/First.Master) |
| **Administration template** | [`Admintemplate.Master`](HomePage/Admintemplate.Master) |
| **Package declarations** | [`packages.config`](HomePage/packages.config) |

<br>

## What to look for

**How the workflows are divided.**  
Compare browsing, account, enrollment, and administration pages to understand how different tasks are represented in the application.

**How shared structure supports consistency.**  
Review the master pages alongside individual screens to see which parts of the interface are shared.

**How interface and application code connect.**  
Read `.aspx` pages with their corresponding `.aspx.cs` files to examine the relationship between controls, events, and application behavior.

<br>

<details>
<summary><strong>Development environment & setup notes</strong></summary>

<br>

This is a historical ASP.NET Web Forms project targeting **.NET Framework 4.7.2**.

A suitable starting environment is Windows with Visual Studio, ASP.NET web-development tooling, and the appropriate .NET Framework targeting support.

Suggested inspection sequence:

1. Open `HomePage/HomePage.sln`.
2. Review the project references and `packages.config`.
3. Restore the required packages.
4. Review the application's database and service configuration.
5. Configure a local development database where required.
6. Build the solution and test the relevant workflows.

Use your own local development configuration. Do not assume the original database or connected resources are available.

**Current verification status:** a clean build, database setup, and end-to-end application run have not yet been verified for this documentation update.

</details>

<br>

<details>
<summary><strong>Project scope & limitations</strong></summary>

<br>

This repository documents an academic web application.

The presence of account, enrollment, and administration pages does not establish production readiness or verified authorization behavior. Current functionality depends on the application configuration, dependencies, and database.

No commercial adoption, measured learning outcomes, or independently verified accessibility or security compliance is claimed here.

</details>

<br>

---

<p align="center">
  <strong>Part of Sandesh Subedi’s design and development work.</strong>
</p>

<p align="center">
  <a href="https://www.sandesh.design/">Portfolio</a>
  &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/sandeshxd/">LinkedIn</a>
  &nbsp; · &nbsp;
  <a href="mailto:subedi.38@wright.edu">Get in touch</a>
</p>
