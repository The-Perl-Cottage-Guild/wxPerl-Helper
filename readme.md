# Martha

A Sister of _the Perl Lazarus Project_

---

## The Perl Lazarus Project

There is no direct equivalent to Free Pascal's Lazarus IDE in the Perl ecosystem.

In practice, building GUI applications for Windows in Perl requires assembling a working stack:

* Strawberry Perl
* wxPerl
* wxGlade
* Packaging tools like `pp` / `wxpar`
* Installer systems such as Inno Setup

These pieces work—but they are not unified.

> **The Perl Lazarus Project** is an effort to:
>
> * Identify a *working, modern stack* for Perl GUI development on Windows
> * Provide clear, practical guidance for setting it up
> * Bridge the gaps between development → packaging → distribution

---

## Where Martha Fits

**Martha** is the packaging and deployment component of this effort.

While the broader project defines the stack and workflow, Martha focuses on:

> Turning a working wxPerl application into a distributable Windows program.

---

## Summary

This tool assists with the creation of **distributable Perl applications for the Windows environment**, with a focus on wxPerl GUI applications.

---

## Status

Functional, and evolving through real-world use.

This tool is developed alongside actual GUI projects, so improvements are driven by practical needs rather than theory.

<img width="954" height="612" alt="image" src="https://github.com/user-attachments/assets/2d340de4-c4e2-468b-bbee-4bd03961f5a9" />

---

## Features

* Save Makefile
* Load Makefile
* Generate Makefile (DLL discovery workflow)
* Run Makefile
* Run compiled `.exe`
* Run Inno Setup Compiler (see Makefile integration)
* Run installer `.exe`
* Load project file
* Save / Save-As project file

---

## To Do

* Add EXE icon support
* Improve project file format (capture full build + packaging state)
* Better integration between tabs (currently partial)
* Add Windows-style Help system in the Help tab
* Expand documentation and in-app guidance

---

## Background

If you're familiar with packaging wxPerl applications on Windows, you may remember older tools like [Citrus Perl](http://www.citrusperl.com/p/about.html).

Those tools are no longer maintained.

The goal here is different:

* Start with a **known working Strawberry Perl environment**
* Use modern tools where available
* Provide a **practical, reproducible path** to building and distributing applications

Martha exists to fill the packaging gap in that workflow.

---

## Environment Guide

Click here for the full setup guide:

https://wiki.perl-guilds.net/index.php?title=Developing_and_Distributing_wxPerl_Applications_on_Windows

This includes:

* Setting up Strawberry Perl
* Using wxPerl and wxGlade
* Understanding the development workflow
* Preparing applications for packaging

---

## Philosophy

This project is built around a few simple ideas:

* Practical over theoretical
* Real workflows over idealized ones
* Tools that help you **ship software**, not just write it

---

**Screenshots**

<img width="954" height="612" alt="image" src="https://github.com/user-attachments/assets/2d340de4-c4e2-468b-bbee-4bd03961f5a9" />

<img width="956" height="608" alt="image" src="https://github.com/user-attachments/assets/191e5667-e21f-493f-8384-405aae977299" />

















