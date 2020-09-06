Milestone 1. Project Plan Complete - Test
PROJECT INFO
Software Project Plan - Book Builder

Other Roles - Requirements.md , Design.md , Code.md , Test.md

File: Milestone-1/Test.md

URL: https://github.com/Mark-Seaman/Mark-Seaman.github.io/blob/master/BookBuilder/Milestone-1/Test.md

Documents: Documents/swplan/BookBuilder

Git Repo: Mark-Seaman.github.io

Milestone 1. Project Plan Complete
Role: QA Engineer  Bryan Aguilar - Test

Goal: Test Plan

Outline of testing that will be used
Setup structure for testing
Log issues
Document how to log issues
Book Builder - Test Plan
Each level of the hierarchy produces increasing levels of detail. Test planning should always start at the top and work down. This prevents getting lost in the weeds and running out of time.

A typical medium-sized app can be built in about 1000 hours of engineering time. This means that about 250 hours should be spent on testing. The testing hierarchy acts as a natural budget for how to spent that time.

Testing Levels
This info is not specific to book builder but relates to test planning in general.

Level 1 - Test Plan


High level discussion of testing strategy
Outline the major types of testing that will be done
Manual Acceptance Testing - A person uses the application and observes what happens. The test script describes scenarios that the tester must go through.
Django unit test - Automatic tests that may start with a blank database. These tests can be very fine grained or run the entire system.
Hammer test - These tests execute automatic scenarios that exercise the entire system.
Quick test - The test is only used during development to iterate on a single function.
Page test - This test runs on “requests” Python package and gets web pages from a live server it is used to see if pages on the internet are changing.
Selenium Page test - Firefox and Chrome are used to obtain pages and look for specific HTML elements.
Book Builder testing

Testing will be reduced because of limited time on this project.
Essential testing will include
Manual Acceptance Testing
Quick Tests in development
Page Tests (using "requests" Python package on PyTest)
