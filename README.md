# 🖥️ Online Judge Platform

An online judge platform hosting coding problems and challenges. Users solve a series of coding problems. First he has to begin with registration for his accound, user can register as admin or user(member). During problem solving, they submit their solutions through the platform. Once submitted, these solutions are evaluated against hidden test cases by the platform. Based on the results of these tests, user solution submission is assigned verdict. The platform provides the infrastructure to manage and execute the DSA coding problems, ensuring fair and impartial evaluation.

## 🌟 Features

- **User Authentication and Role-Based Authorization**: Secure login and role-based access.
- **User Dashboard**: Personalized dashboard for participants.
- **Problem Creation and Management Service**: Admins can create and manage problems.
- **Submission Service**: Participants can submit their solutions.
- **Multiple Languages and Themes**: Support for various coding languages and IDE themes.
- **Interactive Coding Workspace**: Real-time coding environment.
- **Problem Filters**: Search problems based on tags.
- **Validations**: Ensuring the correctness of passwords and code.
- **Optimized Queries**: Faster response times and reduced bandwidth consumption.

## 🛠️ Tech Stack

- **Core**:
  - React
  - MongoDB
  - Node.js (Express)
- **Libraries**:
  - ShadCN
  - TailwindCSS
  - react-hook-form
  - zod
  - zustand
    
## 🔄 Workflow

### User:
1. User logs in or registers.
2. User navigates through problem lists, participates in contests, solves problems.
3. User chooses a problem to solve.
4. User submits code.
5. Backend evaluates the code against test cases.
6. Submissions are stored and can be accessed later.

### Admin:
1. Admin logs in or registers.
2. Admin navigates through the dashboard.
3. Admin can create and edit problems.
4. Admin can change the status and test cases for the problems.
5. Admin can host a contest and see results [Coming Soon].

## 🚀 Deployment

- **Backend**: Containerized and deployed to GCP Run. [Link](https://online-judge-epxxu7x3eq-uc.a.run.app)
- **Frontend**: Deployed on Firebase. [Link](https://online-judge-e34be.web.app/)
## 🔧 Working On

- Validating user email.
- Features to host coding contests and ladders.
- Enhancements to the user dashboard.

## 🌐 Future Scope

- **AI-Based RAG Model**: Assist users with an AI-based model that embeds problems and user solutions. Using an LLM model, generate natural language responses to help users learn better and solve problems more efficiently.

## 🎨 Platform Visuals
### Default Website (Light Theme)
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/Light/landing.png?raw=true" alt="Landing page" style="width: 300px;"/>
        <br />
        <em>Figure 1: Landing page</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/Light/problems.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2: Problems Page</em>
      </td>
    </tr>
        <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/Light/problem-i.png?raw=true" alt="Landing page" style="width: 300px;"/>
        <br />
        <em>Figure 3.1: Problems page</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/Light/tags.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 3.2: Problems Tag Filter</em>
      </td>
    </tr>
  </table>
</div>

### Multi Theme Support Website (Dark Theme)
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/about.png?raw=true" alt="Landing page" style="width: 300px;"/>
        <br />
        <em>Figure 1: About Page</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/problem-n.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2: Problem page</em>
      </td>
    </tr>
        <tr>
     <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/login.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 3.1: Login</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/register.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 3.2: Register</em>
      </td>
    </tr>
     </tr>
        <tr>
     <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/select-tag.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 4: Tag Filter</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/problem-all-submision.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 5: Problem all Submissions</em>
      </td>
    </tr>
  </table>
</div>


### Different Dashboards for multiple roles 
<div align="center">
  <table>
    <tr>
    <th align="center">User Dashboard</th>
      </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/dashboard/profile-user.png?raw=true" alt="Landing page" style="width: 300px;"/>
        <br />
        <em>Figure 1.1: User Profile</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/dashboard/submission.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 1.2: User Submissions</em>
      </td>
    </tr>
  </table>
</div>

<div align="center">
  <table>
     <tr>
    <th align="center">Admin Dashboard</th>
      </tr>
   <tr>
     <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/dashboardadmin/problems.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2.1: Admin Problems</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/dashboardadmin/create.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2.2: Admin Create Problem</em>
      </td>
    </tr>
    <tr>
           <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/dashboardadmin/edit.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2.3: Admin Edit Problem</em>
      </td>
          </td>
           <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/dark/dashboardadmin/submissions.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2.4: Admin Submissions of Problem</em>
      </td>
    </tr>
  </table>
</div>


### Submissions in multiple Languages
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/lang/c.png?raw=true" alt="Landing page" style="width: 300px;"/>
        <br />
        <em>Figure 1: C</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/lang/cpp.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2: C++</em>
      </td>
    </tr>
        <tr>
     <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/lang/java.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 3: java</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/lang/python.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 4: Python</em>
      </td>
    </tr>
  </table>
</div>

    
### Supports multiple theme in code editor
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/theme/vs-dark.png?raw=true" alt="Landing page" style="width: 300px;"/>
        <br />
        <em>Figure 1: vs-dark</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/theme/rose.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 2: cd-rose (self defined)</em>
      </td>
    </tr>
        <tr>
     <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/theme/hc-black.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 3: hc-black</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/xl/theme/game.png?raw=true" alt="Landing register" style="width: 300px;"/>
        <br />
        <em>Figure 4: cd-game (self defined)</em>
      </td>
    </tr>
  </table>
</div>

### Highly responsive UI
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/sm/landing.png?raw=true" alt="Landing page" style="width: 200px;"/>
        <br />
        <em>Figure 1: Landing</em>
      </td>
         <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/sm/sidenav.png?raw=true" alt="Landing register" style="width: 200px;"/>
        <br />
        <em>Figure 2: Side Nav</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/sm/problems.png?raw=true" alt="Landing register" style="width: 200px;"/>
        <br />
        <em>Figure 3: Problems Page</em>
      </td>
    </tr>
        <tr>
     <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/sm/dashboard/admin-problem.png?raw=true" alt="Landing register" style="width: 200px;"/>
        <br />
        <em>Figure 4.1: Admin dashboard</em>
      </td>
      <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/sm/dashboard/admin-submission.png?raw=true" alt="Landing register" style="width: 200px;"/>
        <br />
        <em>igure 4.2: Admin dashboard</em>
      </td>
           <td align="center">
        <img src="https://github.com/HIMANSHUGUPTA123456/Online-Judge/blob/main/Assets/OJ/sm/dark/problem.png?raw=true" alt="Landing register" style="width: 200px;"/>
        <br />
        <em>igure 5: Problem Page</em>
      </td>
    </tr>
  </table>
</div>


