---
layout: post
title: The Linux kernel bug fixing mentorship
date: 2024-12-11 20:00:00
summary: My experience of the mentorship and contributing to the kernel
---

In this blog I will be talking about my experience of the mentorship program including the timeline of the mentorship program, pre-requisite challenges and my contributions to the kernel.

### 1. The Timeline and applying to the mentorship
I got to know about the mentorship when I started researching about getting into Linux kernel development. There are many mentorships from Linux Foundation which have been really helpful in getting many beginners into open-source community. The various mentorships can be browsed from [LFX Mentorship portal](https://mentorship.lfx.linuxfoundation.org/#projects_all).

The Linux kernel bug fixing mentorship has two intakes, one in fall and another in summer. I applied for the fall'24 intake in mid August, the applications are open much earlier for fall intake. I had to create an account and apply for the mentorship program from the above mentioned link. For the application I had to answer a few questions - about why I wanted to apply for the mentorship and my professional background and goals. 

Once the application is completed, there are a few pre-requisite tasks that get added to the candidate's dashboard. These tasks have a specific deadline based on their difficulty. One of the tasks was completion of LFD103 course, which is of super importance for the mentorship for beginners(It's a free course provided by Linux Foundation).

After waiting for a week I got an acceptance mail from the program's mentor Shuah Khan, informing about the duration and meetings for the program. This program was for 3 months, and we had a meeting every Friday for an hour.

### 2. Finding and fixing bugs
When looking for bugs to fix - there are two categories of bugs based on how they are found -- 
- Static analysis bugs - These are discovered before the program is run.
- Dynamic analysis bugs - These are discovered when the program is being run.

#### 2.1 Static analysis bugs - 
There are 4 tools that I have used for finding static analysis bugs along with the resources that would help in using these tools:
1. Sparse : [How to install and use sparse](https://kernelnewbies.org/Sparse)
2. Coccinelle : [Coccinelle, a Static Analysis Tool](https://medium.com/@alessandrozanni.dev/coccinelle-a-static-analysis-tool-68941eb48cf8)
3. Coverity : Would need access from the Admins and account creation required [Coverity Scan](https://scan.coverity.com/)
4. Checkpatch.pl : This is included in the kernel under scripts directory, it is recommended to run this on every patch that is sent upstream, maintaining coding style standards.

#### 2.2 Dynamic analysis bugs -


### 3. My contributins to the Kernel


