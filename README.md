Mini Project1 - Text Analysis
===========

Please read the entire assignment.

Workflow
===============
1. To start, [**fork** repository][forking] [github.com/fdac22/MiniProject1][assignment]
    1. Go to github.com/fdac22/MiniProject1
    1. Click on "Fork Repository" button
	1. Select your GitHubID as the organization to fork to
	1. Go to Settings and enable issue tracking
1. Connect to your docker container
1. [**Clone**][ref-clone] the forked repository to your docker container

     ```
     git clone https://github.com/YourGHUsername/MiniProject1
     ```
1. Copy [Miniproject1.ipynb](https://github.com/fdac22/MiniProject1/blob/master/MiniProject1.ipynb) to YourUTKID.ipynb

       ```
       git add YourUTKID.ipynb
       git commit -m "YOUR commit message"
       ```
1. Now back in the shell [**Push**][ref-push]/sync the changes to github.

	git push

1. At https://github.com/YourGHUsername/Miniproject1
   Create a [**pull request**][pull-request] on the
   original repository [fdac22/Miniproject1][assignment]  to
   turn in the assignment.


Social Workflow with deadlines
==============================

1. Do the first four steps listed above before the class on Sep 8: if you have any
   issues, we need to clarify them before Sep 8.
1. Come up with an idea of what analysis you are going to use and
   what data sources you will use. Discuss it with your assigned peer on Sep 8.
   You present the idea to your peer next to you in the list of groups and you
   produce a comment for the peer before you in the group list below. 
   The first person  comments on the presentation of
   the last person and the last presents to the first.  To access your peer's forked repository, manually enter the url:
   https://github.com/YourPeersGHUsername/Miniproject1
   The mapping of the GH ids to UTK IDs is in https://github.com/fdac22/students/blob/master/NetID2GHID.md 

When you raise an issue, you should assign it to the GHUSER who should comment on it.
1. Start doing the analysis and discuss your progress with your peer
   so that you are done before class on Sep 10. In case you encounter any problems
   retrieving, storing, or analyzing data please discuss them with
   your peer and, if needed, escalate.
1. Prepare a few slides (or a jupyter notebook) explaining the approach and findings and
   present to a small group as specified below.
1. We will have the entire class on Sep 13 for you to practice
   presentations in several groups as shown in https://github.com/fdac22/students/blob/master/TeamingAnalysis.ipynb

    
At the end of the presentations within the group a vote will be held (by that group) for one presentation 
to be selected for the presentation to the entire class. The first person listed in each group will record that in the issue 
https://github.com/fdac22/Miniproject1/issues/1


What operational data traces are expected
==
1. I expect you to make at least one commit (in your cloned
   repo) by Sep 8 and at least three by Sep 13.
1. Each interaction with your peer should result in an issue that
   describes your peers comments. You should raise at least one issue against your peers repository peer/Miniproject1 (see above), and you should make at least one commment on the issue raised against your fork (you/Miniproject1). 

Presentations should include
===
* What is the question?
* What was the approach?
* What problems did I encounter?
* What results did I get?
* What new ideas did this generate?


<!-- Links -->
[assignment]: https://github.com/fdac22/Miniproject1
[forking]: https://guides.github.com/activities/forking/
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[ref-clone]: https://help.github.com/en/articles/cloning-a-repository
[ref-commit]: https://readwrite.com/2013/10/02/github-for-beginners-part-2/
[ref-push]: https://help.github.com/en/articles/pushing-commits-to-a-remote-repository
