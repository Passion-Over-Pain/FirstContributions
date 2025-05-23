Some notes on  GitHub vs Team Foundation Server:
Has Nothing to do with this Repo :)
| Category                   | GitHub                                                                 | Team Foundation Server (TFS)                                             |
|---------------------------|------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Platform Type**         | Cloud-based version control and collaboration platform                 | Self-hosted project management and code versioning platform              |
| **Version Control System**| Uses Git exclusively for distributed version control                    | Supports both Git and centralized TFVC (Team Foundation Version Control) |
| **Hosting**               | Hosted by GitHub in the cloud                                           | Requires on-premise/self-hosting by the organization                     |
| **Integration**           | Integrates with many third-party tools and CI/CD services               | Integrates primarily with Microsoft tools (e.g., Azure DevOps, VS, Teams)|
| **Community**             | Large global developer community; ideal for open-source projects        | Enterprise-focused; suited for centralized enterprise development        |
| **Collaboration**         | Built for distributed teams and open collaboration                      | Designed for controlled, internal team access and workflows              |


# FirstContributions

> A step-by-step guide for everyone to get started on their open-source journey.

Many beginners (developers or non-developers) find it challenging to contribute to open source projects. They may feel that they are not skilled enough or that they don't know how to get involved. However, this is not true. Anyone can contribute to open source, regardless of their level of expertise. The key is to have a learning and helping others mindset, follow the best practices, and follow the specific guidelines of each project.

This repository provides a basic roadmap for anyone who wants to start their open source journey from scratch. It covers the essential steps and tools that you need to become a successful open source contributor.

## Table of Contents

