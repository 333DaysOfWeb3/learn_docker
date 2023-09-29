# Learn Docker

## What is Docker?

    Docker makes development efficient and predictable

    Docker takes away repetitive, mundane configuration tasks and is used throughout the development lifecycle for fast, easy and portable application development – desktop and cloud. Docker’s comprehensive end to end platform includes UIs, CLIs, APIs and security that are engineered to work together across the entire application delivery lifecycle.

    -- The Docker team

Docker allows us 
* to deploy applications inside "containers" (~very lightweight virtual machines)
* instead of just shipping an application, we can ship an application and the environment it's meant to run in


## What is a container?

    A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

    -- Docker

* virtual machines are very heavy on resources 
* a container gives us 95% of the benefits that virtual machines offer (at least as back-end developers), but are super lightweight. They boot up in seconds, while virtual machines can take minutes.
* Virtual machines virtualize hardware, they emulate what a physical computer does at a very low level. 
* Containers virtualize at the operating system level. 
* Isolation between containers that are running on the same machine is still really good. For the most part, it appears to each container as if it has its own operating and filesystem.

