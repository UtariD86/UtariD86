![Project Logo](docs/images/command.jpg)
<div style="background-color: black; color: #00ff00; padding: 10px; font-family: 'Courier New', monospace;">test</div>

```powershell

PS C:\Users\Mehmet> Write-Output "Name: $($person.Name)"
Name: Mehmet Göksu

PS C:\Users\Mehmet> Write-Output "Role: $($person.Role)"
Role: Full-Stack Web Developer

PS C:\Users\Mehmet> Write-Output "Experience: $($person.Experience)"
Experience: 3 years in Full-Stack Web Development

PS C:\Users\Mehmet> Write-Output "Bio: $($person.Bio)"
Bio: 
I've been developing myself as a Full-Stack Web Developer for about three years. During this time, I have worked on freelance and hobby projects. In the last two years, I completed a 1.5-year internship at a Technopark company. After that, I completed my official internship at a company within Innopark and later took on a part-time role at another Technopark company, working on an SSO-based application designed for a project family. Nowadays, we are actively developing our own projects at "zurafworks".
Throughout this journey, I have improved myself in ASP.Net Core API, ASP.Net Core MVC, Entity Framework, SQL, Fluent Validation, JWT Authentication, jQuery, AJAX, Multi-Tenancy, Microservice, Redis Caching, and JavaScript. Additionally, I am proficient in N-Tier Architecture, Onion Architecture, and nArchitecture, as well as design patterns like UnitOfWork, Singleton, and Specification. I also have a strong grasp of OOP, ORM, and SOLID principles. Besides these, I have worked extensively with HTML, CSS, Bootstrap 5, and Python.

PS C:\Users\Mehmet> Write-Output "Skills: $($person.Skills -join ', ')"
Skills: ASP.Net Core API, ASP.Net Core MVC, Entity Framework, SQL, Fluent Validation, JWT Authentication, jQuery, AJAX, Multi-Tenancy, Microservice, Redis Caching, JavaScript, NTier Architecture, Onion Architecture, nArchitecture, UnitOfWork, Singleton, Specification design patterns, OOP, ORM, SOLID principles, HTML, CSS, Bootstrap 5, Python

PS C:\Users\Mehmet> Write-Output "Education: "
Education: 
PS C:\Users\Mehmet> $person.Education.GetEnumerator() | ForEach-Object { Write-Output "$($_.Key): $($_.Value)" }
Konya Technical University: Associate Degree in Computer Programming
Selçuk University: Bachelor's in Statistics

PS C:\Users\Mehmet> Write-Output "Current Company: $($person.Company)"
Current Company: zurafworks

PS C:\Users\Mehmet> Write-Output "Links: "
Links: 
PS C:\Users\Mehmet> Write-Output "[Zurafworks](https://zurafworks.com)"
[Zurafworks](https://zurafworks.com)

PS C:\Users\Mehmet> Write-Output "[Volleytics](https://volleytics.com)"
[Volleytics](https://volleytics.com)
```