- [What is Open Source?](#what-is-open-source)
  - [Main philosophy of Open Source](#main-philosophy-of-open-source)
- [Benefits of Contributing to Open Source](#benefits-of-contributing-to-open-source)
- [Find your Passion](#find-your-passion)
- [Find a project to contribute](#find-a-project-to-contribute)
- [Do I have the right skills?](#do-i-have-the-right-skills)
  - [Soft Skills](#soft-skills)
  - [Technical Skills](#technical-skills)
- [Learning the right skills](#learning-the-right-skills)
  - [Learning Git and GitHub](#learning-git-and-github)
- [Make your first contact](#make-your-first-contact)
- [Communicate Effectively and ask smart questions](#communicate-effectively-and-ask-smart-questions)
- [How to understand Large and Complex Codebases](#how-to-understand-large-and-complex-codebases)
- [Don't hesitate to help others](#dont-hesitate-to-help-others)
- [Document your journey](#document-your-journey)
- [Slides](#slides)

## What is Open Source?

The term [open source](https://opensource.org/osd/) means that anyone can see, understand, learn, modify, or distribute (depending upon the [license](https://opensource.org/licenses/)) the source code of the software. The amazing technology that we use nowadays became possible due to the rise of the open source movement.

The source code of:

- [Linux](https://github.com/torvalds/linux)
- [Blender](https://github.com/blender/blender)
- [Android](https://cs.android.com/android/platform/superproject/main)
- [Firefox](https://searchfox.org/mozilla-central/source)
- [Chromium](https://chromium.googlesource.com/chromium/src.git)
- [Apache HTTP Server](https://github.com/apache/httpd)
- [MySQL](https://github.com/mysql/mysql-server)
- [Git](https://github.com/git/git)
- [TensorFlow](https://github.com/tensorflow/tensorflow)
- [PyTorch](https://github.com/pytorch/pytorch)
- [VsCodium](https://github.com/VSCodium/vscodium)
- [GIMP](https://www.gimp.org/source/)
- [VLC](https://github.com/videolan/vlc)
- [InkScape](https://gitlab.com/inkscape/inkscape)
- [FFmpeg](https://git.ffmpeg.org/ffmpeg.git)
- [Kubernetes](https://github.com/kubernetes/kubernetes)
- [Docker](https://github.com/moby/moby)
- [MongoDB](https://github.com/mongodb/mongo)
- [Godot](https://github.com/godotengine/godot)
- [Krita](https://github.com/KDE/krita)
- Almost all the programming languages

And even many machine learning models like [Meta LLAMA 2](https://ai.meta.com/llama) and OpenAi's general-purpose speech recognition model [Whisper](https://github.com/openai/whisper) are open source. Also, there are some open source [games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) like [Doom](https://github.com/id-Software/DOOM). All of these are open source projects. You can see their source code, learn from them, modify them, and even contribute to them. You can also use them in your own projects. This is the power of open source.

### Main philosophy of Open Source

The main philosophy of open-source products is the freedom to think, create, learn, and share. It is a collaborative effort of many developers who are working together to create something amazing. In the early phases of technology, open source helps the technology to not become handicapped by some big entities and is developed by people who really have the passion to make that piece of technology better.

## Benefits of Contributing to Open Source

As a complete beginner in technology, we face a common problem that we are unable to make our hands dirty on the products or software that we use in our daily life and the software that powers the whole world. Here, open source solves the problem.

By working on an open source project you:

- Understand the magic behind the amazing technology.
- Improve your skills by working with other developers.
- Work and learn from the best developers and technology.
- Make an impact on the world by contributing to the projects that are used by millions.
- Open your door to the world of opportunities.
- Learn people skills like communication, teamwork, leadership, etc.
- Work on the thing that you are passionate about.
- Get paid (as a job or through some programs)

If you want to know if open source is for you or not, then ask these questions to yourself:

- Do you want to become a technology maker?
- Do you want to grow your network?
- Do you like improving the technology that you use in your daily life?
- Building a community?

## Find your Passion

You will be much more successful if you work on your passion. Therefore, the first step is to find your passion.

- The thing which you like to do in your free time.
- Which thing excites you the most?
- The thing which you do without any external or monetary motivation.
- Where do you see yourself in the next 2-3 years?
- Find the intersection of your passion and your technology.

For some people, it's like gaming or art, or poetry which they love to do in their free time. For example, if you like art then you can contribute to artistic software like Blender, Inkscape, GIMP, Openshot, Krita. This way you can improve your skills, learn from the best developers and make an impact on the world.

## Find a project to contribute

Now, you have identified your passion. The next step is to find a project to contribute to. Selecting a project is one of the crucial steps in your open source journey.

> Identify the project that you use in your daily life. This is the best way to find a project to contribute to. As you have the passion for that project and you know the pain points or features that you want to add or improve in that project.

- One of the easiest ways to find the project and the welcoming community is using the Google Summer Of Code [website](https://summerofcode.withgoogle.com/programs/2023/organizations).
  - Just go there, and search for the term that you are passionate about and you will find organizations that work on that technology.
- Use GitHub [Explore](https://github.com/explore/)
- See GitHub [trending repositories](https://github.com/trending)
- See GitHub [choosing a project](https://github.com/collections/choosing-projects)
- [Open Source Friday](https://opensourcefriday.com/)
- [First Timers Only](https://www.firsttimersonly.com/)
- [CodeTriage](https://www.codetriage.com/)
- [24 Pull Requests](https://24pullrequests.com/)
- [Up For Grabs](https://up-for-grabs.net/)
- [First Contributions](https://firstcontributions.github.io)
- [SourceSort](https://web.archive.org/web/20201111233803/https://www.sourcesort.com/)
- [OpenSauced](https://opensauced.pizza/)
- [Ovio](https://ovio.org)
  - For finding good first issues on this platform use this search [powerful issue search tool](https://ovio.org/issues)
- [Contribute-To-This-Project](https://github.com/Syknapse/Contribute-To-This-Project)
- [Open Source Welcome Committee](https://www.oswc.is/)

> See [freeCodeCamp/how-to-contribute-to-open-source](https://github.com/freeCodeCamp/how-to-contribute-to-open-source?tab=readme-ov-file#open-source-contribution-initiatives) for more resources.

## Do I have the right skills?

One of the myths that people have is that they need to be an expert in order to contribute to open source. This is not true. You don't need to be an expert to contribute to open source. You just need to have the right skills.

### Soft Skills

- You know where to find help.
- You learn from the feedback and respond well to it.
- You can work in a team or independently.
- You know when to ask questions.
- You can communicate effectively.
- Respect other people's opinions.

> Note: If you are not interested in the developer side, then you can also look for the Google Summer Of Docs program, which is specifically tailored for technical writing people.

### Technical Skills

- You know the basics of a specific programming language.
- You can fix common issues that are related to the project.
- You have basic experience with a project workflow.
- Knowledge of Git and GitHub is a plus.

## Learning the right skills

The right skills depend on the project that you want to contribute to. For example, if you want to contribute to a Python project then you should know the basics of Python. First, identify your project and then learn the skills that are required for that project.

- Use class central [website](https://www.classcentral.com/)
- Use edX [website](https://www.edx.org/)
- Use Coursera [website](https://www.coursera.org/)
- Use Udemy [website](https://www.udemy.com/)
- Use Udacity [website](https://www.udacity.com/)
- Use Khan Academy [website](https://www.khanacademy.org/)
- Use Codecademy [website](https://www.codecademy.com/)
- Use freeCodeCamp [website](https://www.freecodecamp.org/)
- Use YouTube [website](https://www.youtube.com/)

- For learning from the best universities, use this: https://csdiy.wiki/en/

Learning how to use a search engine is also a great skill to have, which you can learn from here:

- [Google: Power Searching with Google](https://www.edx.org/learn/google-power-searching/google-power-searching-with-google)
- [Google: Advanced Power Searching With Google](https://www.edx.org/learn/google-power-searching/google-advanced-power-searching-with-google)

### Learning Git and GitHub

See [GitHub Flow](https://docs.github.com/en/get-started) for learning Git and GitHub.
A more detailed guide is [freeCodeCamp/how-to-contribute-to-open-source](https://github.com/freeCodeCamp/how-to-contribute-to-open-source?tab=readme-ov-file#using-version-control)

## Make your first contact

Now, you have the right skills and you have identified the project that you want to contribute to. The next step is to make your first contact with the community.

- See the CONTRIBUTING.md or building instructions of that project.
- Read the documentation of that project.
- Build the project on your local machine.
- Run the tests.
- In this process, if you find any issue then try to fix it, introduce yourself to the community, raise a PR or an issue.
  - This is the best way to make your first contact with the community.
- If you don't find any good-first-issue then you can also introduce yourself to the community, ask for help, or ask for a good first issue.

## Communicate Effectively and ask smart questions

- Try to find the answer yourself.
- Search the archives of the forum or mailing list.
- Search the web.
- Read the documentation.
- Ask a skilled friend.
- Make it easy to reply.
- Don’t spam.
- Don’t dm mentors or org admins.
- Be Precise & Informative about your Problems

> Read this interesting guide http://www.catb.org/~esr/faqs/smart-questions.html for more information.

## How to understand Large and Complex Codebases

Understanding the code which was developed by experienced developers over a long period of time is a challenging task. Therefore, don't expect to understand the code by just looking at it. You have to understand the codebase in a systematic way. These are the steps that you can follow to understand the codebase.

- Read the documentation.
- Don't dive into the codebase without any purpose.
- At least know the basics of the programming language.
- Read the theoretical aspect of the project.
- Find a specific task that you want to do and then ask or find which part of the codebase is responsible for that task.
- Use the debugger to understand the codebase.
- Use the search feature of the codebase to find the specific code.
- Use `git blame` to find the author or context of the code.

## Don't hesitate to help others

- Open source is all about learning and helping others. If you find a beginner who is struggling with the same problem that you have faced in the past then don't hesitate to help them. Motivate and refer them to the right resources. This way you can also improve your skills and build a network.

## Document your journey

Documenting your journey is the best way to help others or maybe your future self in understanding the process that you have followed. You can document your journey in the form of a blog, video, or a GitHub repository. Documenting your journey through a blog is the easiest way to get started. You can use

- [Medium](https://medium.com/)
- [Hashnode](https://hashnode.com/)
- [Dev.to](https://dev.to/)
- [Substack](https://substack.com/)
- [Ghost](https://ghost.org/)
- [WordPress](https://wordpress.com/)
- [Blogger](https://www.blogger.com/)
- [Tumblr](https://www.tumblr.com/)
- [GitBook](https://www.gitbook.com/)
- [Notion](https://www.notion.so/)

For writing blogs, or if you want to host your personal site you can use these static site generators:

- [Jekyll](https://jekyllrb.com/)
- [Hugo](https://gohugo.io/)
- [Gatsby](https://www.gatsbyjs.com/)
- [Next.js](https://nextjs.org/)
- [Docusaurus](https://docusaurus.io/)
- [Docsy](https://www.docsy.dev/)
- [MdBook](https://rust-lang.github.io/mdBook/)
- [Doxygen](https://www.doxygen.org/)
- [Sphinx](https://www.sphinx-doc.org/)
- [MkDocs](https://www.mkdocs.org/)
- [BookStack](https://www.bookstackapp.com/)
- [FoamBubble](https://foambubble.github.io/)
- [VuePress](https://vuepress.vuejs.org/)
- [Docz](https://www.docz.site/)

## Slides

- [Google Summer Of Code Slides](https://docs.google.com/presentation/d/e/2PACX-1vTzjZ6Zwj-F51Hdu5cTai-G503oi0NOFVvbSuItI1JMJcyZUGQ2uf7GNiRXgCd_Aw/pub?start=false&loop=false&delayms=3000)
- [GitHub Seekho Slides](https://docs.google.com/presentation/d/e/2PACX-1vTvKx8Xh4k1bmUTot7hwTkvsbC9oyrbhs6W0swhCh4uEp9aSao4ddsyms0gaWkcfQ/pub?start=false&loop=false&delayms=3000)
