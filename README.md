# Collaborative-Text-Editor
PiEdit is a collaborative (multi-user) plain text document editor using Raspberry Pi 2 LAN. It uses Django RestFramework in backend and AngularJS and JQuery to manipulate DOM elements 

##
How does it work?
It uses Publish and Subscribe Pattern, using crossbar.io client in With the Publish & Subscribe pattern, application components subscribe to topics to get notified when other components publish to these topics.

A Editor publishes data on a topic to Crossbar.io client, and the router dispatches events to all editors which are presently subscribed to the topic.

Using the Publish & Subscribe pattern allows your application editors to distribute information to other editors in real-time.

##Technologies Used
 * Front End: HTML, CSS, AngularJs, JQuery and Bootstrap
 * Backend:  Django, Crossbar.IO
 * Icons : Font Awesome (https://fortawesome.github.io/Font-Awesome/ )

##Architecture Diagram
 ![picture alt](http://www.sejalgupta.com/marketplace/img/architecture.png "Title is optional")
 
##Functionality Overview
 * User Login.
 * Guest User Access.
 * Multiple User collaborative text editor.
 * Editor Save.
 * User History.

