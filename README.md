#SB&G Device Automation Test

##Introduction
Welcome to the Sky Betting & Gaming Technical Test!

We hope that you find this exercise fun and interesting. We want to see your solution to a simple problem with well thought-out and well structured code. We realise that there are a lot of topics in the brief and that you may not have the experience or time to complete them all. There is no time limit on how long you spend on the test. When you've produced something you're proud of, send it to us. We may then ask you to do some further work on a certain area or invite you to a face to face interview. In this interview you'll continue developing what you've started, so it's worth being familiar with the topics listed.

##The Brief
The product team would like to augment manual device testing with an automation testing framework using Appium. Automation can give us a suite of repeatable tests to augment existing CI processes.

There are no language specific requirements however we request that you do not use a pre-existing framework such as Nightwatch, Codeception and rather use Selenium in conjunction with Appium or straight Appium to drive a mobile device.

The aim of this exercise is to establish how well you know Appium and on-device automation testing in general rather than your ability to write a comprehensive framework solution. Stability of tests from well structured and easily maintainable code should be considered.

The product team expectation is that the framework can be utilised across as many portals as possible and integration should be as pain-free as possible, therefore adherement to SOLID principles is highly recommended. Code should be able to be used on any environment and not hard coded to perform a specific task in the specified portal.

Once a working framework has been produced, consider how this framework could be used in a continuous integration pipeline. On device automation testing, in general, is pretty slow compared to desktop browser automation. How easy would it be to incorporate parallel execution into the framework using something like Docker and a device bar for example? This should inform the structure of your deliverable but is not in scope for this task.   

##Acceptance Criteria

The Framework must be used to automate a login journey for https://www.skyvegas.com on a mobile device. 

Your tests must demonstrate loading the homepage of Sky Vegas. 
Opening of the Account bar.
Interaction with the Account bar.
Automation of the login form.
Verify that the account has logged in to the portal. 
Log the account out.

Extra credit: 2+ additional tests for journeys of your choice. 

##The Deliverable 
 
A bundled/archived repository showing your commit history. Git is preferred, but any VCS is fine. Git example:

	git bundle create <yourname>.bundle --all --branches

A covering note explaining the technology choices you have made.

Any instructions required to run your solution
