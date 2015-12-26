.. title: Tasks & Issues
.. slug: tasks
.. date: 2015-02-17 07:55:48 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. hidefromnav: true
.. description: 
.. type: text


.. include:: files/rst_helper.txt

Roadmap
=======

No clear roadmap is established. Refer to the tasks below.


Tasks: Issues & ToDo Items
==========================

This is the (non-complete) list of todo items:

Website
------------

* mid-term
    * add git versioning
    * make nicer multiple footnote references
    * 
* long-term
    * integrate the auto-build of the ppa-stats in the build process
    
      * check if last file is older than a month
      * update statistics 
        
    * get a update list from the builder status
        
      * check if package has not been built on https://code.launchpad.net/~pythonxy/+recipes
      * check if all packages have the right upstream version number: https://code.launchpad.net/~pythonxy/+archive/ubuntu/pythonxy-devel


General Issues
--------------

The `Launchpad (LP) <https://launchpad.net/launchpad>`_ platform has quite some issues with importing code from github, especially with repositories converted over or merged from mercurial  [issue_bzr_hg-git]_ and git repositories with submodules  [issue_bzr_submodules]_ .

|rarr| This stalls many packages from being updated or newly packaged at all.

The native git support on LP is still in development [issue_lp_git]_  .


Existing packages
-----------------

.. csv-table:: List of issues with existing packages
   :file: files/tables/pythonxy_ubuntu_tasks_existing.csv
   :delim: ;
   :header-rows: 1
   :stub-columns: 1
   :widths: 10, 10, 10, 10, 10

New packages / potential candidates
-----------------------------------

.. csv-table:: List of potential candidates for new packages
   :file: files/tables/pythonxy_ubuntu_tasks_candidates.csv
   :delim: ;
   :header-rows: 1
   :stub-columns: 1
   :widths: 10, 10, 10, 10, 10, 10, 10, 10
  
.. rubric:: Footnotes


.. [issue_bzr_hg-git] Bazaar_ issue: `hg-git import issues with bzr: non-standard commit headers not supported by bzr <https://answers.launchpad.net/launchpad/+question/264432>`_ ``(bzrlib.plugins.git.errors.UnknownCommitExtra: Unknown extra fields)``

.. [issue_bzr_submodules] Bazaar_ issue: `limitations in Bazaar: repository you are fetching from contains submodules, which are not yet supported. <http://launchpadlibrarian.net/231974004/pythonxy-pythonxy-upstream-jupyter_notebook.log>`_

.. [issue_lp_git] Launchpad_ issue: Git import support not implemented, see `Git code hosting beta <http://blog.launchpad.net/general/git-code-hosting-beta>`_, `bugs for launchpad.net git issue <https://bugs.launchpad.net/launchpad-project/+bugs?field.tag=git>`_, `import external code into a LP git repo (natively) <https://bugs.launchpad.net/launchpad/+bug/1469459>`_, `Please support daily builds via git <https://bugs.launchpad.net/launchpad/+bug/1453022>`_
