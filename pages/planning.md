---
layout: section
class: dark-bg
---

# Planning

<style>
    h1{
        color: #F02C64;
        font-weight: 600;
    }

    .dark-bg{
        background-color: #141521
    }

</style>

---
hideInToc: true
---

# MVP

- Authentication 
    - Login
    - Anonymous Login
    - Signup
    - OAuth
    - Forgot Password
- Polls
    - Create
    - Share
    - Vote
    - Anonymous Vote


<style> 
    h1{
        color: #F02C64;
        font-weight: 500;
    }
</style>

<!-- We need to discuss the goals and minimial features for this project -->


---
transition: fade
hideInToc: true
---

# UI/UX Designing

<div flex justify-center content-center>
<div flex-col content-center justify-center mr-7 self-center>
<img src="/bit.ly_3QeJzAD.png" h-40 mt-11  mx-auto/>
<p text-center text-slate-500> (Scan the code to view the design on Penpot)</p>
</div>
<img src="/penpot.svg" h-36 mt-8  mx-auto self-center/> 
</div>

<style>
  h1{
        color: #F02C64;
        font-weight: 500;
    }
 </style>

<!-- Talk about Penpot
    Open source design tool
    alternative to Figma Adobe XD
    Written in Clojure
    have a good technical documentation and const improving
    make designs get code at the instant
 -->

---
layout: image
image: ./penpot-home.png
hideInToc: true
---


---
layout: center
class: dark-bg
hideInToc: true
---

# Tech Stack

<style>
    h1{
        color: #F02C64;
        font-weight: 600;
     }

    .dark-bg{
        background-color: #141521;
    }
</style>

---
layout: default
class: text-center dark-bg
hideInToc: true
---

# Frontend
<div flex justify-center gap-x-14 mb-7 mt-8>

<v-clicks depth= '1'>
<img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg" class ="h-20 my-auto" />


<img src="https://pink.appwrite.io/logo.svg"  class ="h-36 w-3/12" />
</v-clicks>
</div>

# Backend

<v-click>
<img src="https://appwrite.io/images/appwrite.svg" class= "h-36 w-3/12 mx-auto"/>
</v-click>

<style>
    h1{
        color: #FEFEFF;
        font-weight: 500;
    }
    .dark-bg{
        background-color: #141521;
    }
</style>

<!-- Svelte - web framework. Reactive and easy to use. Not setState useState stuffs.
    Pink Design is Appwrite's open-source design system for building consistent and reusable user interfaces. Pink is designed to prioritize collaboration, dev experience, and accessibility.
 -->

---

# App Flow

```mermaid
flowchart LR
    A[Landing Page] --> B{Is Signed in?}
    B --> |Yes| C[Home page]
    B --> |No| D[Sign In page]
    D -.-> C
    F(logout) --> A
    C --- E(Create Poll)
    C --- F
    E ---> G[Poll Screen]
    G --- F
    G --- H(Share Poll)
    G -.- |Creator only| I(Stop Poll) --> C
    J>Voter] --> |authenticated| G
    J ---> |unauthenticated| D

```


<style>
    h1{
        color: #F02C64;
        font-weight: 600;
    }

    .graphite-col{
        color: #373d4d; /* #373d4d graphite color */
    }

</style>

