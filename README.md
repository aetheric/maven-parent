# Maven Parent: Lombok [![Build Status](https://aetheric.ci.cloudbees.com/buildStatus/icon?job=maven-parent-lombok)](https://aetheric.ci.cloudbees.com/job/maven-parent-lombok/)

Reticent to put Lombok in the java parent itself, I opted to have a sub-parent do my dirty-work for me. This parent
keeps track of the current version of lombok, and the plugin used to convert that lombok-y goodness into Java.
