# gdi2b2d
Using blend2d as backend to GDI calls

blend2d (https://blend2d.com) is a high performance 2D vector graphics library.  It has a few novel approaches to rendering, which puts it in the class of AGG, Cairo, Skia, and others.  This repository is an exercise to demonstrate whether blend2d could be a backend to a GDI front end.  It would live in the space where you're rendering into an in-memory context with GDI.
