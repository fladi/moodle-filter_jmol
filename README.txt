This is a very simple filter taking advantage of the excellent open-source 
"Jmol" molecular visualisation project (http://jmol.sourceforge.net). 
The filter includes some some basic controls and help files.

Installation from tar.gz:

1. Unpack the .zip or .tar.gz download.
2. Copy the /jmol folder (and all its contents) located inside the /filter
   folder to the equivalent location inside the /filter folder of your Moodle 2.0.x
   installation i.e. alongside the folders for other filters

Installation from Git:

cd <moodle2>/filter
git clone git://github.com/fladi/moodle-filter_jmol.git jmol

Remember to activate the filter in Moodle's filter admin screen. 
Depending on settings, you may need to activate this filter in individual Moodle
courses.

There is a sample file included, "manywater.pdb" which can be used for test
purposes. Simply add a link to ../filter/jmol/manywater.pdb into a course to try
it out.




