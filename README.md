# README

## *SECURITY IN-A-BOX*

### About Security in-a-box

**Security in-a-box** is a collaborative effort of the **Tactical Technology Collective** and **Front Line Defenders**. It was created to meet the digital security and privacy needs of advocates and human rights defenders. Security in-a-box includes a How-to Booklet, which addresses a number of important digital security issues. It also provides a collection of Hands-on Guides, each of which includes a particular freeware or open source software tool, as well as instructions on how you can use that tool to secure your computer, protect your information or maintain the privacy of your Internet communication.

### How to use the Security in-a-box Toolkit

This toolkit has three major sections:

* **Issues**
* **Hands-on Guides**
* **Community Focus**

The **Issues** section is designed to explain the issues that you must understand in order to safeguard your own digital security. It seeks to identify and describe the risks you face and help you make informed decisions about how best to reduce those risks. To this end, it answers eight broad questions related to basic security, data protection and communication privacy.

Each **Hands-on Guide** explains how to use a particular freeware or Open Source software tool. They highlight potential difficulties, suggest helpful tips and, most importantly, walk you through the process of configuring and using these tools securely. They include screenshots and step-by-step instructions to help you follow along.

Any single chapter or guide in this toolkit can be read individually, formatted in your browser for easy printing, shared electronically, or remixed according to your particular needs.

Where possible, you should read the chapters of the **Issues** section in order. *Security is a process*, and there is often little point in trying to defend yourself against an advanced threat to your communication privacy, for example, if you have not yet ensured that your computer is free of viruses and other malware. In many cases, this would be like locking your door after a burglar is already in your home. This is not to say that any one of these eight topics is more important than any other, it is simply that the later chapters make certain assumptions about what you already know and about the state of the computer on which you are about to install software.

The **Hands-on Guides**, however, can be used individually, and even remixed with just the parts that most suit your particular needs. They have been subdivided into snippets focusing on different topics, from the tool description to the instructions for installation and so on. Here is a complete index of the different content groups:

* Synthesis
  * Introduction
  * What you will get from this guide (**Note**: this should only be used together with the whole relevant hands-on guide)
* Basic Usage
  * Important premise (**Note**: when present, this file should always be included in the selection pertaining to the relevant tool)
  * Installation
  * Configuration
  * Update
  * Basic Howto
  * Problems and Solutions 
  * Portable
* Advanced Usage 
  * Advanced Howto
  * Add-ons
* FAQ
* Training 
  * Review questions

### Instructions for translators

In order to translate the SIAB texts, you need to use git, a very easy and versatile tool that enables to keep track of changes in the different versions of a project.
If you don't know how git works and want to know more, you can read this howto, translated in several languages: http://www-cs-students.stanford.edu/~blynn/gitmagic/ or this one (only in English): http://git-scm.com/book/en/v2

However, in order to use git all you have to do is downlad and install the software ( http://git-scm.com/download ) and then write the following commands in a shell interface:

$ git clone git@git.tacticaltech.org:ttc/siab-content.git

In this way you will download the whole Security in-a-box repository and will be able to edit it in your computer.

!!!new branch for each language? git checkout -b language!!!

If it is not the first time you are working with this repository, before you start your work, check that there have been no changes in the meantime by accessing your local SIAB directory in a shell interface and by digiting:

$ git pull

In this way you will update your repository and will make sure that there are no conflicts between your changes and other former changes by others.

Remember that when you add or remove new files you need to tell git to add or remove them from the repository:

* After you have added a new file, digit the command:
	$ git add filename
* After you have removed a file, digit the command:
	$ git rm filename
* If you just want to rename a file, you can do it from git by typing:
	$ git mv old-filename new-filename
* Likewise, if you want to move a file to a different directory, you can type:
	$ git rm filename new-directory

When you are done with you work, you can share it with everybody else through these simple commands:

$ git commit -a -m "Your description of what you did"
$ git push origin master

### Disclaimer

Software and documentation in this collection of Security in a Box is provided as is and we exclude and expressly disclaim all express and implied warranties or conditions of any kind, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose so far as such disclaimer is permitted. In no event shall Front Line Defenders, Tactical Technology Collective or any agent or representatives thereof be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption), however caused under any theory of liability, arising in any way out of the use of or inability to make use of this software, even if advised of the possibility of such damage. Nothing in this disclaimer affects your statutory rights.

### License

This work is licensed under a Creative Commons Attribution-Share Alike 3.0 Unported License.

### Credits and Acknowledgments

**Security in-a-box** was developed by the **Tactical Technology Collective** and **Front Line Defenders** in collaboration with:

**Coordination, writing & editing**

Wojtek Bogusz
Dmitri Vitaliev
Chris Walker
Ali Ravi

**Additional writing**

Carol Ann McGough
Benji Pereira
Dirk Slater
Oliver Leistert
Cormac McGuire
Becky Faith
Daniel Ó Clunaigh 

**Tactical Tech** is an international NGO helping human rights advocates use information, communications and digital technologies to maximise the impact of their advocacy work. We provide advocates with guides, tools, training and consultancy to help them develop the skills and tactics they need to increase the impact of their campaigning.

**Front Line Defenders** was founded with the specific aim of protecting human rights defenders at risk, people who work, non-violently, for any or all of the rights enshrined in the Universal Declaration of Human Rights (UDHR). Front Line Defenders aims to address some of the needs identified by defenders themselves, including protection, networking, training and access to international bodies that can take action on their behalf.
Funder

The development of the toolkit is supported by **Hivos**

**Hivos** is a Dutch non-governmental organisation inspired by humanist values. Together with local organisations in developing countries, Hivos seeks to contribute to a free, fair and sustainable world in which citizens - women and men - have equal access to the resources and opportunities for their development. And where they can actively and equally participate in decision-making processes that determine their lives, their society and their future.

### Website

https://securityinabox.org
