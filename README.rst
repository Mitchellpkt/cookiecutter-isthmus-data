Data visualization & analysis template
======================================

This cookiecutter creates a project with general data science requirements (python/jupyter), extant directory structure for data (local & version cnotrolled) and analysis, along with demo data + notebook that carries out the first several steps of exploring numeric data.

Isthmus // Mitchell P. Krawiec-Thayer

Video demo: https://youtu.be/3NfkUkI3msA

Create template from cookiecutter
---------------------------------

Depending on your setup, either 

.. code:: bash

	cookiecutter https://github.com/Mitchellpkt/cookiecutter-isthmus-data.git

or

.. code:: bash

    python3 -m cookiecutter https://github.com/Mitchellpkt/cookiecutter-isthmus-data.git
    
Prepare environment
-------------------
    
After you have cloned a repository and created your environment,

.. code:: bash

    pip install -r requirements.txt
    
and/or 

.. code:: bash

    pip install -r requirements_dev.txt
    
Go forth and explore
--------------------

Exploratory data visualizations have been carried out in the jupyter notebook at

.. code:: bash

    /analysis/analysis.ipynb
    
To swap in your own data for analysis, see

.. code:: bash

    /data/version_controlled      # use for small & non-sensitive data    
    /data/local_only              # excluded from repo via .gitignore

    
Comments
--------

Enjoy!

Questions / comments / suggestions? contact cookiecutter-isthmus-data@mitchellpkt.com
