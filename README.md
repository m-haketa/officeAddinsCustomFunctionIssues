# About This Repository

This repository is created to repoduce the issues for custom functions.


## How to install this add-ins

1. Start Office on the web

2. Click "Home" tab and click "Add-ins" button, then click "More Add-ins"

3. Click "Upload My Add-in" and select [manifest_dist.xml](./manifest_dist.xml)


## Steps to create this repository

### 1. create project

```sh
> yo office

     _-----_     ?──────────────────────────?
    |       |    │   Welcome to the Office  │
    |--(o)--|    │   Add-in generator, by   │
   `---------´   │ @OfficeDev! Let's create │
    ( _´U`_ )    │    a project together!   │
    /___A___\   /?──────────────────────────?
     |  ~  |
   __'.___.'__
 ´   `  |° ´ Y `

? Choose a project type: Excel Custom Functions using a Shared Runtime
? Choose a script type: (Use arrow keys)
? Choose a script type: TypeScript
? What do you want to name your add-in? officeaddins_helpurlissue

```

### 2. Add help file and helpurl property

See commit b216af3a16b57de6d38fd135043bcc72e9965ac5.
