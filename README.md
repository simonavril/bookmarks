Bookmarks  Dev - Devops
==================

Here is the evolving list of notes/blog posts that I want bookmarked.

----------

Infrastructure
==================

Deployment
----------
 - [Great talk][7]: Noah Kantrowitz: Application Deployment State of the Onion. He explains the different strategies one can use to update, deploy, configure and orchestrate a non trivia app. 

Architecture
-----------
 - [5 Common Server Setups For Your Web Application][8] 

Security
---------
 - [My First 5 Minutes On A Server. Bryan Kennedy.][1] 

Ansible
---------
 - [The official docs][9] 
 - [My First 5 Minutes On A Server with Ansible. Matthew Smith][2]

Vagrant
---------
 - [The official docs](https://docs.vagrantup.com/v2/) 


Docker
---------
  - [The official docs][10] 
  - [Ken Cochrane's Guidebook](http://kencochrane.net/blog/2013/08/the-docker-guidebook/)
  - [How mailgun uses Docker (watch video)][11]
  - [Should I use Vagrant or Docker.io for creating an isolated environment?][6]
  - [Continous Integration Workflow with Docker](http://mike-clarke.com/2013/11/applied-docker-continuous-integration/)
  
**Understanding the persistance of data:**
   
   -  [Advanced Docker Volumes: Michael Crosby][3]
   -  [Tiny Docker Pieces, Loosely Joined. Tom Offermann][4]

**Container Linking:**
  - [Docker Links and Runtime Environment Variables](http://mike-clarke.com/2013/11/docker-links-and-runtime-env-vars/)

**Miscelanous:**

   - [Dokku][5]: The smallest PaaS implementation you've ever seen 
   - [Self testing fabfile using docker][12]
   - [http://www.slideshare.net/dotCloud/docker-at-djangocon-kencochranedockertalk2013](http://www.slideshare.net/dotCloud/docker-at-djangocon-kencochranedockertalk2013)
   - [http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)
   - [setting up docker as local dev](http://www.altviz.co/blog/using-docker-as-a-development-environment)
   - [Building a development environment](http://tersesystems.com/2013/11/20/building-a-development-environment-with-docker/)
   - [https://gist.github.com/wsargent/7049221](https://gist.github.com/wsargent/7049221)

*Advanced:*
   - [Multi host containers](http://goldmann.pl/blog/2014/01/21/connecting-docker-containers-on-multiple-hosts/)
   - [Github Repo that configures gitlab with Docker - Sameer Naik](https://github.com/sameersbn/docker-gitlab/)

Email
-----
   - [What MTA email client to use](http://linuxmantra.com/2010/07/sendmail-vs-postfix-vs-qmail-vs-exim.html)
   
Development
==========

Python
------
   - [Understanding meta-classes in Python](http://stackoverflow.com/a/6581949)
   - [Creating a Plugin architecture in 6 lines](http://martyalchin.com/2008/jan/10/simple-plugin-framework/)

Git
---
   - [Working with big git repositories. Shallow clonning and co.](http://blogs.atlassian.com/2014/05/handle-big-repositories-git/)


Design Pattern
--------------
   - [Awesome article on design pattern for game development](http://gameprogrammingpatterns.com/)

Fun
----
   - [The maps of the internet on Vox](http://www.vox.com/a/internet-maps)

Others
=========
   - [A Practical Guide to Web App Success](http://webappsuccess.com/)



  [1]: http://plusbryan.com/my-first-5-minutes-on-a-server-or-essential-security-for-linux-servers
  [2]: http://lattejed.com/first-five-and-a-half-minutes-on-a-server-with-ansible
  [3]: http://crosbymichael.com/advanced-docker-volumes.html
  [4]: http://www.offermann.us/2013/12/tiny-docker-pieces-loosely-joined.html
  [5]: http://progrium.com/blog/2013/06/19/dokku-the-smallest-paas-implementation-youve-ever-seen/
  [6]: http://stackoverflow.com/questions/16647069/should-i-use-vagrant-or-docker-io-for-creating-an-isolated-environment
  [7]: https://www.youtube.com/watch?v=SW1OXGl3Mck
  
  [8]: https://www.digitalocean.com/community/articles/5-common-server-setups-for-your-web-application
  [9]: http://docs.ansible.com/
  [10]: http://docs.docker.io/
  [11]: http://www.rackspace.com/blog/how-mailgun-uses-docker-and-contributes-back/
  [12]: http://agiliq.com/blog/2013/06/self-testing-fabfile-using-docker/
