<!-- ********************************************************* HEADER ************************************************************************** -->

<!-- <h1 align="center">  📎 Open-Source-Software-Development-methods</h2> <br>

<em> Open Source software Development methods by <b> The Linux Foundation </b> 

Lecturer: <b>Jerry Cooperstein </b>, Training Program Director at The Linux Foundation, theoretical nuclear physicist </em>

<br> <hr> -->

<img src="https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods/blob/4271e4197857c258031962387ca80d1d3805b2e9/banner%20img%201-min%20(1).png" width="100%" >

<!-- ********************************************************* BODY BEGINS ************************************************************************** -->

### List of Contents

- [What is OSS](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#what-is-open-source-software)
- [Famous OSS](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#famous-open-source-softwares)
- [Advantages of OSS](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#advantages-of-open-source-software)
- [Licensing Classification](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#licensing-classification)
- [What is Propreitary Software](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#what-is-proprietary-software)
- [Successful OSS Projects](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#successful-oss-projects-a-few)
- [Contributing to OSS Projects](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#contributing-to-oss-projects-learn-the-previous-history--research-knowledge-and-preparation-is-vital)
- [Continuous Integration](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#continuous-integration)
- [What is CI/CD](https://github.com/ritikbalwant/CourseNotes-Open-Source-software-Development-methods#what-is-cicd)
- [Github and other hosting providers](#github-and-other-hosting-providers)
- [Concluding Remarks](#concluding-remarks)

### What is Open Source Software?

Source code is made available with a license which provides rights to:
- Examine
- Modify
- Redistribute
Without restriction on the user’s identity or purpose.

### Famous Open-Source Softwares:
- Mozilla Firefox 
- Blender
- Wikipedia
- VLC Media Player
- LibreOffice

### Advantages of Open-Source Software

- How Collaborative development lead to a better and more secure product
    - Enables to build better software
        - When a project is developed collaboratively by a diverse group of developers, maybe in different organisations, or companies, or geographic locations, one just has many more ideas to draw on.
        - Faster progress and reduced costs
            - When project is shared, not everyone has to solve the same problems and make the same mistakes 
        - Secure and Strong code when deployed
            -  More people viewing the code and more groups testing it 

- Security and Quality of source code
    - Coding standards and styles tend to be more cleaner and consistent on community projects
        - As more people have to understand and work on the code
        - Its kinda embarrassing to show ugly and sloppy code
        - Helps find security problems before product is deployed in the field
        - You get more input in the original design
        - Enables a lot of people to look for the security flaws and quickly publish fixes to them
        - Ability to fix bugs more quickly
- Business 
    - Lowers the total cost of development
    - Speeds up time of release to market
    - Encourages community feedback; criticism, suggestions, contributions
    - Supports upstreaming to reduce future costs for new products that reduce code
    - Uses well-delineated (precise) APIs
- Developers
    - Makes it easier to not have to re-invent everything
    - Helps to make good early decisions on product design by having more inputs
    - More people on the code helps to find and fix bugs faster
    - Allows for suggestions/contributions from a larger group which is really helpful
    - Helps to find the next job
        - Code is readily available for evaluation
        - Code shows how well you work and play with others
        - Shows how good you are at mentoring and maintaining projects and sub-projects
    - Builds community of developers

### Licensing Classification 

- Permissive
    - Any code changes need not be available to recipients. 
    - Often offered by companies because they're reluctant to give all their changes out to other entities. 
    - Eg BSD license Software
- Restrictive
    - Any code changes must be available to all recipients .
    - Known as copyleft too
    - Eg. GPL-licensed software (General Public License)

You can use the given link to help you choose the most appropriate license for your project:

* Choose an Open Source License:  by GitHub, this site walks you through the properties you must consider, helping you decide what license makes sense.


### What is Proprietary Software?

Only software owners, those who distributed originally, have the full legal access to the source code. They may give trusted partners the rights to inspect the code, especially if they want to develop companion products, but they will be forced to sign a non-disclosure agreement or NDA, and the source remains closed to a wider audience.

Now, if you use proprietary software, you have to sign a license and that license will restrict the rights. Such licenses generally say you can't redistribute the software.

### Successful OSS Projects (a few)

- Linux Kernel 
    - Open-source project since its inception in 1991
    - Linus Torvald’s student project
    - Released under GPL (General public license) v2
    - Android is based on Linux
    - Pace of Development is extremely rapid, new versions come out every 10-12 weeks
- Git
    - Distributed version control system that is used worldwide for an astounding number of collaborative products
    - Successfully handles its widely dispersed contributers
    - Github (used to host projects) is entirely based on Git
    - Can be used in non-open source projects (via private repositories)
- Apache
    - Most widely used web-server with around 50% of the market share 
    - Released under the Apache software license
- Computer Languages
    - Many computer languages are developed using OpenSource methods
        - Python
        - Perl
        - Ruby
        - GCC & LLVM
        - Rust 
        - and more

### Contributing to OSS projects (Learn the previous history- research, knowledge and preparation is vital)

- understand the ecosystem, the community and the methods of any project before diving in.
    - investigate the project, understand its style, what the workflow is, what the scope of the project is
    - Ask these
        - Why does this project exist and why was it started?
        - Has it diverged far from its original purpose?
        - Is the contributing community large or small? Continuously active or only sporadic burst of activity?
        - What kind of license does it adopt? Is there a CLA (Contributor License Agreement ) you have to agree on?
- See what communication methods the projects use
    - Mailing lists (check archives of mailing lists to see the history)
    - Chat rooms
- How are contributions made?
    - Revison control system (Git)
    - Through email and so on
- Before beginning to code, it's often good to volunteer your services for testing, finding bugs, et cetera.
    - Projects are often short for help in this
- Make sure you’re competent at whatever programming or scripting language the project uses
- Be polite and respectful and avoid contentious discussions 
- Don’t start with trivial patches (less important) such as changing white space in code and other things.

### Continuous Integration

it's very important to have fixes, updates, and new software rolled out as quickly as possible, with as few bugs or security problems as possible. This is where the concept of Continuous Integration comes in.

What Continuous Integration techniques do is they ensure you test constantly and frequently, that any problems which develop are quickly resolved, and developers and users all stay on the same page.

The Linux kernel development community employs a very robust Continuous Integration project, kernelci. While it was originally created by Linaro, it is now an independent Linux Foundation project.
Its mission is to help ensure long-term quality control, stability and facilitate maintenance of the Linux kernel. It works with:
* The kernel developer community, giving them a tool to use in their daily workflow as needed.
* Hardware manufacturers to help them stay close to kernel changes and development.
* Helping downstream developers by performing solid upstream testing.
Detailed reports are continuously updated in real time

### What is CI/CD? 

designed to be a vendor-neutral home for the coalescence of significant projects in the CI/CD (continuous delivery and integration) universe.
By establishing and documenting best practices, working out guidelines and making training available, the goal is to evangelize and spread CI/CD and DevOps practices and improve product release processes.

### Github and other hosting providers

Open source projects need a place to host your code, so that people can have access to it. And so they can concentrate on their work and not having to host a repository server.

The GitHub site was founded in 2008 and it has grown exponentially. In 2018, it had 30 million users and 60 million repositories.

Before wide use of GitHub and similar websites, projects needed to set up their own servers to host repositories, set things up, administer, make sure things are secure, et cetera. By using GitHub and others, a project can concentrate on its actual code and not having to deal with that sort of thing.

### Other providers include-

- GitLab
- GitKraken
- LaunchPad

There are two kinds of repositories on Github
- Public<br>
For a large-scale open source project, people generally use a public repository. Anybody can get permission to copy or fork a repository, download its contents. Uploading into the repository and making contributions requires permission that has to be given by whoever owns the repository. 
- Private <br>
With a private one, the owner restricts access to a named list of collaborators and only those people can actually use the repository and be able to update it. (Comes under the pro version ). it's used by many organizations for proprietary code or for even open source code that they're not quite ready to open up yet.

### Concluding Remarks

The goal is to promote healthy and rapid development from a large pool of contributors and users as possible.

While working on an OSS project, the best strategy is to:
Contribute your work in digestible pieces, in small meals, not in very large code dumps. People get overloaded, and overwhelmed when you give them a lot of code at once and it's very difficult to test individual parts if a lot of things are done at once.
