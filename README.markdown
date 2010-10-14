# Getting started

First time I used this to install all dependencies:

    ant -Divy=true -Dgems=true

After that I run `ant` to run the cucumber scenarios.    

# Dependencies

* Ivy 
* Ant

# FAQ

## How to install Ivy

1. Checkout the project

    svn co https://svn.apache.org/repos/asf/ant/ivy/core/trunk ivy
    
2. Build Ivy with Ant

    cd ivy
    ant jar

3. Marry Ant with Ivy

Given `ANT_HOME=/usr/share/ant`, copy the ivy jar to the `ANT_HOME/lib`.

    cp build/artifact/org.apache.ivy_2.2.0.final_20101013172528.jar $ANT_HOME/lib/
