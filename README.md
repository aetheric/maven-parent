# Maven Parent: Lombok

Reticent to put Lombok in the java parent itself, I opted to have a sub-parent do my dirty-work for me. This parent
keeps track of the current version of lombok, and the plugin used to convert that lombok-y goodness into Java.