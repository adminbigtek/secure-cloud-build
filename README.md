Overview
Software vulnerabilities are weaknesses that can cause an accidental system failure or provide bad actors a means to compromise your software. Artifact Analysis provides two kinds of OS scanning to find vulnerabilities in containers:

The On-Demand Scanning API allows you to manually scan container images for OS vulnerabilities, either locally on your computer or remotely in Artifact Registry. This gives you granular control over the containers you want to scan for vulnerabilities.
The Container Scanning API allows you to automate OS vulnerability detection, scanning each time you push an image to Artifact Registry. You can use On-Demand Scanning to scan images in your CI/CD pipeline before deciding whether to store them in a registry. Enabling this API also enables language package scans for Go and Java vulnerabilities.
In this lab you'll learn how to build and scan for vulnerabilities conainer images stored in Artifact Registry wth Cloud Build.

What you'll learn
In this lab you'll:

Build Images with Cloud Build
Use Artifact Registry for Containers
Utilize automated vulnerability scanning
Configure On-Demand Scanning
Add image scanning in CI/CD in Cloud Build
Setup and Requirements
