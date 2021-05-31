ARCHIVED
========

This project is no longer maintained. 

Jenkins has moved quite a bit since this was written, and a declarative pipeline would be the preferred way of doing this now.

---

Docker Jenkins Build Pipeline Template
======================================

This is a Jenkins pipeline to build
https://github.com/deweysasser/docker-project-template.  It is
intentionally generic enough that it can be used directly as the build
pipeline for projects that match the make target protocol above, or it
can be used as a base project for modifications.

Why is the Jenkinsfile not checked in directly to the
docker-project-template?  Because your Jenkins might be different from
my Jenkins, and you (or I) might want to work on the build pipeline
separate from the code it builds (or deploys).
