# Understanding Docker

This series will involve exercises to practice and learn docker.But before that let dive in a litle and understand Docker by answering few Wh-questions.

what 
why
who 
when
where

## What is Docker?
    
`Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Docker combines all the dependencies into a container allowing it to run independent of environment. `

To understand how docker works, let us take an example of frozen food. You went to market and brought one of the packets and then cooked it directly using oil or water, whatever it required. It does not matter if the raw material required to make the dish is available around you or you know how to cook it. All you need is the packet and some oil.And now you cooked it perfectly.

    Similarly,The Docker works. The Packet here is the Container of the application, the oil- Docker CLI.

    The user need not to worry about the dependencies like the condition or the recipe in the former case, all that is handled by docker.

## Why is a Container Different from VMs

Containers are analogous to VM, but the main difference is the shared Kernel in Containers.

 For every replica of an application a new Guest OS is used in VM which consumes the majority of resources available for the container. While in Containers the host is shared thus saving the resources for the processes running.

Another difference between is the space consumed by an application.

 Size of ubuntu on a VM is about 2.3 Gb, While the size of ubuntu image is just 188 Mb. The storage makes is more convenient to use Docker.

For better understanding check out [this](https://www.youtube.com/watch?v=0qotVMX-J5s) video or [this article](https://opensource.com/resources/what-are-linux-containers?intcmp=7016000000127cYAAQ).

<p>
<img src=https://i.ytimg.com/vi/TvnZTi_gaNc/maxresdefault.jpg height=300
>
</p>

