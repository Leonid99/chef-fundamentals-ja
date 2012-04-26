This guide describes prerequisites that students should meet in order
to get the most out of Chef Fundamentals.

# General Requirements

Students should be familiar with basic to intermediate system
administration topics including the following:

* Command-line familiarity with Unix/Linux shells or Windows
  Powershell
* System resource concepts like package, service and user management
* Key-based authentication (e.g., RSA/SSH)
* Version control systems (e.g., Git, Mercurial, Subversion)
* Knowledge of cloud computing or virtualization concepts such as
  API-driven compute

Students should have basic working knowledge with at least one third
generation programming language such as Perl, Python, Php or Ruby.

* Basic data structures (string, numbers, array, hash or language
  equivalent)
* Conditionals (if/unless, case)
* Loops (for/foreach, while, or language equivalent)

# Workstation Requirements

Student Exercises will run from a management workstation
system. Students should install non-Chef required software before the
class starts.

* SSH/SCP (OpenSSH, puTTY/WinSCP or equivalent)
* [Git](http://git-scm.org)

On Unix/Linux/OS X systems:

* C/C++ compiler, build environment (`build-essential`, Xcode, or
  platform equivalent).

If Chef is not already installed, use [Opscode's Full Stack Chef
installer](http://www.opscode.com/chef/install). This will also be
covered during the introductory portion of the course.

### Mac OS X Users

**If you do not already have Xcode installed**

Recently, Apple made Xcode 4.3's command-line tools available as a
separate download from the full Xcode package. If you do not already
have Xcode installed, you can use this installation instead, as it is
a 165Mb download instead of several gigabytes. Log in with your Apple
ID here:

* https://developer.apple.com/downloads/index.action

And select, "Command Line Tools for Xcode" to download the dmg.

## Additional Requirements

The instructor may provide virtual machine image(s) in the form of a
VMDK format disk image which will be the target system(s) to configure
with Chef during the hands on exercises. This can be imported into
VMware Fusion, Player or Workstation, or otherwise indicated by the
instructor. The image should be downloaded before the course starts,
and imported into the virtual machine hypervisor as indicated by the
instructor.

They will also provide additional details such as the platform of the
virtual machine, and the login information.

# Chef Server Requirements

Students may already have a Chef Server, whether it is Opscode Hosted
Chef, Opscode Private Chef or an Open Source Chef Server. The
exercises in the course will focus on using Opscode Hosted Chef unless
otherwise prior arrangements have been made by the instructor with the
students.

## Sign up for Opscode Hosted Chef

It is recommended that students do not use the same Chef Server that
their production infrastructure might be using. It is relatively quick
and easy to sign up for Opscode Hosted Chef, so this is done during
the first exercises of the course. Students are welcome to sign up
ahead of time. The signup process will also provide instructions how
to set up an organization which you will use for your Chef
Server. When creating the organization, select the Free trial, which
you may continue to use for free for further studies and to manage up
to 5 nodes when the class is over.

* http://www.opscode.com/hosted-chef/

# Need Help?

If you are taking this course from Opscode directly and need help or
have questions above this document, please email support@opscode.com with
"Chef Fundamentals Prerequisites" in the subject line.

If you are taking this course from an independent Chef Fundamentals
trainer, contact your instructor for assistance.
