Documentation
============
Visit the documentation at: [Latest Documentation][id1]


What is in this POM project?
==========

This is a comprehensive master pom for use with Maven projects.  It is based off of Maven 3.0 reporting and plugin structure.

This POM contains configurations the following plugins and should be considered "active":

-  maven-antrun-plugin
-  maven-assembly-plugin
-  maven-changelog-plugin
-  maven-checkstyle-plugin
-  maven-clean-plugin
-  maven-compiler-plugin
-  maven-dependency-plugin
-  maven-deploy-plugin
-  maven-eclipse-plugin
-  maven-enforcer-plugin
-  maven-failsafe-plugin
-  maven-install-plugin
-  maven-jar-plugin
-  maven-javadoc-plugin
-  maven-jxr-plugin
-  maven-pmd-plugin
-  maven-project-info-reports-plugin
-  maven-release-plugin
-  maven-resources-plugin
-  maven-scm-publish-plugin
-  maven-site-plugin
-  maven-source-plugin
-  maven-surefire-plugin
-  maven-surefire-report-plugin
-  codenarc-maven-plugin
-  findbugs-maven-plugin
-  taglist-maven-plugin
-  versions-maven-plugin
-  cobertura-maven-plugin (Commented out by default, look at POM for syntax, but must implement in child of parent POM)


NOTE: Most plugins can be skipped with simple helper properties found at the bottom of the <properties/> section in the POM (ex: <checkstyle.skip>fasle</checkstyle.skip>

NOTE: Review the [Latest Documentation][id1] for setup/requirements to use Checkstyle and PMD



Credits
===========
The documentation publishing was created for [How to publish maven site docs to BitBucket and GitHub](http://www.ensor.cc/2013/01/how-to-publish-maven-site-docs-to.html "How to publish maven site docs to BitBucket and GitHub")

The POM is available in Maven Central.  Example usage


    <parent>
        <groupId>com.clickconcepts.project</groupId>
        <artifactId>master-site-pom</artifactId>
        <version>0.17</version>
    </parent>


[id1]: http://mike-ensor.github.com/clickconcepts-master-pom "Latest documentation for master POM"