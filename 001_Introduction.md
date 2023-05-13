
## Table of Contents

1) Introduction
2) Getting Started
3) Basic examples
4) Debugging GDExtension
5) Contributing _(fix bug, test, commit, push, pull request)_
6) Architecture Overview
7) Building Godot for Debugging

# Introduction

This guide introduces reader to a godot-dlang development, it contains sections for both game and the bindings development and is aimed to help reader getting familiar with contributing to the project.

## Skill requirements

Basic programming and command-line skills is required. This guide itself is not an introduction to programming and we are expecting readers are:
- familiar with one of the language of a C languages family such as C++ or C#
- has some D experience
- understanding OOP paradigm
- is at least familiar with JSON file format structure
- has basic proficiency level in command-line terminal

## What to expect

Before diving in here is an overview of what to expect. Many of the steps described in these recipes is now automated, however as an advanced users or contributors these steps allows to better understand underlying tech.

Note that we will work on a cloned repo instead of dub package because this guide is written for potential contributors.

The guide starts from setting up the required tools, it then guides the reader through how to create godot project and godot-dlang GDExtension from scratch, we then build a overly simplified game component and show how to debug game, we close the tutorial with godot-dlang architecture design overview and building godot for debugging it more efficiently as the official godot releases doesn't have debug symbols with them making debugging experience shallow.

We don't plan writting end-to-end complete guide or anything extra hard, these skills should help reader to understand the workflow without getting into hardcore assembly or ABI details which even though helpful but not strictly necessary.

The guide was originally written using as a reference Issue 121 [Floating point bug](https://github.com/godot-dlang/godot-dlang/issues/121)
