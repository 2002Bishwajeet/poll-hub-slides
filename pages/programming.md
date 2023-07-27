---
layout: center
class: dark-bg
hideInToc: true
---

<div flex gap-x-24>

<h1 class="self-center"> Programming Time </h1>

<img src="https://media3.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif?cid=ecf05e47gxe14igjs2jwvmwvcopkn3gs0x3tu8ol0fkaq85m&ep=v1_gifs_search&rid=giphy.gif&ct=g"  mt-11  mx-auto/>

</div>

<style>
    h1{
        color: #F02C64;
        font-weight: 600;

    }


  

</style>

---
layout: center

---

# Setup Project

<style>
    h1{
        color: #F02C64;
        font-weight: 600;

    }


  

</style>

---
hideInToc: true
---

# Starter Template


<div class="w-5/12 mx-auto mt-12">
<img src ="github-starter-repo.png"/>
</div>



<style>

     h1{
        color: #373d4d;
        font-weight: 600;

    }

    </style>


---
hideInToc: true
---
# Directory Structure


```bash
.
├── functions # Cloud functions
│   └── create-poll 
├── public # static assets
├── src
│   ├── assets # images
│   └── lib
│       ├── components # Reusable svelte components
│       ├── elements # forms
│       ├── layout
│       ├── models # custom model interfaces
│       ├── pages # Pages
│       ├── sdk 
│       │   ├── appwrite
│       │   └── mock
│       ├── store # state management variables
│       └── utils # misc stuffs
└── tests # unit tests but not really
```

<style>

     h1{
        color: #373d4d;
        font-weight: 600;

    }

    </style>

---

# Adaptor Pattern


<style>
    h1{
        color: #F02C64;
        font-weight: 600;

    }
</style>

--- 

# Setup Appwrite

### Head over to [cloud.appwrite.io](https://cloud.appwrite.io) and create an account

  <img src= "/appwritecloud.png" class="h-2/3" mx-auto mt-12/>

  <!-- Discuss about creating a new project -->

<style>
    h1{
        color: #F02C64;
        font-weight: 600;

    }
</style>

---
layout: center
hideInToc: true
---
# Setup OAuth


<style>

     h1{
        color: #F02C64;
        font-weight: 600;

    }

    </style>


---
layout: two-cols
hideInToc: true
---
# Github OAuth

For setting up Github Oauth we need appId and secret from Github:

![Alt text](github1.png)

::right::

![Alt text](github2.png)

<style>

     h1{
        color: #373d4d;
        font-weight: 600;

    }

    </style>

---
layout: two-cols
hideInToc: true
---

<img src="github3.png" class="" />


::right::

![Alt text](github4.png)


---
layout: center
hideInToc: true
---

# Same goes for Discord 🙂

(Read their docs for more info)


<style>

     h1{
        color: #F02C64;
        font-weight: 600;

    }

    </style>


---
hideInToc: true
---


# Setup Cloud Functions

The recommended way is to do by using the Appwrite CLI

<div flex gap-12>

<div>

### Install via NPM

```bash
npm install -g appwrite
```

### Login to Appwrite

```bash
appwrite login
```
</div>

<div >

### Create a new function

```bash
appwrite init function
? What would you like to name your function? My Awesome Function
? What runtime would you like to use? Node.js (node-18.0)
✓ Success! 
```


### Deploy the function

```bash
appwrite deploy function
? Which functions would you like to deploy? Awesome Function (621229798628cf5bf712)
ℹ Info Deploying function Awesome Function ( 621229798628cf5bf712 )
✓ Success Deployed Awesome Function ( 621229798628cf5bf712 )
```

</div>

</div>


<style>

     h1{
        color: #F02C64;
        font-weight: 600;

    }

    h3{
        color: #373d4d;
        font-weight: 500;
        margin-top: 2rem;
        margin-bottom: 0.5rem;
    }

    </style>

---
hideInToc: true
---

# Database Collection + Attributes


<style>


     h1{
        color: #373d4d;
        font-weight: 600;

    }

    </style>

---
hideInToc: true
---

# Authentication


<style>


     h1{
        color: #F02C64;
        font-weight: 600;

    }

    </style>

---
hideInToc: true
---

# Databases


<style>


     h1{
        color: #F02C64;
        font-weight: 600;

    }

    </style>