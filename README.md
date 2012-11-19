maven-tomcat-jenkins
====================

Its a   small  hello   world project    for  folks  starting to use  Jenkins  for   CI 


Getting Started  
====================

Prerequisite  :   Make  sure  that   you   have  java  installed  on your dev  box  .

Step  0  :
=======
Before  using   CI  it   is  always  better   to  do a   small  console check  for  your  preoject  .  Maven  provide   an  unique  functionality
called  archetypes   which can help    you  generate   some   hello   world  projects on  various   Java  based  Application
Platform .  

C:\Users\pdam>mvn  archetype::generate
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building Maven Stub Project (No POM) 1
[INFO] ------------------------------------------------------------------------
[INFO]
[INFO] >>> maven-archetype-plugin:2.2:generate (default-cli) @ standalone-pom 
[INFO] Generating project in Interactive mode
---   A long  List  of   archetypes  ---

Lets   choose  a  basic  tomcat  application  which  needs   to be  deployed  on a  tomcat instance as a    war 

Its   is   called   tomcat-maven-archetype  and  is   a   complete  service oriented ,layered   tomcat  application  

It  has   5  submodules  

      basic-api    Interface for   a  REST  Based  API  service  
      basic-api-impl   Implementation  of  basic-api
      basic-webapp     A  set of   HTML /JSP  Pages   where  the  service is  calle 
      basic-webapp-exec   A   binary  bundle  with   application  embeeded  as  1   war  in   tomcat 
      basc-webapp-it   Selenium   Functional  Tests    to  run   it 


      


