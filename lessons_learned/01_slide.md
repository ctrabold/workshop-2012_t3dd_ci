!SLIDE new-chapter center

# How much QA <br/>do we already have?

!SLIDE

# [ci.typo3.org](http://ci.typo3.org)
# [metrics.typo3.org](http://metrics.typo3.org)


!SLIDE center

![Jenkins](jenkins.png)
# [ci.typo3.org](ci.typo3.org)
## aka "The Worker"


!SLIDE

.notes Checks like Code Sniffer, PMD

# commit > check > +1 / -1
## for TYPO3 v4 Core master


!SLIDE

# Example check

	# Check Coding Style
	phpcs --extensions=php,inc --report=checkstyle
	  --report-file=build/logs/checkstyle.xml .


!SLIDE

# TER-Upload > [metrics.typo3.org](http://metrics.typo3.org)
## for TYPO3 Extensions


!SLIDE

# Example metrics
## % of comments
## CGL Violations


!SLIDE

# Job Overview
## [https://ci.typo3.org/view/TYPO3/view/Core/](https://ci.typo3.org/view/TYPO3/view/Core/)


!SLIDE center sonar

.notes We can only improve things we see

![Sonar](sonar-logo.png)
# [metrics.typo3.org](http://metrics.typo3.org)
## aka "The Dashboard"


!SLIDE

# Collect code metrics

* Find Hotspots in Code
* Developers can improve code
* _We can only improve things we see_
