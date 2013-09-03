*First steps

JAVA_HOME=/usr/lib/jvm/java-openjdk
export GRAILS_HOME=~/grails-2.2.4
export PATH="$PATH:GRAILS_HOME/bin"

cd gtunes 
git init
grails integrate-with --git  # will generate a good .gitignore file
git add .gitignore
git add .classpath .project 
git add *
git commit -m "initial commit"

