# Introduction

Our company operates in an exciting and fast-growing industry. This implies work under considerable time pressure and rapidly changing business requirements. The following exercise has been designed to mimic this type of environment. Therefore, the requirements are deliberately ambiguous and the time limit is capped at 3 hours.

You are *not* expected to complete all of the requirements within this time frame (including those yielding extra points). Instead, it's an opportunity to discuss the way you prioritise requirements and the trade-offs you have to make to meet the deadline. However, we do expect you to show off your engineering talents along the way :)

The exercise will be followed by a 30-minute debrief session via Skype. We will discuss issues, challenges and engineering decisions you have made while working on this task.

## Requirements

The task is to create a simple Rails-based application that will download images from user-specified URLs and present the user with the results. 

**User story**. As a content editor, I need to keep information on our website up-to-date. Once I receive an update from one of our data providers, I amend our records accordingly. In order to that, I visit a page hosted by our data provider and copy some of its contents. The text bits are easy, but image files are painful to handle. I have to download, convert, and upload them back to our file vault. I would like have a system that accepts any URL (such as [this](http://www.colliersproperty.co.uk/industrial-for-sale/lisburn/23272)), downloads sufficiently large images found on that page, and uploads new ones (i.e. no duplicates) to our file vault.

## Limitations:

- front-end should consist of a *single* page, it’s up to you to decide how to present the results
- database choice is restricted to sqlite
- there are no restrictions on the use of 3rd party libraries
- the result should be published in a publicly available GitHub repository

## Things to consider

The primary objective is designed to take no more than 20 minutes. After that, you are welcome to invest your time into any of the extra requirements listed below. In any case, *do not proceed* beyond the 3-hour deadline - that is the maximum alloted time frame for this task.

## Bonus points for…

- deployment-ready setup with a tool of your choice
- code tests with a tool of your choice
- image conversion (to a standardised format)
- security considerations (network-related, input sanitisation)
- business-level logging 
- whatever else you deem important

## File vault

Our vault resides on S3. The credentials below will provide you with read and write privileges:

- access key ID: `AKIAJO63N3IAREEVHTKA`
- secret key: `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`
- bucket name: `ideals-recruitment-task`

