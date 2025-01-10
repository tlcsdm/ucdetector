# UCDetector

UCDetector (Unnecessary Code Detector - pronounced "You See Detector") is a eclipse PlugIn tool to find unnecessary (dead) public java code. For example public classes, methods or fields which have no references. UCDetector creates markers for the following problems, which appear in the eclipse problem view:
* Unnecessary (dead) code
* Code where the visibility could be changed to protected, default or private
* Methods or fields, which can be final

Go to UCDetector web site for more screenshots and other information: http://www.ucdetector.org/index.html

# How to install

**Update Site:**

Create a new update site in Eclipse with the following:

* Site name:  ``UCDetector``
* Site URL:   ``https://raw.githubusercontent.com/tlcsdm/ucdetector/master/org.ucdetector.update_site/site.xml``

**Manual Install:**

Download the plugin jar and copy it to Eclipse plugins directory. The jar location is (replace ``<version>``): 
``https://raw.githubusercontent.com/tlcsdm/ucdetector/master/org.ucdetector.update_site/plugins/org.ucdetector_<version>.jar``.   Alternatively, you can download the entire Update Site bundled with everything else in the release link above and create a new update site in Eclipse, pointing to your local directory where you expanded the release.
