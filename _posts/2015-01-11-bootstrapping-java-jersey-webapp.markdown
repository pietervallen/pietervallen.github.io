---
layout: post
title:  "Bootstrapping a jersey REST API with Maven"
date:   2015-01-11
categories: blog jersey java rest maven war
---
I needed a REST API to experiment with in Java running in a Tomcat container. I found this way to do it:
{% highlight bash %}
mvn archetype:generate -DarchetypeCatalog=http://download.java.net/maven/2
{% endhighlight %}
A menu follows and you select option 3:
{% highlight bash %}
Choose archetype:
1: http://download.java.net/maven/2 -> com.sun.jersey.archetypes:jersey-quickstart-grizzly (Archetype for creating a RESTful web application with Jersey and Grizzly)
2: http://download.java.net/maven/2 -> com.sun.jersey.archetypes:jersey-quickstart-grizzly2 (Archetype for creating a RESTful web application with Jersey and Grizzly 2.x)
3: http://download.java.net/maven/2 -> com.sun.jersey.archetypes:jersey-quickstart-webapp (Archetype for creating a Jersey based RESTful web application with WAR packaging)
4: http://download.java.net/maven/2 -> com.sun.jersey.archetypes:jersey-quickstart-ejb (Archetype for creating a Jersey based RESTful EJB application with WAR packaging)
5: http://download.java.net/maven/2 -> com.sun.faces:simple-jsf (Archetype for creating a simple JSF project)
6: http://download.java.net/maven/2 -> com.sun.faces.regression:i_jsf_XXXX-archetype (Archetype for mojarra JSF regression tests)
Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): :
{% endhighlight %}
Just fill in you project stuff and off you go!
